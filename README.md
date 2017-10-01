# GradientDescentExampleInPython
Gradient Descent Example for Linear Regression
Code Requirements

The example code is in Python (version 2.X or version 3.X). The only other requirement is NumPy.

Description

This code demonstrates how a gradient descent search may be used to solve the linear regression problem of fitting a line to a set of points. In this problem, we wish to model a set of points using a line. The line model is defined by two parameters - the line's slope m, and y-intercept b. Gradient descent attemps to find the best values for these parameters, subject to an error function.

The code contains a main function called run. This function defines a set of parameters used in the gradient descent algorithm including an initial guess of the line slope and y-intercept, the learning rate to use, and the number of iterations to run gradient descent for.

initial_b = 0 # initial y-intercept guess
initial_m = 0 # initial slope guess
num_iterations = 1000
Using these parameters a gradient descent search is executed on a sample data set of 100 ponts. Here is a visualization of the search running for 200 iterations using an initial guess of m = 0, b = 0, and a learning rate of 0.000005.
