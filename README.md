
# Dijkstra's Shortest Path Algorithm

This Python package implements Dijkstra's shortest path algorithm using a min-heap priority queue. It allows users to find the shortest path from a source node to all other nodes in a weighted, directed graph.

---

## Installation

   Install the package locally using pip:

   ```bash
   pip install .
   ```

---

### Output Explanation:

1. **Shortest distances**: The output will display the shortest distances from the source node (`0` by default) to all other nodes in the graph.

2. **Paths**: The output will also show the path taken to reach each node from the source node.

---

## Input File Format

The input file should describe the graph in the following format:
- The first line should contain the number of vertices.
- Each subsequent line describes an edge in the graph with the format:
  ```
  <start_vertex> <end_vertex> <weight>
  ```

---
