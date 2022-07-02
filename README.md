# Solving the time-dependent Schroedinger equation 
## using the ’Finite Domain Time Difference Method’ for different simple static potential wells for a Gaussian wave packet.

## Project Summary

In this project the time-dependent Schroeodinger Equation has been solved using the ’Finite Domain Time Difference Method’ for different simple static potential wells for a Gaussian wave packet.
The behaviour of the particle waves exhibits the inherently quantum mechanical behaviour that is expected. The animations generated allow to gain physical intuition.

## Theory 

For the detailed Theory (Physical Conditions and Numerical Approximation) see **README_MiniProject_Solve_TDSE.pdf**

## Aims & Objectives
### Aims
- solve the time dependent Schr oeodinger equation using the ’Finite Domain Time Difference Method’
- demonstrate the working method on a few potentials
- comment on physical intuition gained

### Objectives
- discretize space and time
- implement a physical potential parameters
- implement physical particle/wave parameters
- generate potential wells: free, square, harmonic, step 
- demonstrate potential wells

## Method

All of the method is self contained and described the Mathematica notebook. Please see the Notebook.

### Usage of Code

This the Mathematica notebook contains all the calculations and some interactive animations.
For convenience all animation produced have been exported for ease of viewing as some calculations may take a few moments. Find the animations in the \animations folder.
All cells have been evaluated already to show the results. To rerun the calculations please evaluate all essential cells and user inputs cell consecutively. Note the color coding:
- light blue cells are essential to be run
- yellow cells require user input
- white cells are optional
- cells with a watch face mark may take 1-3 minutes to evaluate
In case errors occur please rerun the notebook in consecutive order. Note that occasionally the notebook may require time to reformat, a message will show Formatting Notebook Contents.

### References
[1] A fast explicit algorithm for the time-dependent Schr ̈odinger equation Computers in Physics 5, 596 (1991); https://doi.org/10.1063/1.168415 P. B. Visscher
