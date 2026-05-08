# Maze Generator and Solver

This project generates and solves a maze using **Depth-First Search (DFS)** and **stack-based backtracking**. It visualizes how algorithms navigate grid structures to create perfect mazes (mazes with no loops and a path to every cell).

## 🚀 Features
* **Random Maze Generation**: Uses a recursive backtracker to create unique layouts.
* **DFS Traversal**: Efficiently explores the grid to find a path.
* **Stack-based Backtracking**: Keeps track of the path and retreats when it hits a dead end.
* **Maze Solving Algorithm**: Automatically finds the shortest route from start to finish.

## 🛠 Language
* **Python **

## 💻 How to Run

\`\`\`
python maze.py
\`\`\`

## 🧠 How it Works
The generator starts at a random cell and marks it as visited. It then moves to a random unvisited neighbor, pushing the current cell to a stack. If it hits a dead end, it pops from the stack to backtrack until it finds a cell with unvisited neighbors.
