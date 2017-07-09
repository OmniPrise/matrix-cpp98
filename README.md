# matrix-cpp98
The C++ Matrix library provides methods for manipulating matricies and solvers for various types of problems, implemented in C++ style from 1998.  Features include:

* Matrix access methods to data
* Various matrix types like Banded, Upper Triangular, etc.
* Matrix augmentation, sub-matrices and matrix row/column vectors
* Basic matrix row operations
* Varous matrix decompositions and factorizations
* Solutions for Least Squares
* Solutions for Linear Programs to be added
* Convext Hull to be added
* Note: SVD and other algorithms that use \epsilon are not properly implemented and should be corrected

# Motivation
The original C++ Matrix library was written in an attempt to better understand "Benchmarking numerical accuracy of statistical algorithms", Lesage and Simon, 1988.  The code was implemented using "Matrix Computations" Third Edition, Golub and Van Loan, 1996.  Indeed, the wamplerTest.cpp is code written to produce results from the Lesage and Simon paper.



