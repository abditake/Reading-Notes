# Implementation: Linked Lists

## Trees:

- ### A `graph` a data structure that is non-linear and it a collection of vertices that can be connected by line segments called edges.

- # The following example below is a graph.


![Tree](https://media.geeksforgeeks.org/wp-content/cdn-uploads/binary-tree-to-DLL.png)


## Terminology 

  - Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
  
  - Edge - An edge is a connection between two nodes.
  
  - Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
  
  - Degree - The degree of a vertex is the number of edges connected to that vertex.



# Undirected Graph 
  - a undirected graph is a graph that does not move in any direction this is also called bi-directional because the nodes or vertices in the graph are bi-directional

# Example of Undirected Graph 
![bi-directional graph](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/UndirectedGraph.PNG)

# Directed Graph 
  - A directed graph is a graph where every edge is directed. This means that every edge flows to another in the graph. 
# Example of Directional Graph
  ![directional](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/DirectedGraph.PNG)


- ## Different types of Graphs
    


  - Complete Graphs
    - A complete graph is when all nodes are connected to all other nodes.

    ![complete](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/CompleteGraph.PNG)

  <hr>


  - Connected
    - A connected graph is a graph that has all of the vertices have a least one edge

    ![connected](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/ConnectedGraph.PNG) 

  - Disconnected
    - A disconnected graph is a graph where some vertices may not have edges.

    ![Disconnected](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/assets/ConnectedGraph.PNG) 


# Traversals

  - BreadthFirst 
    ```
    ALGORITHM BreadthFirst(vertex)
    DECLARE nodes <-- new List()
    DECLARE breadth <-- new Queue()
    DECLARE visited <-- new Set()

    breadth.Enqueue(vertex)
    visited.Add(vertex)

    while (breadth is not empty)
        DECLARE front <-- breadth.Dequeue()
        nodes.Add(front)

        for each child in front.Children
            if(child is not visited)
                visited.Add(child)
                breadth.Enqueue(child)

    return nodes;
    ```
    - ### breakDown
    - We have declared that our starting node (or root) is going to be Node A.
    - The first thing we want to do is Enqueue the root.
    - We also need to add the root to the visited set.
    - Next, we enter a while loop. We want this loop to keep running until there are no more nodes in our queue.
    - Once we are in the while loop, we want to Dequeue the front node and then check to see if it has any children.
    - if there are children of the node we are currently looking at, we want to add them to visited set. This will help us know that we have already seen that node before, and won’t accidently push us into an infinite loop if the graph was cyclic. In addition to tracking each child node as visited, we want to place any of its children that have not yet been visited into the queue.
    - The process will complete until the queue is empty.
    - nce the while loop breaks, we can then return the list of nodes. This list will contain, in order, all the nodes that were traversed.

  - DepthFirst
  - 










 