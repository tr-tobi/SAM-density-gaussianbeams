# SAM-density-gaussianbeams

## Python code used to generate the SAM density plots of for non-paraxial Gaussian beams 

The code calculates the diffraction pattern by computing the intensity of the wave function at each point in a grid of points that covers the aperture.

The intensity I at a point (x,y) is given by:

![image](https://github.com/user-attachments/assets/8859e8ca-a48e-4442-81d0-ac9a0ccff4a3)


To compute the intensity at each point, the code first iterates over all the points in the grid and computes the polar coordinates r and θ for each point. It then uses the expression for R(r) to compute the radial part of the wave function at that point, and computes the intensity I by squaring the absolute value of the wave function. Finally, the intensity value is stored in the appropriate position in the raw array. The code then normalises the values in the raw array and matplotlib is used to display the plot.
