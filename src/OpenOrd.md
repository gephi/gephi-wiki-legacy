It is one of the few force-directed layout algorithms that can scale to over 1 million nodes, making it ideal for large graphs. However, small graphs (hundreds or less) do not always end up looking so good. This algorithm expects undirected weighted graphs and aims to better distinguish clusters. It can be run in parallel to speed up computing.

The algorithm is originally based on Fruchterman-Reingold and works with a fixed number of iterations. The algorithm is using simulated annealing and has five different phases: liquid, expansion, cool-down, crunch, and simmer. Each stage is a fraction of the total iterations and several parameters like temperature, attraction and damping are changing. The default schedule spends approximately 25% of its time in the liquid stage, 25% in the expansion stage, 25% in the cool-down stage, 10% in the crunch stage, and 15% in the simmer stage.

The original OpenOrd C++ implementation is available at the following address : http://www.cs.sandia.gov/~smartin/software.html. This plug-in version doesn't include the multi-level version of the algorithm. The algorithm was formerly known as DrL, and before that VxOrd.

OpenOrd can be run in parallel to speed up computation. Each thread will work on a subset of the nodes of the graph. It's recommended to put the number of core minus 1 to keep a thread for display. For example on a quad-core computer, it's good to use three threads.

Edge-cutting in OpenOrd is specified using a fraction from 0 to 1. An edge-cutting value of 0 corresponds to the standard Fruchterman-Reingold layout algorithm (no cutting), while an edge-cutting value of 1 corresponds to aggressive cutting. Aggressive cutting promotes clustering but will not cut every edge. The default value for edge-cutting in OpenOrd is 0.8.

### Reference

S. Martin, W. M. Brown, R. Klavans, and K. Boyack (to appear, 2011), "OpenOrd: An Open-Source Toolbox for Large Graph Layout," SPIE Conference on Visualization and Data Analysis (VDA).

### Source code

Available on the Marketplace: https://gephi.org/plugins/#/plugin/openord-layout
https://github.com/gephi/gephi-plugins/tree/openord-layout
Author: Mathieu Bastian.
