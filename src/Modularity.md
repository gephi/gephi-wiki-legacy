Measures how well a network decomposes into modular communities. 

### Objective

A high modularity score indicates sophisticated internal structure.
This structure, often called a community structure, describes how the the network is compartmentalized into sub-networks. These sub-networks (or communities) have been shown to have significant real-world meaning.

### Explanation

Randomizing the algorithm can produce a better decomposition resulting in a higher modularity score, however randomizing will increase computation time.

### Source code

See org.gephi.statistics.plugin.Modularity.java.

### Acknowledgments

This code was implemented by Patrick McSweeney.

### Implemented Algorithm

Vincent D. Blondel, Jean-Loup Guillaume, Renaud Lambiotte, Etienne Lefebvre - Fast unfolding of communities in large networks (2008) [PDF](https://arxiv.org/abs/0803.0476)

### Reference

- [Original implementation](http://sites.google.com/site/findcommunities/)