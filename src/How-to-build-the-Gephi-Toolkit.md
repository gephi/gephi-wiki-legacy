This helps you to build the latest version of the Gephi Toolkit from the source code. If you just want to use a toolkit release, you can download it [here](http://gephi.org/toolkit/).
The Gephi Toolkit is based on exactly the same source code as Gephi is, it is just a different way to select and packages modules.

## Build Toolkit

### Command-line

Go to the source code root folder, where build.xml file is and type in a command-line

``ant toolkit``

That compiles and builds all modules and package the final JAR in the toolkit folder. You need to have ANT installed, with version >= 1.8.

### From Netbeans

* As explained in [[How to build Gephi]], open Gephi project in Netbeans.
* Expand the project and then **Important Files**.
* Right click on **Build script**, select **Run target** and finally **toolkit**.

Got to the **toolkit** directory that has just been created in the source directory to get the toolkit JAR.

## Build Toolkit Javadoc

The toolkit Javadoc is the same as the [Gephi API](http://gephi.org/docs/api/) + some 'Plugin' modules accessible from the Toolkit.
To build the toolkit Javadoc, use the *toolkit-javadoc* target

``ant toolkit-javadoc``
