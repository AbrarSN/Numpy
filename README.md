# Numpy
# NumPy Fundamentals and Array Operations

## Overview
This repository contains a Jupyter Notebook demonstrating essential operations using the `numpy` library in Python. It serves as a foundational guide for machine learning engineers and data scientists to understand array manipulation, vectorization, and matrix operations, which are critical for data preprocessing and model development.

## Topics Covered

The notebook is structured into several key components of tensor and array manipulation:

### 1. Array Operations
- **Initialization**: Creating basic 1D arrays using `np.array()`.
- **Element-wise Arithmetic**: Performing vectorized addition (`+`) and multiplication (`*`) between arrays.
- **Mathematical Functions**: Applying universal functions (ufuncs) such as square root calculation (`np.sqrt()`).

### 2. Indexing and Slicing (Accessing Elements)
- **1D Indexing**: Retrieving individual elements based on their positional index.
- **1D Slicing**: Extracting subsets of an array using slice notation (`start:stop`).

### 3. Boolean Indexing
- **Conditional Filtering**: Extracting elements that satisfy specific logical conditions (e.g., selecting elements strictly greater than a threshold value).

### 4. Reshaping of Arrays
- **Sequence Generation**: Creating linear sequences using `np.arange()`.
- **Dimensionality Manipulation**: Altering the shape of arrays without changing their data using `.reshape()` (e.g., transforming a 1D array of 10 elements into `2x5` and `5x2` matrices).
- **Multi-dimensional Slicing**: Accessing row and column subsets from 2D reshaped matrices.

### 5. Matrix Multiplication
- **Matrix Initialization**: Generating utility matrices, such as arrays filled with ones (`np.ones()`).
- **Dimensionality Checking**: Inspecting matrix dimensions using the `.shape` attribute to ensure compatibility.
- **Dot Product**: Performing standard matrix multiplication using `np.dot()`.

## Prerequisites
To execute the code in this notebook, ensure your environment has the following installed:
- Python 3.x
- NumPy (`pip install numpy`)
- Jupyter Notebook or JupyterLab (`pip install jupyter`)

## Usage
1. Clone this repository or download the notebook file to your local machine.
2. Navigate to the directory containing the file in your terminal.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
