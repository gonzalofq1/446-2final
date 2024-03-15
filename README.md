# Numerical Solution for the Swift-Hohenberg equation.


This is the the code for the final project for ESAM 446-2 with Prof. Daniel Lecoanet. This project was prepared by Gonzalo Ferrandez Quinto.

# Running the code

To regenerate the simulations presented in our report `Numerical_Solution_for_the_Swift-Hohenberg_Equation.pdf`, simply run the scripts in `SwiftPDE.ipynb` using a Python Kernel. This Jupyter notebook includes the code for all of our simulations and visualizations 
such as spectral.

If you want to check the code for the resolution study, run the file `resolution study code.ipynb`

# Changing Simulation Parameters

Most simulation parameters can be conveniently changed in `SwiftPDE.ipynb` by changing the initial conditions, parameters boundary lenght and timestep in the second cell block. 

I assume a square uniform domain, but the values and resolution of this domain can be adjusted by changing the variables `N` (resolution) and `L` (lenght).

To change the initial conditions, the definition of `INITIAL` can be changed in the second block of code.

To change the timestep, you can change the variable `dt` and the variable `total` to determine the number of time steps. 

In addition, you can select if you want a gif of your simulation to be saved in your directory, by doing `gif = true` or you prefer all the sliced photos by doing `gif = false`.
