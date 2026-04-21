# MIDTERM LAB 2 - Node Map and Shortest Path

## 👤 Author
Samuel Angelo M. Arnaiz

---

## 📌 Project Description
This program visualizes a network of nodes and determines the shortest path between two selected nodes. Each connection between nodes includes three attributes:
- Distance (km)
- Time (minutes)
- Fuel (liters)

The system allows the user to choose which metric to optimize.

---

## ⚙️ Features
- Graph visualization using NetworkX and Matplotlib
- Supports shortest path based on:
  - Distance
  - Time
  - Fuel consumption
- Uses Dijkstra’s Algorithm for pathfinding
- Displays:
  - Path taken
  - Total distance
  - Total time
  - Total fuel

---

## 🧠 Algorithm Used
### Dijkstra’s Algorithm
Dijkstra’s Algorithm is used to find the shortest path between nodes in a graph. It works by:
1. Starting at the selected node
2. Exploring neighboring nodes
3. Updating the shortest known distance
4. Repeating until the destination is reached

This algorithm guarantees the optimal path for weighted graphs.

---

## 🛠️ Tools & Libraries
- Python
- NetworkX (for graph structure)
- Matplotlib (for visualization)

---

## ▶️ How to Run the Program

1. Install required libraries: