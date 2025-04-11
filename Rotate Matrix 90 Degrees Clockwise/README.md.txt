# Rotate Matrix 90 Degrees Clockwise

This project involves creating a matrix of random numbers, and then rotating the matrix 90 degrees clockwise. The program demonstrates how to manipulate 2D arrays and perform matrix transformations in C++.

## Functionality

1. **Matrix Creation**: The program generates a matrix with random numbers between 0 and 99.
2. **Matrix Rotation**: It rotates the matrix by 90 degrees clockwise.
3. **Memory Management**: The program properly allocates and deallocates memory for dynamic 2D arrays.

## How it works

- The program first asks for matrix dimensions (set to 4x4 in the example).
- It then fills the matrix with random values.
- The matrix is printed, followed by the rotated version of it (90 degrees clockwise).
- Memory is freed after the operations to avoid memory leaks.

## Example

**Initial Matrix:**

10 20 30 40
50 60 70 80
90 100 110 120 130 140 150 160

**Matrix after 90-degree rotation clockwise:**

130 90 50 10 140 100 60 20 150 110 70 30 160 120 80 40

## Compilation and Execution

**Compiling**: To compile the program, use a C++ compiler Visual Studio