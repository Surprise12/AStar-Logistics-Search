### Project Overview

This project implements the A* search algorithm to solve a route optimization problem for a logistics company. The goal is to find the shortest path for a delivery truck traveling from Disaneng to Coligny in the Mahikeng local municipality.

The program takes into account:
- Actual distances between locations (in kilometers)
- Traffic heuristic values provided in the assignment brief

### How the Algorithm Works

The A* search algorithm combines:
1. **g(n)** - The actual cost from start to current node (distance traveled)
2. **h(n)** - The heuristic estimate from current node to goal (traffic values)
3. **f(n) = g(n) + h(n)** - Total estimated cost

The algorithm explores nodes with the lowest f(n) first, ensuring an optimal path is found.

### Results

After running the program, the following results were obtained:

| Metric | Value |
|--------|-------|
| Start Location | Disaneng |
| Goal Location | Coligny |
| Optimal Path | Disaneng → Mahikeng → Bakerville → Lichtenburg → Coligny |
| Total Distance | 110 km |
| Nodes Explored | 8 |
