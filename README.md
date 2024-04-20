# Traveling Salesman Problem Solver

## Overview
This repository provides solutions for the Traveling Salesman Problem (TSP) using both dynamic programming and a metaheuristic approach, specifically the General Variable Neighborhood Search (GVNS). The aim is to compare the efficacy and performance of these methods on different instances of TSP problems, emphasizing why certain methods are preferred for larger instances.

## Introduction to TSP
The Traveling Salesman Problem (TSP) is a well-known combinatorial optimization problem, which requires finding the shortest possible route that visits a list of cities and returns to the origin city. It is NP-hard, meaning that the time required to solve the problem increases exponentially with the number of cities.

## Methods Used

### Dynamic Programming
Dynamic Programming (DP) solves problems by breaking them down into simpler subproblems and storing the results of these subproblems to avoid computing the same results multiple times. For TSP, the DP approach ensures finding an optimal solution by exploring all possible tours, but it becomes impractical for larger datasets due to its exponential time complexity.

### Metaheuristic: General Variable Neighborhood Search (GVNS)
Metaheuristics are strategies designed to find, generate, or select heuristics that may provide a sufficiently good solution to an optimization problem, especially with incomplete or imperfect information. GVNS is a robust metaheuristic that systematically changes the neighborhood structures within which local search is applied, aiming to bring a good balance between exploring new regions and exploiting known promising areas.

## Project Structure

- `TSP_programmation_dynamique.ipynb`: Implementation of the TSP using the dynamic programming approach.
- `TSP_Métaheuristique_GVNS.ipynb`: Implementation of the TSP using a metaheuristicc method, General variable neighborhood search (GVNS).
- `data/`: Directory containing sample TSP problem datasets.
- `results/`: Directory where results and graphs are saved.

## Technologies
- Python 3.8+
- NumPy
- Matplotlib (for visualization)

## Setup
Clone this repository :
```bash
git clone <repository-url>
cd <repository-directory>
