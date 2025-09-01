It is possible to convert a citation graph to a co-citation graph in Gephi.
It can be done as follows

1) Add a type column in edge file and fill all edges with "Undirected"
2) Import node and edge files in to Gephi
3) Add a Type column to nodes to Bloean
4) Make cited article type 1 and citing articles 0
5) Use multimode network projection
6) In multimod projection window
click load attributes
left matrix--->0-1
right matrix-->1-0
remove edges
remove nodes
directed
The problem was related to multimodal netwrok projection add in. It do not work with directed graphs.

https://www.researchgate.net/post/What_is_the_best_equavelent_for_Co-Citation_and_Bibliographic_Coupling_in_Gephi?isAnswerFieldFocused=true