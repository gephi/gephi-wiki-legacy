General API that defines the graph structure.

### Overview

API is providing a complete graph data structure that has the following features:

- Directed, Undirected and Mixed graphs support
- Easy iterable structure
- Thread-safe
- Hierarchical graphs, graphs within graphs support
- Automatic meta-edges calculation
- Subscribe to graph events
- Multi-view, host sub graphs

The Graph interface has classical features needed for graph algorithms and is simplifying accesses by returning NodeIterable and EdgeIterable. The internal data model is flexible with the type of graph (directed, undirected or mixed) and allows getting any type of graph regardless to its nature. For instance it’s totally possible to get an undirected graph, even if all edges are directed and the contrary.

No convert operations have to be executed because Graph interfaces are only assessors. All Graph interfaces (DirectedGraph, UndirectedGraph, HierarchicalGraph, ...) can be get from the graph model.

Therefore on the client side, GraphModel is the only object to keep in memory. For instance to iterate over nodes, you first ask for a new Graph object to the model and then call getNodes().

The structure is securized by a read-write lock. That means multiple threads can read the graph at the same moment, but writing is exclusive. If a thread is currently updating the graph, readers have to wait. Most of the time the locking will be transparent but it can also be controlled for more advanced operations.

This graph structure API differs slightly from others about hierarchical graphs and propose an efficient automatic meta-edges calculation. The fundamental idea is that the hierarchy defines a tree of nodes and a marker for each node to flatten the representation. A marked node cannot have any ancestor or descendants be marked as well. When a node is unmarked and his children are marked we call this expand. The contrary operation is retract. The expand and retract operations are available in the API, and let users navigate in multilevels graphs with ease. Therefore group of nodes is unified in the model, and represents a node that has children in the hierarchy. When a node is not a leaf, it is called a meta-node. In addition, users can access meta-edges that comes from the current expand/retract positioning. Meta-edges are edges that connects group of nodes according to edges between nodes. If computed manually, that would require costly procedure. The hierarchical graph support currently has only a single limitation: a node can only have one parent.

The multi-view support allows defining views on the graph and thus creating sub-graphs. The API proposes, for a GraphModel to have several GraphView on the same nodes and edges. One can get graphs exactly in the same way on sub-graphs than on graphs, and therefore execute the same operations.

[Javadoc](http://gephi.org/docs/api/org/gephi/graph/api/package-summary.html)