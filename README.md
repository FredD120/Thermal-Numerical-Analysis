# Thermal Numerical Model
#Implementation of the Runge-Kutta 4 numerical method for solving nonlinear ordinary differential equations. Will try use it to solve the heat equation in one and two dimensions.
#Update: RK4 is not useful for the finite differential method, so using Euler method to solve nonlinear ODEs instead. This is because I have solved in one dimension for around 100 elements using explicit algorithm, but going higher massively increases computing time as the algorithm is divergent if time step is too small. Will try to implement implicit algorithm using linear algebra, but trying to invert the RK4 version of this algorithm would be very difficult. 
