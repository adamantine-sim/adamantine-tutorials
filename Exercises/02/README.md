Set the boundary conditions and the time step
=============================================
The goal of this exercise is to set boundary conditions and the time step used in the simulation.
In order to do this, you will need to modify the `input.info` file. You can run the exercise using 
`./adamantine -i input.info`. The solution of the exercises is given in `solution.info`. 

Please refer to the documentation in the
[boundary](https://adamantine-sim.github.io/adamantine/doc/input_file.html#boundary-required) 
and in the
[time\_stepping](https://adamantine-sim.github.io/adamantine/doc/input_file.html#time_stepping-required)
sections.

Extra exercises
---------------
* Use adiabatic boundary condition on the bottom of the domain (Boundary ID: 4).
* Increase the time step size until the simulation diverges.
* Do not set the final end time. Instead modify the scan path to end the
simulation.
