# N-Puzzle and N-Queens Solver

This project implements solutions for the N-Puzzle and N-Queens problems using Genetic Algorithms, as well as both informed and uninformed search algorithms.

## Problem Descriptions

### N-Puzzle Problem
The N-Puzzle is a classic sliding puzzle where a board of size N x N is divided into cells containing numbers from 1 to N^2 - 1, with one cell left empty. The objective is to rearrange the cells to form a goal configuration.

### N-Queens Problem
The N-Queens problem involves placing N chess queens on an N x N chessboard in such a way that no two queens threaten each other. That is, no two queens can share the same row, column, or diagonal.

## Algorithms

### Informed Search Algorithms
1. **A Star Algorithm:**

   A* is a popular informed search algorithm that combines the advantages of both Dijkstra's algorithm and greedy best-first search.
   It uses a heuristic function to estimate the cost from a state to the goal, allowing it to efficiently find optimal paths.

3. **Iterative Deepening Search (IDS) Graph:**

   Iterative Deepening Search is an uninformed search algorithm that combines depth-first search with breadth-first search.
   It performs depth-limited searches repeatedly, increasing the depth limit in each iteration until the goal is found.

### Uninformed Search Algorithm
1. **Best-First Tree Search:**

   Best-First Tree Search is an uninformed search algorithm that expands the most promising node based on a heuristic evaluation function.
   It explores the most promising paths first while avoiding the full exploration of all paths.

### Genetic Algorithms (GA)
1. **Genetic Algorithm for N-Puzzle and N-Queens:**

   Genetic Algorithms are optimization techniques inspired by the process of natural selection.
   In this project, we use Genetic Algorithms to evolve solutions for the N-Queens problem, aiming to find optimal or near-optimal solutions through generations of genetic variation and selection.

## Features
- Solving N-Puzzle problem using informed search algorithm (A*).
- Solving N-Puzzle problem using uninformed search algorithm (Iterative Deepening Search Graph).
- Solving N-Queens problem using Genetic Algorithms.
- Solving N-Queens problem using uninformed search algorithm (Best-First, Tree Search).

## Requirements

- Python 3 (or higher)
- [timeout-decorator](https://pypi.org/project/timeout-decorator/)
- [Pyevolve](https://github.com/perone/Pyevolve)


## Installation

1. Clone the repository:
   ```
   git clone https://github.com/matiasbrizzio/N-AI.git && cd N-AI
   ```
2. Install dependencies.
    
## License

This project is licensed under the MIT License.
