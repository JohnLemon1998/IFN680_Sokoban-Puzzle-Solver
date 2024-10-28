# Automated Sokoban Solver

An automated Sokoban puzzle solver built in Python, designed to find solutions for complex Sokoban levels using advanced search algorithms. This project leverages algorithms such as Breadth-First Search (BFS), Depth-First Search (DFS), Greedy Search, and A* Search to efficiently navigate through puzzle layouts and find the optimal path to victory.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Algorithms](#algorithms)
- [Setup and Usage](#setup-and-usage)
- [Project Structure](#project-structure)
- [License](#license)

## Overview

Sokoban is a classic puzzle game where the player pushes boxes onto target locations within a warehouse-like grid. This solver automates that task, analyzing the layout and computing the optimal moves to achieve the goal with the fewest moves possible.

## Features

- Implements multiple pathfinding algorithms
- Optimized to avoid redundant moves
- Provides visual representation of the solution

## Algorithms

This project implements the following search algorithms:

1. **Depth-First Search (DFS)**: Explores as deep as possible along each path before backtracking, potentially finding a solution quickly, though not necessarily the optimal one.
2. **Breadth-First Search (BFS)**: Explores all possible moves level-by-level, guaranteeing the shortest solution path but with potentially high memory usage.
3. **Greedy Search**: Focuses on moves that appear closer to the goal, finding solutions faster but without a guarantee of optimality.
4. **A* Search**: Uses heuristics to combine the benefits of BFS and Greedy Search, efficiently finding the shortest path with optimal results when paired with an admissible heuristic.

## Setup and Usage

This project is implemented in a Jupyter Notebook (`.ipynb`), so you’ll need Jupyter installed along with any necessary libraries. There is no `requirements.txt` file; however, the following packages may be required depending on the algorithms and visualizations used:
- `numpy`
- `matplotlib`

### Running the Solver

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/automated-sokoban-solver.git
   cd automated-sokoban-solver
