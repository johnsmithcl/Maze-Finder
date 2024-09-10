# Maze Pathfinding with Curses

This is a Python program that uses the curses module to visualize a pathfinding algorithm in a 2D maze. The algorithm explores the maze and finds the shortest path from the starting point (O) to the end point (X). The path is visualized in real-time using terminal-based graphics.

# Features

Maze Visualization: The maze is printed in the terminal using the curses library.
Breadth-First Search (BFS): The algorithm utilizes a BFS approach to find the shortest path through the maze.
Real-Time Updates: As the algorithm explores the maze, the visualization is updated in real-time, showing the path as it is discovered.
Colorful Display: The path is highlighted in red (X), while the rest of the maze is displayed in blue.

# Prerequisites
Python 3.x
curses module (typically comes with Python, no need for separate installation)
How It Works
The maze is represented as a 2D list where:

# # represents a wall.
" " represents an open path.
O is the start position.
X is the end position.
The program uses Breadth-First Search (BFS) to explore the maze and find the shortest path from the start to the end. The path is displayed as the algorithm progresses.
