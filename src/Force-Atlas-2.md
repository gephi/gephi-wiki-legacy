Gephi is a network visualization software used in various disciplines (social network analysis, biology, genomics…). One of its key features is the ability to display the spatialization process, aiming at transforming the network into a map, and ForceAtlas2 is its default layout algorithm. The latter is developed by the Gephi team as an all-around solution to Gephi users’ typical networks (scale-free, 10 to 10,000 nodes).

ForceAtlas2 is a force-directed layout close to other algorithms used for network spatialization. We do not claim a theoretical advance but an attempt to integrate different techniques such as the Barnes Hut simulation, degree-dependent repulsive force, and local and global adaptive temperatures. It is designed for the Gephi user experience (it is a continuous algorithm), and we explain which constraints it implies. The algorithm benefits from much feedback and is developed in order to provide many possibilities through its settings.

### Référence
- [ForceAtlas2, a Continuous Graph Layout Algorithm for Handy Network Visualization Designed for the Gephi Software](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0098679), Mathieu Jacomy , Tommaso Venturini, Sebastien Heymann, Mathieu Bastian, Published: June 10, 2014DOI: 10.1371/journal.pone.0098679

### Source code

`org.gephi.layout.plugin.forceAtlas.ForceAtlasLayout.java`

Author: Mathieu Jacomy.