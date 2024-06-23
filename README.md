# A* Pathfinding Algorithm Visualization

This project implements the A* pathfinding algorithm and visualizes its process using the Pygame library. It's designed to demonstrate how the A* algorithm finds the shortest path between two points on a grid, considering obstacles and using a heuristic to guide its search.

## Features

- **A* Algorithm Implementation**: Core logic that drives the pathfinding process, efficiently finding the shortest path.
- **Real-Time Visualization**: Utilizes Pygame for graphical representation of the algorithm in action, including the exploration of nodes and the final path.
- **Heuristic Function**: Employs the Manhattan distance as a heuristic to estimate the cost from the current node to the end node, optimizing the search process.
- **Dynamic Path Reconstruction**: Once the end node is reached, the algorithm reconstructs the path taken and highlights it on the grid.

## Requirements

To run this project, you'll need:

- Python 3.x
- Pygame library

## Installation

1. **Clone the Repository**

  ```git clone https://github.com/RahmanImtiaz/A-Algorithm-Visualiser.git```

2. **Install Dependencies**

Navigate to the project directory and install the required Python packages:

```pip install pygame```

## Usage
To run the visualization, execute the A*pathFindingAlgoVis.py script from your terminal:

```python A*pathFindingAlgoVis.py```

## How It Works
- Initialization: The grid is initialized, and the start and end points are set.
- Algorithm Execution: The A* algorithm starts from the start node, exploring neighbors and considering their costs (g_score) and estimated distances to the end node (f_score), guided by the heuristic.
- Visualization: Each step of the algorithm is visualized in real-time, showing open and closed nodes, until the path is found.
- Path Reconstruction: Upon reaching the end node, the algorithm reconstructs the path from start to end, highlighting it on the grid.

## Contributing
Contributions to improve the project are welcome. Please follow the standard fork-branch-pull request workflow.

## License
Distributed under the MIT License.


