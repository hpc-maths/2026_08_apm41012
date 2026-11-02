# Essential notions

In this section, we first focus on the heat equation, a linear scalar equation, and then address its nonlinear counterpart by adding a nonlinear source term, which yields a reaction-diffusion equation known as the Nagumo equation, which admits traveling-wave solutions.

In a [first notebook](./heat_edo.ipynb), we consider a set of first- and second-order, explicit and implicit, time integration methods to solve the heat equation, and we make the connection between the exact fundamental solution, the quasi-exact solution for a fixed spatial discretization, and the numerical solution of the PDE over a time and space interval. The orders of convergence predicted by the theory are recovered experimentally.

In a [second notebook](./vp_laplacien.ipynb), the notion of stiffness of the ODE system obtained previously is analyzed graphically (and theoretically in the lecture) on the basis of the spectrum of the continuous Laplace operator and of its spatial discretization by finite differences. We recover the conditioning of the discretization matrix of the Laplacian in $1/\delta x^2$, which is directly related to the moderate stiffness of the system.

In a [third notebook](./heat_edp.ipynb), we consider the notion of convergence in the PDE sense, in line with the Lax-Richtmyer theory. There are some subtleties here depending on how the space and time steps are linked, in particular when one has the freedom to choose them independently in the framework of implicit methods.
