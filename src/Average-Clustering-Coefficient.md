The clustering coefficient (Watts-Strogatz), when applied to a single node, is a measure of how complete the neighborhood of a node is. When applied to an entire network, it is the average clustering coefficient over all of the nodes in the network.

### Objective

The clustering coefficient, along with the mean shortest path, can indicate a "small-world" effect.
For the clustering coefficient to be meaningful it should be significantly higher than in version of the network where all of the edges have been shuffled.

### Description

The neighborhood of a node, u, is the set of nodes that are connected to u. If every node in the neighborhood of u is connected to every other node in the neighborhood of u, then the neighborhood of u is complete and will have a clustering coefficient of 1. If no nodes in the neighborhood of u are connected, then the clustering coefficient will be 0.

### Source code

See org.gephi.statistics.plugin.ClusteringCoefficient.java.

### Acknowledgements

This code was implemented by Patrick McSweeney.

### Implemented Algorithm

Matthieu Latapy, [Main-memory Triangle Computations for Very Large (Sparse (Power-Law)) Graphs](http://www-rp.lip6.fr/~latapy/Triangles/), in Theoretical Computer Science (TCS) 407 (1-3), pages 458-473, 2008. PDF

### Other References

Watts, D.J., Strogatz, S.H.(1998) Collective dynamics of 'small-world' networks. Nature 393:440-442. [PDF](http://tam.cornell.edu/SS_nature_smallworld.pdf)

### Additional Reading

- [Wikipedia](http://en.wikipedia.org/wiki/Clustering_coefficient)