# Newton's Method with LU Decomposition

This project implements Newton's method combined with LU decomposition to solve systems of nonlinear equations. The implementation is done in Python.

## Features

- **Newton's Method**: Iterative root-finding algorithm for systems of nonlinear equations.
- **LU Decomposition**: Matrix factorization technique to solve linear systems efficiently.



## Usage

1. Define the system of nonlinear equations and its Jacobian matrix.
2. Initialize the Newton solver with an initial guess.
3. The solver will iterate until convergence or maximum iterations are reached.
4. Results are printed in a table format showing iterations, function values, and errors.

## Example

The example solves the system:
- \( f_1(x_1, x_2) = x_1^2 + x_2^2 - 1 = 0 \)
- \( f_2(x_1, x_2) = 5x_1^2 - x_2 - 2 = 0 \)

with various initial points.
