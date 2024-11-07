# Cutting Stock Optimization with Genetic, Simulated Annealing, and Hill Climbing Algorithms

This project implements and analyzes three optimization algorithms—Genetic Algorithm, Simulated Annealing, and Hill Climbing—to solve the **Cutting Stock Problem**. This classic problem involves minimizing material waste while cutting materials to fulfill specific size requests.

## Problem Overview

The **Cutting Stock Problem** is an NP-hard problem where the goal is to cut standard-sized stock materials (e.g., rolls of paper) to meet specific size requests with minimal waste. For example, if we have a 10-meter roll and requests for 3, 5, and 7 meters, we aim to cut the roll in a way that meets these requests while minimizing leftover material.

The specific objectives for this project are to optimize solutions for four different input scenarios by minimizing the total number of rolls required.

<div style="text-align: center;">
    <img src="./assets/Screenshot 1403-08-17 at 12.12.26.png" alt="drawing" width="330"/>
</div>

## Requirements

The project must fulfill the following criteria:

1. Use fewer than 56 rolls for **input1**
2. Use fewer than 80 rolls for **input2**
3. Use fewer than 115 rolls for **input3**
4. Use fewer than 235 rolls for **input4**

## Solution Approach

This project explores three AI-based optimization methods:

- **Genetic Algorithm**: An evolutionary algorithm inspired by natural selection, leveraging crossover, mutation, and selection strategies to evolve solutions.
- **Simulated Annealing**: A probabilistic technique that avoids local minima by allowing occasional moves to worse solutions, aiming to converge to an optimal solution over time.
- **Hill Climbing**: A heuristic search that iteratively makes small changes to improve the solution, suitable for problems where local optimization is effective.

Each algorithm is tailored to suit the constraints and objective of the cutting stock problem, with custom parameters to enhance performance.

## Files

- **AI_HW2.pdf**: Problem description and requirements.
- **HW02.ipynb**: Contains the full implementation and report. This notebook includes:
  - Code for each optimization algorithm
  - Parameter tuning and testing
  - Detailed analysis of results and performance comparison

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: `numpy`, `matplotlib`, and any other dependencies specified in the notebook.

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/MohaZamani/Cutting-Stock-Optimization.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook HW02.ipynb
   ```
3. Run the cells sequentially to execute the implementations and view the results.

## Results

The notebook provides a comprehensive analysis of each algorithm's effectiveness in minimizing roll usage for each input case. Performance improvements were achieved through careful parameter selection, resulting in optimal solutions that meet or exceed the specified roll limits.
