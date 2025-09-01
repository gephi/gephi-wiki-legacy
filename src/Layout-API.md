Layout API/SPI provides real-time layout algorithms execution.

The API let users control execution of a layout algorithms. It also gathers various information about an algorithm to present it to the user in a pleasant way.

How must a Layout algorithm look like is defined in the `org.gephi.layout.spi` package. Layout algorithm have access to the graph structure and can define properties users can change in real-time when algorithm is running. Utility graph transformations like Random or Rotate can also be defined as Layout algorithms.

[Javadoc API](http://gephi.org/docs/api/org/gephi/layout/api/package-summary.html)

[Javadoc SPI](http://gephi.org/docs/api/org/gephi/layout/spi/package-summary.html)