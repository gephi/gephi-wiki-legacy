Hyperlink-Induced Topic Search (HITS) (also known as Hubs and authorities) is a link analysis algorithm that rates Web pages, developed by Jon Kleinberg.

### Objective

The HITS metric determines two values for a page: its authority, which estimates the value of the content of the page, and its hub value, which estimates the value of its links to other pages.
Description

Actually computes two different scores: hubs and authority. The authority score indicates the value of the page (node) itself and hubs estimates the value of the links outgoing from the page (node). Hits is an iterative algorithm at each iteration:

1. Update the authority value of each node to be the sum of the hub values for every node it has a link into.
- Update the hub values for each node to be the sum of the authority values that it has a link into.
- Normalize the hub and authority scores for all nodes by normalizing each value by the system sum for each value.
- Repeat these steps (assumingly until the values no longer fluctuate).

### Source code

See org.gephi.statistics.plugin.Hits.java.

### Acknowledgments

This code was implemented by Patrick McSweeney.

### Implemented Algorithm

Kleinberg, Jon (1999). "Authoritative sources in a hyperlinked environment". Journal of the ACM 46 (5): 604–632. doi:10.1145/324133.324140. [PDF](http://www.cs.cornell.edu/home/kleinber/auth.pdf)

### Reference

- http://www.math.cornell.edu/~mec/Winter2009/RalucaRemus/Lecture4/lecture4.html
- http://en.wikipedia.org/wiki/HITS_algorithm