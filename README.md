# Search Algorithms in AI

This project implements various **search algorithms** commonly used in Artificial Intelligence (AI) for pathfinding and problem-solving. The algorithms applied include **Uniform Cost Search (UCS), A\*, Depth-First Search (DFS), and Breadth-First Search (BFS)**.

## Description

Search algorithms are fundamental in AI for solving problems that require finding an optimal or feasible path from a start state to a goal state. In this project, we explore different strategies:

- **Uniform Cost Search (UCS)**: Expands the least-cost node first, ensuring an optimal solution if the cost function is consistent.
- **A\***: Uses both cost (g) and a heuristic estimate (h) to find the most efficient path.
- **Depth-First Search (DFS)**: Explores as deep as possible before backtracking, often leading to non-optimal but quick solutions.
- **Breadth-First Search (BFS)**: Expands the shallowest nodes first, guaranteeing the shortest path in an unweighted graph.

Each algorithm is tested in a simple problem environment where the goal is to reach a target state efficiently.

## Technologies Used

- **Python**: Main programming language.
- **Priority Queue (heapq)**: Used for UCS and A\* implementations.
- **Graph Representations**: Nodes and edges for defining search spaces.
- **Heuristics**: Applied in A\* to estimate remaining cost.

