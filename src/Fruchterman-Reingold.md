The Fruchterman-Reingold Algorithm is a force-directed layout algorithm. The idea of a force directed layout algorithm is to consider a force between any two nodes. In this algorithm, the nodes are represented by steel rings and the edges are springs between them. The attractive force is analogous to the spring force and the repulsive force is analogous to the electrical force. The basic idea is to minimize the energy of the system by moving the nodes and changing the forces between them. For more details refer to the Force Directed algorithm.

In this algorithm, the sum of the force vectors determines which direction a node should move. The step width, which is a constant determines how far a node moves in a single step. When the energy of the system is minimized, the nodes stop moving and the system reaches it's equilibrium state. The drawback of this is that if we define a constant step width, there is no guarantee that the system will reach equilibrium at all. T.M.J. Fruchterman and E.M. Reingold introduced a "global temperature" that controls the step width of node movements and the algorithm's termination. The step width is proportional to the temperature, so if the temperature is hot, the nodes move faster (i.e, a larger distance in each single step). This temperature is the same for all nodes, and cools down at each iteration. Once the nodes stop moving, the system terminates.

### Reference

- Fruchterman, T. M. J., & Reingold, E. M. (1991). [Graph Drawing by Force-Directed Placement](http://citeseer.ist.psu.edu/viewdoc/download;jsessionid=19A8857540E8C9C26397650BBACD5311?doi=10.1.1.13.8444&rep=rep1&type=pdf). Software: Practice and Experience, 21(11).

### Source code

`org.gephi.layout.plugin.fruchterman.FruchtermanReingold.java`
Author: Mathieu Jacomy.

### Additional Reading

- http://en.wikipedia.org/wiki/Force-based_algorithms