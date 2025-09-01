An iterative algorithm that measures the importance of each node within the network. The metric assigns each node a probability that is the probability of being at that page after many clicks. The page rank values are the values in the eigenvector that has the highest corresponding eigenvalue of a normalized adjacency matrix A'. The standard adjacency matrix is normalized so that the columns of the matrix sum to 1.

### Reference

Page, Lawrence; Brin, Sergey; Motwani, Rajeev and Winograd, Terry (1999). The PageRank citation ranking: Bringing order to the Web. [PDF](http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf)

### Source code

See org.gephi.statistics.plugin.PageRank.java.

### Acknowledgements

This code was implemented by Patrick McSweeney.

### Additional Reading

- Sergey Brin, Lawrence Page, The Anatomy of a Large-Scale Hypertextual Web Search Engine, in Proceedings of the seventh International Conference on the World Wide Web (WWW1998):107-117
- http://en.wikipedia.org/wiki/PageRank