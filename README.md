# Sorting Algorithm Comparison: Insertion-sort vs Merge-sort

This repository contains a comprehensive comparison between two fundamental sorting algorithms: Insertion-sort and Merge-sort. Through a series of experiments conducted in Python, this project aims to illustrate the efficiency and performance of each sorting algorithm under various conditions. The analysis is performed on lists of different sizes and types, including random, sorted, reversed, and nearly sorted lists.

## Introduction

Sorting algorithms are essential for organizing data in a specific order, which is a common requirement in computer science and programming. The performance of a sorting algorithm is crucial for the efficiency of data processing tasks. This project compares Insertion-sort, a simple yet efficient algorithm for small datasets, with Merge-sort, a more complex but highly efficient algorithm for larger datasets.

## Project Structure

- `InsertionSort_vs_MergeSort.ipynb`: A Jupyter notebook that contains the implementation of both sorting algorithms, along with the experiments and analysis of their performance.
- `README.md`: This file, providing an overview of the project and instructions on how to run the experiments.

## Algorithms Overview

### Insertion-sort

- **Time Complexity**: O(n^2) in the worst case
- **Space Complexity**: O(1)
- **Best For**: Small datasets or nearly sorted datasets

### Merge-sort

- **Time Complexity**: O(n log n) in all cases
- **Space Complexity**: O(n)
- **Best For**: Large datasets

## Running the Experiments

To run the experiments and analyze the performance of the sorting algorithms, follow these steps:

1. Ensure you have Python installed on your system.
2. Install Jupyter Notebook or use Jupyter Lab to open the `.ipynb` file.
3. Run each cell in the notebook to execute the sorting algorithms and generate the performance plots.

## Dependencies

- Python 3
- Jupyter Notebook or Jupyter Lab
- Matplotlib (for plotting the results)
- Random (for generating lists of different types)

## Installation

To set up the project environment, run the following commands:

```bash
pip install notebook matplotlib
