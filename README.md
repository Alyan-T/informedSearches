# Dynamic Pathfinding Agent 

## Overview
This project is a grid-based Dynamic Pathfinding Agent developed in Python using Pygame. It visualizes and compares the performance of **A* Search** and **Greedy Best-First Search (GBFS)** algorithms. The environment supports real-time map editing, dynamic obstacle generation, and real-time path re-planning if the agent's route gets blocked while in transit.

## Features
Interactive Grid: Draw and erase walls, or randomly generate a maze.
Algorithm Toggling: Switch between A* and GBFS on the fly.
Heuristic Toggling: Compare Manhattan and Euclidean distance heuristics.
Dynamic Mode: Obstacles can randomly spawn while the agent moves. If the path is blocked, the agent immediately recalculates a new route from its current position.
Real-Time Dashboard: Tracks the algorithm, heuristic, nodes visited, path cost, and execution time (ms).

## Installation & Dependencies
To run this project, you need Python 3.x installed on your system. 

1. Clone this repository to your local machine.
2. Install the required Pygame library by running the following command in your terminal:
   pip install pygame
## How to Run
Open your terminal or command prompt, navigate to the project directory, and execute:

python main.py

Controls & Interactivity
Mouse Controls
Left Click: Place the Start node (Red), then the Goal node (Turquoise). Subsequent clicks will draw walls (Black).

Right Click: Erase nodes (resets to White).

Keyboard Controls
Spacebar: Start the search and initiate the agent's movement.

A: Select A* Search Algorithm.

G: Select Greedy Best-First Search (GBFS) Algorithm.

M: Select Manhattan Distance Heuristic.

E: Select Euclidean Distance Heuristic.

D: Toggle Dynamic Mode (ON/OFF).

R: Generate a random map (30% obstacle density). Note: Start and Goal must be placed first.

C: Clear the entire grid and reset all metrics.

UP Arrow: Increase grid density (adds more rows/columns).

DOWN Arrow: Decrease grid density.
