# Graphs

## What is `Graph`?
A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph. More formally a Graph can be defined as, A Graph consisting of a finite set of vertices(or nodes) and a set of edges that connect a pair of nodes.

## Types of Graphs:  
### These some of Graphs types:
1. **Finite Graphs:** 
A graph is said to be finite if it has a finite number of vertices and a finite number of edges.  


2. **Infinite Graph:** A graph is said to be infinite if it has an infinite number of vertices as well as an infinite number of edges. 

3. **Trivial Graph:** A graph is said to be trivial if a finite graph contains only one vertex and no edge. 

4. **Simple Graph:** A simple graph is a graph that does not contain more than one edge between the pair of vertices. A simple railway track connecting different cities is an example of a simple graph. 

5. **Multi Graph:** 
Any graph which contains some parallel edges but doesn’t contain any self-loop is called a multigraph. For example a Road Map. 

    - Parallel Edges: If two vertices are connected with more than one edge then such edges are called parallel edges that are many routes but one destination.  

   - Loop: An edge of a graph that starts from a vertex and ends at the same vertex is called a loop or a self-loop.


6. **Null Graph:** A graph of order n and size zero is a graph where there are only isolated vertices with no edges connecting any pair of vertices.

7. **Complete Graph:** A simple graph with n vertices is called a complete graph if the degree of each vertex is n-1, that is, one vertex is attached with n-1 edges or the rest of the vertices in the graph. A complete graph is also called Full Graph. 


8. **Pseudo Graph:** A graph G with a self-loop and some multiple edges is called a pseudo graph.   



## What is the Difference between graph and tree?

The basis of Comparison |	Graph	|Tree
--------| --------|----------
Definition|	Graph is a non-linear data structure.| 	Tree is a non-linear data structure.
Structure|	It is a collection of vertices/nodes and edges.|	It is a collection of nodes and edges.
Edges|	Each node can have any number of edges.|	If there is n nodes then there would be n-1 number of edges
Types of Edges|	They can be directed or undirected|	They are always directed
Root node	|There is no unique node called root in graph.|	There is a unique node called root(parent) node in trees.
Loop Formation|	A cycle can be formed.|	There will not be any cycle.
Traversal	|For graph traversal, we use Breadth-First Search (BFS), and Depth-First Search (DFS).|	We traverse a tree using in-order, pre-order, or post-order traversal methods.
Applications|	For finding shortest path in networking graph is used.	|For game trees, decision trees, the tree is used.

