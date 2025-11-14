# Vehicle Routing Problem with Time Windows (VRPTW) Solver Comparison - Python (strategies for solving NP-hard optimization problems using multi Meta-heuristic ​= ​Heuristic ​+ ​Randomization algorithms)

---

## The Comparison results of different NP metahuristic algorithms for VRPTW

Running Algorithms on dataset: rc108.txt

---

Best-Known Solution (BKS) Route Cost: 1114.2

BKS solution:

Route #1: 2 6 7 8 46 4 45 5 3 1 100

Route #2: 12 14 47 17 16 15 13 9 11 10

Route #3: 33 32 30 28 26 27 29 31 34 93

Route #4: 41 42 44 43 40 38 37 35 36 39

Route #5: 61 81 94 71 72 54 96

Route #6: 64 51 76 89 18 48 19 20 66

Route #7: 65 83 57 24 22 49 21 23 25 77

Route #8: 69 98 88 53 78 73 79 60 55 70 68

Route #9: 82 99 52 86 87 59 97 75 58 74

Route #10: 90

Route #11: 92 95 67 62 50 63 85 84 56 91 80

---

Hybrid Genetic Search (HGS) Route Cost: 1114.2

HGS solution:

Route #1: 12 14 47 17 16 15 13 9 11 10 

Route #2: 82 99 52 86 87 59 97 75 58 74 

Route #3: 65 83 57 24 22 49 21 23 25 77 

Route #4: 64 51 76 89 18 48 19 20 66 

Route #5: 92 95 67 62 50 63 85 84 56 91 80 

Route #6: 33 32 30 28 26 27 29 31 34 93 

Route #7: 61 81 94 71 72 54 96 

Route #8: 41 42 44 43 40 38 37 35 36 39 

Route #9: 2 6 7 8 46 4 45 5 3 1 100 

Route #10: 90 

Route #11: 69 98 88 53 78 73 79 60 55 70 68 

---

Guided Local Search (GLS) Route Cost: 1266.9

GLS solution:

Route #1: 71 72 44 43 40 38 37 35 36 39

Route #2: 98 82 90 53 78 73 79 2 60

Route #3: 92 67 32 30 28 26 27 29 31 34 93

Route #4: 65 99 24 22 20 49 21 23 25 77

Route #5: 95 51 76 89 33 50 62 91 80

Route #6: 12 14 47 17 16 15 13 9 11 10

Route #7: 88 6 7 8 46 4 45 5 3 1 100 55

Route #8: 69 70 61 81 94 96 54 41 42 68

Route #9: 83 52 57 86 87 59 97 75 58 74

Route #10: 64 19 48 18 63 85 84 56 66

---

Ant Colony Optimization (ACO) Route Cost: 1321.8459204561746

ACO solution:

Route #1: 69 98 88 82 99 52 86 74 57 83 66 91

Route #2: 65 64 51 76 89 85 63 62 56 80

Route #3: 90 53 73 79 78 60 55 68

Route #4: 33 28 30 32 34 31 29 27 26

Route #5: 72 71 93 94 81 61 54 96 100 70

Route #6: 2 45 5 8 7 6 46 4 3 1

Route #7: 41 42 44 38 39 40 36 35 37 43

Route #8: 19 21 23 18 48 49 22 20 24 25

Route #9: 12 14 47 17 16 15 11 10 9 13

Route #10: 59 58 87 97 75 77

Route #11: 92 95 84 50 67

---

Simulated Annealing (SA) Route Cost: 1237.620141359753

SA solution:

Route #1: 7 8 46 4 45 5 3 1 100 55

Route #2: 64 51 76 89 63 85 84 56 91

Route #3: 69 98 53 12 15 16 17 47 14

Route #4: 90 82 9 13 11 10

Route #5: 61 42 44 40 39 38 37 35 36 43

Route #6: 65 52 86 77 25 23 57

Route #7: 88 60 78 73 79 6 2 70 68

Route #8: 92 67 62 34 50 94 96

Route #9: 99 87 59 97 75 58 74

Route #10: 83 24 22 19 18 48 21 49 20 66

Route #11: 81 93 71 72 41 54

Route #12: 95 33 32 30 28 26 27 29 31 80

---

Algorithms - - No. of Routes - - Costs - - Gap(%) - - Runtime(seconds)

  BKS - - - - - - 11 - - - - - - - - - - 1114.2 - - -	-

  HGS - - - - - - 11 - - - - - - - - - - 1114.2 - - 0.0 - - - - 300.137736082077

  GLS - - - - - - 10 - - - - - - - - - - 1266.9 - - 13.7 - -- - 300.0492959022522

  ACO - - - - - - 11 - - - - - - - - - - 1321.8 - - 18.63 - - - 877.1980187892914

  SA - - -- - - - 12 - - - - - - - - - - 1237.6 - - 11.08 - - - 416.80780506134033

---

![3 HGS rc108](https://github.com/user-attachments/assets/afac9be9-37a1-4b4d-a7f8-5d346d653e2f) ![3 GLS rc108](https://github.com/user-attachments/assets/b8140b7f-30c2-4f65-9d55-24207754dd0f) ![3 ACO rc108](https://github.com/user-attachments/assets/3643d0e9-c3d4-418c-8ed7-efea8d94ede9) ![3 SA rc108](https://github.com/user-attachments/assets/3632158b-6131-4157-97bd-9cd4116bcecf)
---

## Project Summary

This repository provides a comprehensive comparison and implementation of several heuristic and metaheuristic algorithms for solving the **Vehicle Routing Problem with Time Windows (VRPTW)**. Developed as part of an advanced study project, it showcases reproducible computational experiments, detailed analysis, and visualizations of solution quality for different algorithms. The target audience includes researchers, students, and practitioners interested in operations research, optimization, and applied machine learning.

---

## Table of Contents

- [Project Summary](#project-summary)
- [Project Details](#project-details)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Algorithms Implemented](#algorithms-implemented)
- [How to Run](#how-to-run)
- [Visualizations](#visualizations)
- [Results & Comparison](#results--comparison)
- [Screenshots](#screenshots)
- [Keywords](#keywords)
- [Contact](#contact)

---

## Project Details

The Vehicle Routing Problem with Time Windows (VRPTW) is a classic combinatorial optimization problem that extends the basic Vehicle Routing Problem (VRP) by adding constraints on service time windows for each customer. The challenge is to determine optimal routes for a fleet of vehicles to service a set of customers within their specified time windows, minimizing total travel cost. This project benchmarks and compares several well-known metaheuristic algorithms on standard datasets (e.g., Solomon's instances) and visualizes their performance.

**Algorithms Compared:**
- Hybrid Genetic Search (HGS)
- Guided Local Search (GLS)
- Ant Colony Optimization (ACO)
- Simulated Annealing (SA)

---

## Features

- Modular implementation for each algorithm
- Benchmarking against Best-Known Solutions (BKS)
- Visual comparison of routes and costs
- Reproducible experiments via fixed seeds (with options to randomize)
- Interactive Jupyter notebook for experiment walkthroughs
- Easily extensible for new algorithms or datasets

---

## Technologies Used

- **Python 3.x**: Core programming language
- **NumPy, pandas**: Data manipulation and analysis
- **matplotlib**: Visualization of routes and performance
- **OR-Tools**: Used in GLS for routing optimization
- **pyVRP**: Framework for HGS implementation
- **Jupyter Notebook**: Interactive analysis and visualization

---

## Project Structure

```
.
├── main.py                   # Main script to run all algorithms and generate results
├── solver.ipynb              # Jupyter Notebook for interactive exploration
├── aco/                      # Implementation of Ant Colony Optimization
│   ├── vrptw_base.py         # Node and graph structures for ACO
│   ├── basic_aco.py          # Core ACO logic and route extraction
│   ├── ant.py                # Ant agent behaviors and movement
├── gls/                      # Implementation of Guided Local Search
│   ├── base_solver.py        # GLS algorithm and solver logic
│   ├── instance_loader.py    # Data loader for GLS
├── sa/                       # Simulated Annealing code
├── hgs/                      # Hybrid Genetic Search code
├── bks.py                    # Processes Best-Known Solutions (BKS)
├── plot.py                   # Visualization utilities
├── data/                     # Benchmark datasets (Solomon .txt and .sol)
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
```

---

## Algorithms Implemented

### 1. Hybrid Genetic Search (HGS)
A metaheuristic that evolves a population of solutions using selection, crossover, and mutation. Implementation is based on the pyVRP library and supports customizable stopping criteria.

**Example Usage:**
```python
from pyvrp import Model, read
from pyvrp.stop import MaxRuntime

def solve_with_hgs(input_path, runtime):
    INSTANCE = read(input_path, instance_format="solomon", round_func="trunc1")
    model = Model.from_data(INSTANCE)
    result = model.solve(stop=MaxRuntime(runtime), seed=0)  # Can randomize 'seed'
    return result
```

---

### 2. Guided Local Search (GLS)
Enhances local search by penalizing overused solution components, implemented using OR-Tools, and allows for time-limited optimization.

**Example Usage:**
```python
from gls.base_solver import Solver
from gls.instance_loader import load_instance

def solve_with_gls(input_path, runtime):
    data = load_instance(input_path)
    solver = Solver(data)
    solver.create_model()
    solver.solve_model({"time_limit": runtime})
    return solver.get_solution()
```

---

### 3. Ant Colony Optimization (ACO)
A population-based metaheuristic that simulates ant foraging behavior using pheromone trails to discover optimal routes.

**Key Classes:**
- `Node` (in `aco/vrptw_base.py`): Represents each location (customer or depot), including time windows and demand.
- `Ant` (in `aco/ant.py`): Each ant constructs a route, considering vehicle load, time windows, and updates its path.
- `BasicACO` (in `aco/basic_aco.py`): Core logic for iteratively building solutions and updating pheromones.

**Example Code Excerpt:**
```python
# Example: Extracting routes from the best path (aco/basic_aco.py)
def get_best_route(self):
    routes = []
    route = []
    for node in self.best_path:
        if node != 0:
            route.append(node)
        else:
            if route:
                routes.append(route)
                route = []
    return routes
```

---

### 4. Simulated Annealing (SA)
A probabilistic algorithm that explores the solution space by occasionally accepting worse solutions, allowing escape from local minima.

---

## How to Run

### 1. Environment Setup

```sh
python -m venv .venv
# Activate the virtual environment:
# Linux/Mac:
source .venv/bin/activate
# Windows:
.venv\Scripts\activate

pip install -r requirements.txt
```

---

### 2. Running the Algorithms

To run all algorithms and generate comparative results:

```sh
python main.py
```

---

### 3. Interactive Exploration

For a step-by-step interactive analysis:

```sh
jupyter notebook solver.ipynb
```

---

## Visualizations

- Visualizations of the generated routes and algorithm performance are created using `matplotlib`. You can customize these plots in `plot.py`.
- Results are saved and/or displayed as images for direct comparison.

---

## Results & Comparison

The following table summarizes the results of each algorithm on the `rc108.txt` dataset:

| Algorithm | Route Cost | No. of Routes | Gap (%) | Runtime (s) |
|-----------|------------|---------------|---------|-------------|
| BKS       | 1114.2     | 11            | 0       | -           |
| HGS       | 1114.2     | 11            | 0.0     | 300.14      |
| GLS       | 1266.9     | 10            | 13.7    | 300.05      |
| ACO       | 1321.8     | 11            | 18.63   | 877.20      |
| SA        | 1237.6     | 12            | 11.08   | 416.81      |

> See the detailed solution routes and costs for each algorithm in the section below.

---

## Screenshots

*All images are retained from the original README and illustrate the route solutions for each algorithm.*

*(See README for full image list)*

---

## Keywords

- Vehicle Routing Problem (VRP)
- Time Windows
- Metaheuristics
- Genetic Algorithm
- Ant Colony Optimization
- Simulated Annealing
- Guided Local Search
- Solomon Dataset
- Routing Optimization
- Visualization
- Benchmarking

---

## Conclusion

This project serves as a hands-on, extensible, and educational platform for benchmarking and understanding metaheuristic algorithms applied to the VRPTW. You are encouraged to explore, modify, and extend the codebase for learning, research, or practical use cases.

---

## Contact

For questions, feedback, or collaboration:

**Arnob Mahmud**  
Email: arnob_t78@yahoo.com

---

*Thank you for exploring this project!*
