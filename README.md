# The Linear Conjugate Gradient Method(Numerical Optimization)

A iterative optimization strategy for solving large systems of linear equations is called the conjugate gradient (CG) method. It is frequently employed in numerical computations, especially when solving linear equations that arise in a variety of scientific and technical applications.

For the purpose of resolving linear systems of equations, the Conjugate Gradient (CG) technique is a popular iterative procedure. By minimizing the quadratic form f(x)=0.5xTAx-bTx, the CG method attempts to solve the linear system Ax=b, where A is a symmetric positive-definite matrix.

The conjugate search directions are used in the CG method's technique to update the estimation of the answer. A new search direction is calculated after each iteration by adding the previous search directions in a linear fashion so that they are conjugate with respect to the A-matrix.

The Conjugate Gradient (CG) and Gradient Descent (GD) optimization methods for a particular quadratic function are compared in all three sets of data. In terms of the number of iterations necessary to reach the minimal function value as well as the gradient norm at the minimum, the CG approach performs better than the GD technique. The CG approach converged in just two rounds in all three circumstances, but the GD method took many more iterations. The CG strategy utilizes the structure of the quadratic function to accelerate convergence, making it more efficient than the GD strategy overall. Therefore, the Conjugate Gradient method is frequently the best option when dealing with quadratic functions.



Install python,dependent libraries and run .ipynb file.
