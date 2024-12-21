# Advanced Optimization Problems with R

This repository contains a comprehensive collection of optimization algorithms implemented in R, designed to solve both basic and advanced optimization problems. The focus is on practical applications and performance comparison across various methods. The repository is divided into two key scripts:

1. **Script.R** - This script tackles basic optimization challenges by comparing several widely used algorithms. It provides insights into their efficiency and effectiveness in finding optimal solutions for constrained and unconstrained problems. 🛠️

2. **Script_Advanced.R** - This script delves into advanced optimization techniques, showcasing the implementation of Ant Colony Optimization (ACO) combined with grid search refinement. It explores optimization in multidimensional spaces with a detailed 3D visualization of objective functions and their optima. 🐜

---

## Table of Contents
- [Features](#features) ✨
- [Dependencies](#dependencies) 📦
- [Getting Started](#getting-started) 🚀
- [Optimization Algorithms](#optimization-algorithms) 📊
- [Plots and Visualizations](#plots-and-visualizations) 🖼️
- [Acknowledgments](#acknowledgments) 🙏

---

## Features

### **Script.R**
- Compares multiple algorithms:
  - Monte Carlo 🎲
  - Hill Climbing 🧗
  - Simulated Annealing (SANN) ❄️
  - Tabu Search 🚫
- Benchmark problem: Maximization of the `rubies` function with a penalty for constraint violations. 💎
- Visualizations include:
  - Algorithm performance comparison 📈
  - Convergence plots 🔄

### **Script_Advanced.R**
- **Ant Colony Optimization (ACO):** Implements ACO for a multidimensional problem with grid search refinement. 🐜
- **Recursive Grid Search:** Refines the ACO results for better precision. 🔍
- 3D visualization of the objective function with annotated optima. 🖥️

---

## Dependencies

The scripts require the following R packages:
- `rminer`: For average computations. 🧮
- `plotly`: For 3D visualizations. 📊
- `ggplot2`: For comparative analysis plots. 🖼️
- `tabuSearch`: For implementing Tabu Search. 🚫
- `genalg`, `DEoptim`, `pso`: For population-based algorithms. 🧬

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
- Source the scripts and run them to see results. 🎉

---

## Optimization Algorithms

### Implemented Algorithms:
1. **Monte Carlo** 🎲
2. **Hill Climbing** 🧗
3. **Simulated Annealing** ❄️
4. **Tabu Search** 🚫
5. **Ant Colony Optimization (ACO)** 🐜
6. **Recursive Grid Search Refinement** 🔍
7. **Population-Based Methods:** 🧬
   - Evolutionary Algorithm (EA)
   - Differential Evolution (DE)
   - Particle Swarm Optimization (PSO)

### Benchmark Function: `rubies`
- A quadratic function with sinusoidal components and penalties for constraint violations. 💎

---

## Plots and Visualizations
- **Convergence Plots:** Track algorithm performance over iterations. 📈
- **3D Surface Plots:** Visualize the optimization landscape and optima. 🌄
- **Comparative Bar Charts:** Display best values achieved by each algorithm. 📊

---

## Acknowledgments

This project is inspired by advanced optimization techniques and demonstrates practical applications in R. Special thanks to the contributors and the R community for their excellent libraries and support. 🙏

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 📜

