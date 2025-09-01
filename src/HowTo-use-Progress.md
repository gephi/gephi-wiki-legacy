Progress management usually come with [LongTask](http://gephi.org/docs/api/org/gephi/utils/longtask/spi/LongTask.html). The LongTask API offers asynchronous tasks execution, as well as progress and cancellation.

When implementing a Importer, Statistics and some others a `ProgressTicket` is given through the `setProgressTicket(ProgressTicket progressTicket)` method of `LongTask` interface.

See [Progress Javadoc](http://gephi.org/docs/api/org/gephi/utils/progress/package-summary.html)

## Progress workflow (indeterminate)

```java
ProgressTicket progressTicket = ...;
 
Progress.setDisplayName(progressTicket, "Task running...");
Progress.start(progressTicket);
...
Progress.finish(progressTicket);
```

Note we use a static class `Progress`, which wraps operations on a ticket. It is preferable to use it instead than directly call the progress ticket. Indeed, the `Progress` static class supports `null` tickets. In that case, failing to get a progress ticket will never throw any `NullPointerException`.

## Progress workflow (determinate)

It shows two variants. Either you always increment the progress by one (Variant A), or specify the unit pointer.

### Variant A

```java
Progress.setDisplayName(progressTicket, "Task running...");
int units = 100;
Progress.start(progressTicket, units);
for (int i = 0; i < units; i++) {
   Progress.progress(progressTicket);
}
Progress.finish(progressTicket);
```

### Variant B

```java
Progress.setDisplayName(progressTicket, "Task running...");
int units = 100;
Progress.start(progressTicket, units);
for (int i = 0; i < units; i++) {
   Progress.progress(progressTicket, i);
}
Progress.finish(progressTicket);
```

## Manually get a ProgressTicket

Here is how to manually get a `ProgressTicket`, when not working with a `LongTask`:

```java
ProgressTicketProvider progressProvider = Lookup.getDefault().lookup(ProgressTicketProvider.class);
ProgressTicket ticket = null;
if (progressProvider != null) {
   ticket = progressProvider.createTicket("Task name", null);
}
```

Instead of `null`, you can provide a `Cancellable` implementation.