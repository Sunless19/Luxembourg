# Dijkstra's Algorithm for Finding Shortest Path in a Graph

## This application is designed to find the shortest path between two nodes in a graph using Dijkstra's algorithm. It utilizes a map of Luxembourg as the graph for demonstration purposes.

## Features:

## 1. Reading Map from Text File and Transforming into Graph:

- The application reads the map from a text file and transforms it into a graph representation.
## 2. Map Visualization:

- The map is visualized in a window, adjusting its size according to its dimensions.
- Only the edges (roads) of the map are graphically represented, not the nodes.
## 3. Selecting Nodes:

- Users can select two nodes by clicking on the window.
- The nearest node to the clicked location is identified and highlighted with a different color.
## 4. Finding Shortest Path:

- Dijkstra's algorithm is efficiently implemented using a priority queue to find the shortest path between the selected nodes.
## 5. Visualizing Shortest Path:

- The shortest path between the selected nodes is displayed on the map with a different color.
##How to Use:

+ Ensure that the map data is correctly formatted in the text file.
+ Run the application and click on the window to select two nodes.
### The shortest path between the selected nodes will be highlighted on the map.
### Note: This application is implemented using the Qt framework and is intended as a demonstration of Dijkstra's algorithm for finding shortest paths in a graph. To add new nodes press right click in the framework after compiling.
