# Advanced Optimization Problems with R

This repository contains implementations of various optimization algorithms in R, applied to benchmark problems. It is divided into two main scripts:

1. **Script.R** - Focuses on basic optimization problems and compares several algorithms for performance.
2. **Script_Advanced.R** - Implements advanced optimization techniques like Ant Colony Optimization (ACO) with grid search refinement.

---

## Table of Contents
- [Features](#features)
- [Dependencies](#dependencies)
- [Getting Started](#getting-started)
- [Optimization Algorithms](#optimization-algorithms)
- [Plots and Visualizations](#plots-and-visualizations)
- [Acknowledgments](#acknowledgments)

---

## Features

### **Script.R**
- Compares multiple algorithms:
  - Monte Carlo
  - Hill Climbing
  - Simulated Annealing (SANN)
  - Tabu Search
- Benchmark problem: Maximization of the `rubies` function with a penalty for constraint violations.
- Visualizations include:
  - Algorithm performance comparison
  - Convergence plots

### **Script_Advanced.R**
- **Ant Colony Optimization (ACO):** Implements ACO for a multidimensional problem with grid search refinement.
- **Recursive Grid Search:** Refines the ACO results for better precision.
- 3D visualization of the objective function with annotated optima.

---

## Dependencies

The scripts require the following R packages:
- `rminer`: For average computations.
- `plotly`: For 3D visualizations.
- `ggplot2`: For comparative analysis plots.
- `tabuSearch`: For implementing Tabu Search.
- `genalg`, `DEoptim`, `pso`: For population-based algorithms.

Install missing packages using:
```R
install.packages(c("rminer", "plotly", "ggplot2", "tabuSearch", "genalg", "DEoptim", "pso"))
```

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/DanteSc03/ruby-splitting-optimization.git
cd your-repo-name
```

### Run the Scripts
- Open the scripts in RStudio or your preferred R environment.
- Set the working directory to the folder containing the scripts:
  ```R
  setwd("<path-to-scripts>")
  ```
- Source the scripts and run them to see results.

---

## Optimization Algorithms

### Implemented Algorithms:
1. **Monte Carlo**
2. **Hill Climbing**
3. **Simulated Annealing**
4. **Tabu Search**
5. **Ant Colony Optimization (ACO)**
6. **Recursive Grid Search Refinement**
7. **Population-Based Methods:**
   - Evolutionary Algorithm (EA)
   - Differential Evolution (DE)
   - Particle Swarm Optimization (PSO)

### Benchmark Function: `rubies`
- A quadratic function with sinusoidal components and penalties for constraint violations.

---

## Plots and Visualizations
- **Convergence Plots:** Track algorithm performance over iterations.
- **3D Surface Plots:** Visualize the optimization landscape and optima.
- **Comparative Bar Charts:** Display best values achieved by each algorithm.


---

## Acknowledgments

This project is inspired by advanced optimization techniques and demonstrates practical applications in R. Special thanks to the contributors and the R community for their excellent libraries and support.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
