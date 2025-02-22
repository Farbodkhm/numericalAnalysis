# numericalAnalysis
Codes of lesson of numerical analysis in winter and spring of 2023.
All the exercises are there and in this order that I write here.

# Newton
In numerical analysis, Newton's method, also known as the Newton–Raphson method, named after Isaac Newton and Joseph Raphson, is a root-finding algorithm which produces successively better approximations to the roots (or zeroes) of a real-valued function. The most basic version starts with a single-variable function f defined for a real variable x, the function's derivative f′, and an initial guess x0 for a root of f. If the function satisfies sufficient assumptions and the initial guess is close, then

$x1 = x0 - f(x0)/f'(x0)$

is a better approximation of the root than x0. Geometrically, (x1, 0) is the intersection of the x-axis and the tangent of the graph of f at (x0, f(x0)): that is, the improved guess is the unique root of the linear approximation at the initial point. The process is repeated as

$xn + 1 = xn − f(xn)/f′(xn)$

until a sufficiently precise value is reached. The number of correct digits roughly doubles with each step. This algorithm is first in the class of Householder's methods, succeeded by Halley's method. The method can also be extended to complex functions and to systems of equations. 

This code calculate the answer of some equations that is hard to find its exact value.

# Dollar Price
In this code I analysis the price of dollar in Iran of after revolusion.
This analysis is in two way one of them is in simple way another one in logarithmic way.

# Integral
This code calculate the integral of some function that is hard to calculate its exact value.

# Difference
In this code I calculate the real answer of difference of function sin(3x) and its approximate value and plot table and chart to show that if we choose a small h we can find its approximate answer so close to real answer.

# Equation
In this code I solve the system of equation for answer one Differential equation that is unanswerable.

# Sympy Assignment
SymPy is a Python library for symbolic mathematics. It aims to become a full-featured computer algebra system (CAS) while keeping the code as simple as possible in order to be comprehensible and easily extensible. SymPy is written entirely in Python. 

This file is a set of 5 problems about sympy library.

__Problem 1:__ Finding derivative of functions by sympy.

__Problem 2:__ Finding the indefinite integral.

__Problem 3:__ Solve equations.

__Problem 4:__ Finding 10 terms of Fourier series.

__Problem 5:__ Find velocity and acceleration from function $x = 3sin(t) - 4sin(2t)$

# Numpy and Pandas
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

This file is a set of 3 problems about numpy and pandas.

__Problem 1:__ Numpy tasks

__Problem 2:__ Pandas tasks

__Problem 3:__ Bonus task

# Taylor
In mathematics, the Taylor series or Taylor expansion of a function is an infinite sum of terms that are expressed in terms of the function's derivatives at a single point. For most common functions, the function and the sum of its Taylor series are equal near this point.

In this file we plot taylor's and real functions of $\sin(x)$ and $\cos(x)$.

# Fourier
A Fourier series is an expansion of a periodic function into a sum of trigonometric functions. The Fourier series is an example of a trigonometric series, but not all trigonometric series are Fourier series. By expressing a function as a sum of sines and cosines, many problems involving the function become easier to analyze because trigonometric functions are well understood.

In this file we plot Fourier series and origin function of $x^3$.
