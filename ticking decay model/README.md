# Notes on determining model size #

## The human heart ##
The average heart contains an estimated 2-3 billion 
cardiac muscle cells - making up for 1/3 of all cells in the heart.
Average size is 12cm long and 8-9cm wide and 2.5cm deep.


## Modelling the left atria ##
From the paper "Mechanisms of stochastic onset and termination of atrial 
fibrillation studied with a cellular automaton model", the left atria is 
40ml, which has a radius of 21.1mm.

Translated to a square, with area 1398.7mm^2.

The mitral valve at the bottom have the circumference of 85mm, radius of 13.5mm.
Giving it an area of 574.9mm^2

The 4 ventricles have a base radius of 5mm. Giving it an area of 78.5mm^2 (x4).

One ventricle should take up 1.77% of the square.
The mitral valve should take up 41.1% of the square.

## Current model ##
Using a model square of 200x200 cells.

One ventricle should take up 708 cells. Giving it a radius of 15.0 units.
The mitral valve should take up 16440 cells. Giving it a depth of 82.2 units.