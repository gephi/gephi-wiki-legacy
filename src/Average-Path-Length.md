The average graph-distance between all pairs of nodes.

### Description

Connected nodes have graph distance 1. The diameter is the longest graph distance between any two nodes in the network. (i.e. How far apart are the two most distant nodes).
Two measures derive from the distance: [Betweenness Centrality](https://github.com/gephi/gephi/wiki/Betweenness-Centrality) and [Closeness Centrality](https://github.com/gephi/gephi/wiki/Closeness-Centrality).

### Source code

See org.gephi.statistics.plugin.GraphDistance.java.

### Acknowledgments

This code was implemented by Patrick McSweeney.

### Implemented Algorithm

Ulrik Brandes (2001). [A faster algorithm for betweenness centrality](http://www.cs.ucc.ie/~rb4/resources/Brandes.pdf)

### Reference

- Albert, R., and Barabasi, A.-L. (2002) Statistical mechanics of complex networks. Review of Modern Physics 74:47-97. [PDF](http://www.cs.unibo.it/babaoglu/courses/cas/tutorials/rmp.pdf)
- Newman, M.E.J. (2003) The structure and function of complex networks. SIAM Review 45:167-256. [PDF](http://www-personal.umich.edu/~mejn/courses/2004/cscs535/review.pdf)

### Additional Reading

- [Wolfram MathWorld](http://mathworld.wolfram.com/GraphDistance.html)
- [Wikipedia](http://en.wikipedia.org/wiki/Distance_%28graph_theory%29)