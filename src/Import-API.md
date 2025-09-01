Import API/SPI provides the **import workflow** to import data form any support.

API is providing a secure workflow, from importers that connects to the data source (files, databases, spigots...) to the processors that append imported data to the workspace. It is based on the `Container` interface, that has a loading and unloading sub-interface. Importers are loading the container, then the controller is checking it's consistency and finally processors are unloading it.

See [org.gephi.io.importer.spi](http://gephi.org/docs/api/org/gephi/io/importer/spi/package-summary.html) package to know how to define new data importers.

[Javadoc API](http://gephi.org/docs/api/org/gephi/io/importer/api/package-summary.html)

[Javadoc SPI](http://gephi.org/docs/api/org/gephi/io/importer/spi/package-summary.html)