LongTask API provides utility features for long and asynchronous task execution.

The API can be used by any module to provide a safe way to execute a task in a background thread with native progress and cancellation support, as well as error management.

It is currently used in various modules, including:

- Import
- Generate
- Statistics
- Layout

## Architecture

- An interface LongTask, which for instance Statistics or Generator would implement
- An LongTaskExecutor for executing a cancellable and progressable single task.
- A ProgressTicket long task implementations uses for notifying their progress to the exterior

It fits in our architecture like this:

- Business tasks like Generator or Statistics implements LongTask. Implementations could completely ignore it if they want.
- Controllers uses LongTaskExecutor to manage execution of tasks. They are not forced to execute LongTask through a LongTaskExecutor.
- If UI is available the ProgressTicket will connect to the Netbeans classical Progress API and Platform's statusbar. If not it remains UI free.

## LongTask

```java
public interface LongTask {
 
    /**
     * Cancel the task. Returns <code>true</code> if the task has been sucessfully cancelled, <code>false</code> otherwise.
     * @return  <code>true</code> if the task has been sucessfully cancelled, <code>false</code> otherwise
     */
    public boolean cancel();
 
    /**
     * Set the progress ticket for the long task. Can't be null.
     * @param progressTicket the progress ticket for this task
     */
    public void setProgressTicket(ProgressTicket progressTicket);
}
```

## LongTaskExecutor

Internally, uses a java.concurrent.ExecutorService.

An unique executor is used for executing several tasks. However only one task can be executed in the same time.

Use LongTaskListener to get notified when a task is finished 

## Example

We assume Generator implements LongTask. The following code is from DesktopGeneratorController:

```java
executor.execute(generator, new Runnable() {
   public void run() {
      generator.generate(container.getLoader());
   }
},taskname);
```

## ErrorHandler

When executing a task in a executor through a Runnable, Exceptions are not normally retrieved, the task just terminate. Too avoid this and reveal exceptions when executing, provide an LongTaskErrorHandler to the execute method. An error handler example, which shows a dialog when an exception is catched:

```java
//Error handler
LongTaskErrorHandler errorHandler = new LongTaskErrorHandler() {
   public void fatalError(Throwable t) {
      NotifyDescriptor.Exception ex = new NotifyDescriptor.Exception(t);
      DialogDisplayer.getDefault().notify(ex);
   }
};
```

Only one thing to be careful, don't catch exceptions and return in the Runnable given to the exector. Always rethrow exceptions to allow the executor finish the progress and return. Example of good practice:

```java
executor.execute(task, new Runnable() {
   public void run() {
      try {
         textImporter.importData(reader, container.getLoader(), report);
         finishImport(container);
      } catch (Exception ex) {
         **throw new RuntimeException(ex);**
      }
   }
}, "Import " + fileObject.getNameExt(), errorHandler);
```

## When you are not sure a task implements LongTask

The task executor can still be used with ease:

```java
LongTask task = null;
if (importer instanceof LongTask) {
   task = (LongTask) importer;
}
executor.execute(task, new Runnable() {.....
```

LongTaskExecutor supports **null** task. The runnable will be executed normally but without progress and cancel support.

## Javadoc

[Javadoc API](http://gephi.org/docs/api/org/gephi/utils/longtask/api/package-summary.html)

[Javadoc SPI](http://gephi.org/docs/api/org/gephi/utils/longtask/spi/package-summary.html)