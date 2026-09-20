# Going further

Since in practice a preconditioner is used in order to achieve improved convergence, we have implemented [polynomial preconditioning](preconditioning.ipynb) of Chebyshev type (which lends itself well to parallelisation) for the conjugate gradient. Its impact on convergence is clear when solving the Poisson problem in 1D, 2D and above all in 3D, the most interesting case for iterative methods.
