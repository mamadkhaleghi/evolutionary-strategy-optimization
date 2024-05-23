# Evolutionary Strategy for Optimization

## Overview
This repository contains an implementation of an Evolutionary Strategy (ES) algorithm for solving various optimization problems. The algorithm uses mutation, selection, and crossover operations to evolve a population of solutions over multiple generations, aiming to find the optimal solution for given objective functions.

## Features
- **Uncorrelated n-step Mutation**
  - Applies adaptive step-size mutations to evolve the solutions.
- **Parent Selection**
  - Implements tournament selection to choose parents for generating offspring.
- **Objective Functions**
  - Includes different objective functions (F1, F2, F3) to test the ES algorithm.
- **Evolutionary Algorithm**
  - Combines mutation and selection to evolve a population of solutions over multiple generations.
- **Multiple Configurations**
  - Allows experimentation with different values of miu (population size), lam (number of offspring), and number of generations.

## Files
- **`evolutionary_strategy.py`**: Contains the main implementation of the Evolutionary Strategy algorithm and helper functions.
- **`.tsp files`**: Contains several .tsp files with city coordinates used as input data for testing the algorithm.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Python 3.6 or higher
- Libraries: numpy, tqdm

You can install the required packages using the following command:
```bash
pip install numpy tqdm
