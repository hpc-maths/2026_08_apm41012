# Essential notions

To begin with, we return to [the Curtiss and Hirschfelder equation](./curtiss_rk.ipynb), which is a very good toy model allowing one to play with the stiffness of the system and to illustrate the notion of linear stability, or absolute stability. In particular, we consider explicit methods in connection with stiffness and with the stability diagram, in order to see the impact of the stiffness and of the order on the results.

We then deal with [the system of equations of Belousov and Zhabotinsky](./brusselator_rk.ipynb) (oscillating chemical reactions) in order to study the computational cost at fixed accuracy.

Finally, the whole set of methods is tested on the highly nonlinear problem of [the thermal explosion](./explosion_rk.ipynb). This scalar equation involves positive real eigenvalues of very large magnitude in an initial explosion-type regime, and then negative real eigenvalues of very large magnitude leading to very strong stiffness at the end of the integration. We illustrate the fact that, for this type of problem, the "right" strategy consists in using a high-order implicit method with adaptive time stepping, of Radau 5 type.
