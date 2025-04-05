# prims-algorithm
Implementation of Prim's Algorithm for finding Minimum Spanning Trees.

## What Is
A minimum spanning tree (MST) of a weighted graph, is a spanning tree T of G with a weight that is no larger than any other  
spanning tree of G.
A weighted graph is a graph G=(V,E) along with a function w: E → ℝ where the function w assigns a real number to every edge.

## Pseudocode
G is an undirected, connected, weighted graph  
T is a minimum spanning tree for G  
inside/outside means the point is in the set or outside the set  

T = ∅  
Pick any vertex in G and add it to T  
For j = 1 to n - 1
* Let C be the set of edges with one endpoint inside T and one endpoint outside T
* Let e be a minimum weight edge in C
* Add e to T
* Add the endpoint of e not already in T to T
