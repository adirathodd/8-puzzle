# 8-Puzzle Solver (A* Algorithm Implementation)

## Overview
This program solves the 8-puzzle problem using the A* search algorithm. The puzzle consists of a 4x4 grid with 15 numbered tiles and one blank tile. The objective is to slide the tiles to match the goal state configuration. The algorithm uses Manhattan distance as a heuristic to guide the search.

---

## Features
- **Initialization**: Loads the initial and goal states from the command line.
- **Heuristic Function**: Calculates the Manhattan distance for a given state.
- **A* Search Algorithm**: Explores possible moves (up, down, left, right) to find the optimal path to the solution.
- **Node Management**: Uses open and closed lists to avoid revisiting states.
- **Solution Path**: Traces and displays the sequence of moves leading to the solution.

---

## How to Run

### Prerequisites
- A C compiler (e.g., GCC)

### Compilation
Compile the program using the following command:
```bash
gcc -o puzzle puzzle.c
