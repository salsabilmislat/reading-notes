# What we will learn

- Graphs

The source of this summary [The first link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

_______________________________________

## What is a Graphs

**a graph is an abstract data type that is meant to implement the undirected graph and directed graph concepts from the field of graph theory within mathematics.**

### common terminology used when working with Graphs

1. Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.

2. Edge - An edge is a connection between two nodes.

3. Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.

4. Degree - The degree of a vertex is the number of edges connected to that vertex.

### Directed vs Undirected

### Undirected Graphs

**is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.**

![code1](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

The undirected graph we are looking at has 6 vertices and 7 undirected edges.

Vertices/Nodes = {a,b,c,d,e,f}

Edges = {(a,c),(a,d),(b,c),(b,f),(c,e),(d,e),(e,f)}


### Directed Graph

**a set of objects (called vertices or nodes) that are connected together, where all the edges are directed from one vertex to another. A directed graph is sometimes called a digraph or a directed network.**

![code2](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DirectedGraph.PNG)

The directed graph above has six vertices and eight directed edges

Vertices = {a,b,c,d,e,f}

Edges = {(a,c),(b,c),(b,f),(c,e),(d,a),(d,e)(e,c)(e,f)}


### Complete vs Connected vs Disconnected

*There are many different types of graphs. This depends on how connected the graphs are to other node/vertices.*

#### The three different types are completed, connected, and disconnected.

### Complete Graphs

*A complete graph is when all nodes are connected to all other nodes.*

### Complete Graph

*Take a close look at each of the vertices in the graph above. Do you notice that each vertex is actually connected to every other node on the graph? That is what makes it a complete graph.*

![code](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/CompleteGraph.PNG)

### Connected

*A connected graph is graph that has all of vertices/nodes have at least one edge.*

![code](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/ConnectedGraph.PNG)

### ConnectedGraph

*In the visual above, this looks a lot more than what you are used to seeing. If you look closely at the different vertices of the graph, you will see that each node is connected to at least one other node or vertices. A Tree is a form of a connected graph. We will talk more about that in a bit.*

### Disconnected

*A disconnected graph is a graph where some vertices may not have edges.*

*In the above visual, the disconnected graph shows that some nodes may not always be connected to other nodes or vertices of the graph. It is complelty possible to have standalone nodes or edges (also known as islands) in a graph data structure.*

![code](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DisconnectedGraph.PNG)




