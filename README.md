# MOBO tutorials
The repository contains Multi-objective Bayesian optimization (MOBO) framework, integrated to unconstrained multi-objective optimization of different physics based numerical models.
The MOBO framework in build under GpyTorch/BoTorch package.

**Guide to tutorials**:

Start with "**SimpleGP/BO tutorial.ipynb**". Here we illustrate 1D Gaussian Process and search space exploration by maximizing acquisition function (using BO).

Then check "**Classical MOBO tutorial.ipynb**". Here we extend from BO to MOBO, and illustrate MOBO implementation to non-physics toy problems.

Then check the below two notebooks where we implemented MOBO with complex physics based models.

"**PhysicsDriven MOBO (PZO) tutorial.ipynb**"- Here we extend to **MOBO implementation to a bulk antiferroelectric PZO model**.

"**PhysicsDriven MOBO (FerroSim) tutorial.ipynb**" - Here we extend to **MOBO implementation to a kinetic lattice simulation model of a ferroelectric with a double well potential and a vector order parameter $(P_x,P_y)$ at each site**. More on FerroSim model can be found here: FerroSim Model: https://github.com/ramav87/FerroSim

**Example (PZO): Exploration over parameter space containing FE and AFE hysteresis loops:**

**Building Pareto front to maximize energy storage and loss for with Multi-objective Bayesian optimization**

![image](https://user-images.githubusercontent.com/19354142/217886178-a0f51fd1-ab19-45ef-af64-d197a4ce24f2.png)

Check the latest versions of the above mentioned titles. The other files are older versions.

In future, more examples will be added.
Also, the framework will be extended to solve constrained problems.




