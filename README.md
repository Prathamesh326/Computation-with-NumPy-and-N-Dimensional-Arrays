# Computation with NumPy and N-Dimensional Arrays

This repository contains a comprehensive introduction to using NumPy for numerical computations and working with N-dimensional arrays in Python. The notebook walks through various concepts, challenges, and exercises to help you master the powerful ndarray in NumPy.

## Table of Contents
1. [Introduction](#introduction)
2. [Import Statements](#import-statements)
3. [Understanding NumPy's ndarray](#understanding-numpys-ndarray)
    - [1-Dimensional Arrays (Vectors)](#1-dimensional-arrays-vectors)
    - [2-Dimensional Arrays (Matrices)](#2-dimensional-arrays-matrices)
    - [N-Dimensional Arrays (Tensors)](#n-dimensional-arrays-tensors)
4. [NumPy Mini-Challenges](#numpy-mini-challenges)
    - [Challenge 1: Create a Vector with `.arange()`](#challenge-1-create-a-vector-with-arange)
    - [Challenge 2: Python Slicing Techniques](#challenge-2-python-slicing-techniques)
    - [Challenge 3: Reverse an Array](#challenge-3-reverse-an-array)
    - [Challenge 4: Non-Zero Elements Indices](#challenge-4-non-zero-elements-indices)
    - [Challenge 5: Generate a 3x3x3 Array with Random Numbers](#challenge-5-generate-a-3x3x3-array-with-random-numbers)
    - [Challenge 6: Use `.linspace()` to Create a Vector](#challenge-6-use-linspace-to-create-a-vector)
    - [Challenge 7: Plot a Line Chart Using Matplotlib](#challenge-7-plot-a-line-chart-using-matplotlib)
    - [Challenge 8: Generate a 128x128x3 Array with Random Values](#challenge-8-generate-a-128x128x3-array-with-random-values)
5. [Linear Algebra with Vectors](#linear-algebra-with-vectors)
6. [Matrix Multiplication with @ and `.matmul()`](#matrix-multiplication-with--and-matmul)
7. [Manipulating Images as ndarrays](#manipulating-images-as-ndarrays)
    - [Image Conversion to Grayscale](#image-conversion-to-grayscale)
    - [Image Manipulation Challenges](#image-manipulation-challenges)
8. [Use Your Own Image](#use-your-own-image)
9. [Challenge Solutions](#challenge-solutions)

## Introduction
In this notebook, we explore how to use NumPy for performing numerical computations and manipulating N-dimensional arrays. NumPy’s ndarray is a powerful tool that allows for efficient computation and manipulation of large datasets, and this notebook will guide you through the basics of using it.

## Import Statements
We start by importing essential libraries like NumPy, Matplotlib, SciPy, and PIL for image processing and numerical computations.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy import misc
from PIL import Image
```

## Understanding NumPy's ndarray
NumPy's ndarray is at the core of numerical computation in Python. This section covers how to create and manipulate arrays of various dimensions.

### 1-Dimensional Arrays (Vectors)
Learn how to create and access elements in 1D arrays.

### 2-Dimensional Arrays (Matrices)
Understand how to work with 2D arrays, including accessing elements, slicing, and reshaping.

### N-Dimensional Arrays (Tensors)
Explore the concept of N-dimensional arrays, how to access and manipulate their elements.

## NumPy Mini-Challenges
This section provides a series of challenges to help you test and solidify your understanding of NumPy's ndarray.

### Challenge 1: Create a Vector with `.arange()`
Use `.arange()` to create a vector with values ranging from 10 to 29.

### Challenge 2: Python Slicing Techniques
Practice slicing arrays to extract specific elements or subsets.

### Challenge 3: Reverse an Array
Learn how to reverse the order of elements in an array.

### Challenge 4: Non-Zero Elements Indices
Identify the indices of non-zero elements in an array.

### Challenge 5: Generate a 3x3x3 Array with Random Numbers
Use NumPy's random function to create a 3-dimensional array filled with random numbers.

### Challenge 6: Use `.linspace()` to Create a Vector
Generate a vector with evenly spaced values using `.linspace()`.

### Challenge 7: Plot a Line Chart Using Matplotlib
Use the generated vectors to plot a line chart.

### Challenge 8: Generate a 128x128x3 Array with Random Values
Create a 128x128x3 array and visualize it as an image.

## Linear Algebra with Vectors
Explore vector operations, including addition, multiplication, and dot products.

## Matrix Multiplication with @ and `.matmul()`
Understand how to perform matrix multiplication using the `@` operator and `.matmul()` function.

## Manipulating Images as ndarrays
Learn how to manipulate images using NumPy arrays, including converting images to grayscale, flipping, rotating, and inverting colors.

### Image Conversion to Grayscale
Convert a color image to grayscale using matrix operations.

### Image Manipulation Challenges
Flip, rotate, and invert images using NumPy operations.

## Use Your Own Image
This section shows how to use PIL to open your own images and manipulate them using NumPy.

## Challenge Solutions
All solutions to the challenges are provided here for reference.

---

## How to Run
Clone the repository and run the notebook using Jupyter or any compatible environment:

```bash
git clone https://github.com/Prathamesh326/Computation-with-NumPy-and-N-Dimensional-Arrays.git
cd Computation-with-NumPy-and-N-Dimensional-Arrays
jupyter notebook
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.
