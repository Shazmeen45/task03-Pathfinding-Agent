# Task 3: Heuristic Graph Pathfinding Agent Search Engine

## Project Overview
This project implements grid-based pathfinding using A* Search and Dijkstra’s Algorithm in Python.

The algorithms navigate through maze environments while avoiding obstacles and finding paths from a start position to a goal.

## Technologies Used
- Python
- Google Colab
- NumPy
- Matplotlib
- Pandas
- Heapq

## Algorithms
- A* Search with Manhattan Distance heuristic
- Dijkstra’s Algorithm

## Evaluation Metrics
- Path steps
- Runtime
- Expanded nodes
- Expanded node density

## Results
The algorithms were tested on three maze configurations. Both algorithms found paths with 12 steps in the tested mazes. A* explored fewer nodes than Dijkstra’s Algorithm across all three mazes.

## Project Files
- `Task3_Pathfinding_Agent.ipynb` — Python implementation
- `Task3_Pathfinding_Report.pdf` — Project report
- `pathfinding_results.csv` — Algorithm comparison results
- `astar_search_log.csv` — Search log
- `astar_visualization.png` — Pathfinding visualization

## How to Run
Open the notebook in Google Colab or Jupyter Notebook and execute the cells sequentially.
