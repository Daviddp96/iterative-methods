Linear systems of equations, represented by the equation Ax = b, are ubiquitous in scientific computing. While direct methods like LU decomposition offer a guaranteed solution in a finite number of steps, their computational cost can become prohibitive for large and sparse matrices. This is where iterative methods shine.

This notebook explores three popular iterative methods for solving linear systems: Jacobi, Gauss-Seidel, and Conjugate Gradient. Each method approaches the solution through successive approximations, aiming to converge to the true solution within a desired tolerance.

