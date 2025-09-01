Filters API/SPI provides filtering features, how to create subgraph.

The API let users create and combine filter queries and execute them on the current graph. The aim is to filter the graph (i.e. remove elements according to filter functions). The system works with Graph API and its view concept. New filters can easily be added.

Filters me be defined as explained in `org.gephi.filters.spi`. Difference is made between node filters, edge filters and operators. Categories are a simple way to classify filters in a hierarchy tree for displaying it to users.

[Javadoc API](http://gephi.org/docs/api/org/gephi/filters/api/package-summary.html)

[Javadoc SPI](http://gephi.org/docs/api/org/gephi/filters/spi/package-summary.html)