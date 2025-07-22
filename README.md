# VectorFlow
# Dijkstra's Algorithm Simulation with OpenGL

A C++ and OpenGL application that provides a real-time, interactive visualization of Dijkstra's shortest path algorithm.
## Key Features

* **Step-by-Step Algorithm Visualization**: Watch Dijkstra's algorithm execute in real-time as it explores the graph to find the shortest paths from a source node.
* **Color-Coded Simulation**: The visualization uses distinct colors to provide clarity:
    * **Blue Nodes**: Represent explored or visited nodes.
    * **Violet Edges**: Indicate an edge that successfully led to a "relaxation" step (a shorter path was found).
    * **Gray Edges**: Edges that were considered but did not result in a shorter path.
* **Interactive Path Query**: Once the initial simulation is complete, you can query for the shortest path from the source to any destination node.
* **Animated Path Traversal**: A green "mover" node animates the journey along the calculated shortest path from the source to your chosen destination.

## How to Use

1.  **Launch the application** and follow the prompts in the console.
2.  **Define your graph**: Enter the total number of nodes, edges, and the ID of the source node.
3.  **Specify the edges**: For each edge, enter its start node, end node, and cost.
4.  **Observe the simulation**: The application will automatically begin visualizing the Dijkstra algorithm.
5.  **Query for a path**: Once the simulation finishes, press `Enter` to activate query mode. Enter a destination node in the console to see the shortest path animated.

## Planned Features

The following features are planned for future releases to enhance interactivity:

* **Interactive Graph Editor**:
    * Add new nodes to the graph with a simple mouse click.
    * Create new edges by clicking on two existing nodes.
* **Flexible Path Queries**:
    * Initiate a shortest path query from any node to any other node.
    * Visually select the source and destination nodes using the mouse.

## Technologies Used

* **C++**
* **OpenGL**
* **GLUT (The OpenGL Utility Toolkit)**
