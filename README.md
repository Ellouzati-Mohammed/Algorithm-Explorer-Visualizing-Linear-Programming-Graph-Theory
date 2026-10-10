# Algorithm Explorer
### Visualizing Linear Programming & Graph Theory

**Algorithm Explorer** is a desktop application developed in Python to make complex algorithms in **Linear Programming and Graph Theory** easier to understand through interactive, step-by-step visualizations.

The application provides an educational environment where users can explore algorithmic processes, observe how solutions evolve, and better understand the logic behind optimization and graph-based problems.

## Screenshots

### Home Page

![Algorithm Explorer - Home Page](doc/images/1.png)

### Algorithm Visualizations

| Visualization 1 | Visualization 2 |
|---|---|
| ![Algorithm Visualization 1](doc/images/2.png) | ![Algorithm Visualization 2](doc/images/3.png) |

| Visualization 3 | Visualization 4 |
|---|---|
| ![Algorithm Visualization 3](doc/images/4.png) | ![Algorithm Visualization 4](doc/images/5.png) |

## Features

- **Desktop graphical interface** for exploring algorithms.
- **Step-by-step visualization** to understand algorithm execution.
- **Linear Programming algorithms** for transportation and optimization problems.
- **Graph Theory algorithms** for graph traversal, shortest paths, spanning trees, and network flow.
- **Educational approach** that connects theoretical concepts with practical execution.

## Algorithms Covered

### Linear Programming & Transportation Problems

| Algorithm | Purpose |
|---|---|
| Simplex Method | Finds an optimal solution to a linear programming problem. |
| North-West Corner Method | Produces an initial feasible solution to a transportation problem. |
| Least Cost Method | Builds a transportation solution by prioritizing lower-cost cells. |
| Vogel's Approximation Method (VAM) | Estimates an initial transportation solution using penalty values. |

### Graph Theory

| Algorithm | Purpose |
|---|---|
| Welsh–Powell | Colors graph vertices using a degree-based ordering strategy. |
| Kruskal's Algorithm | Finds a minimum spanning tree in a weighted graph. |
| Dijkstra's Algorithm | Computes shortest paths from a source in a graph with non-negative edge weights. |
| Bellman–Ford Algorithm | Computes shortest paths and detects reachable negative-weight cycles. |
| Ford–Fulkerson Algorithm | Computes maximum flow in a flow network. |

## Technologies

- **Python** — application logic and algorithm implementation.
- **Tkinter** — desktop graphical user interface.
- **Matplotlib** — graphical visualization.
- **NetworkX** — graph representation and graph-related operations.

## Getting Started

### Prerequisites

- Python 3.10 or a compatible Python version.
- Tkinter, which is included with many standard Python installations.
- The Python libraries required by the project.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Ellouzati-Mohammed/Algorithm-Explorer-Visualizing-Linear-Programming-Graph-Theory.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Algorithm-Explorer-Visualizing-Linear-Programming-Graph-Theory
   ```

3. Create and activate a virtual environment (recommended):

   **Windows**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

   **Linux / macOS**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

4. Install the required libraries:

   ```bash
   pip install matplotlib networkx
   ```

   Install any additional dependencies required by the project if applicable.

### Run the Application

From the project root, execute:

```bash
python main.py
```

Run the application from the project root so that Python can correctly resolve the `gui` package and its modules.

## Project Structure

```text
Algorithm-Explorer-Visualizing-Linear-Programming-Graph-Theory/
│
├── Visualisation/   # Visualization-related modules
├── algorithms/      # Algorithm implementations
├── assets/          # Project assets
├── data/            # Data and input files
├── doc/             # Screenshots and project documentation
│   ├── 1.png        # Home page
│   ├── 2.png        # Algorithm visualization 1
│   ├── 3.png        # Algorithm visualization 2
│   ├── 4.png        # Algorithm visualization 3
│   └── 5.png        # Algorithm visualization 4
├── gui/
│   └── pages/       # Graphical interface pages
├── test/            # Tests
├── controller.py    # Application controller
└── main.py          # Application entry point
```

## Learning Objectives

This project explores the practical application of algorithmic concepts, including:

- Understanding linear programming and optimization techniques.
- Comparing methods for solving transportation problems.
- Exploring graph coloring, shortest paths, and minimum spanning trees.
- Understanding maximum-flow algorithms.
- Connecting mathematical theory with visual and computational results.



Software Engineering and Artificial Intelligence student.

- GitHub: [Ellouzati-Mohammed](https://github.com/Ellouzati-Mohammed)
- LinkedIn: [mohammed-ellouzati](https://linkedin.com/in/mohammed-ellouzati)

---

*Developed as an educational project to explore and visualize fundamental algorithms in optimization and graph theory.*
