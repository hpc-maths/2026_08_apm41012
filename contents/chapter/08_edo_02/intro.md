# Introduction

Having introduced, within the framework of "simple" first-order methods, the fundamental concepts that are found in many numerical analysis studies (definitions of stability, definitions of local truncation error and of global error, convergence, order, notion of stiffness), we are now going to address in a more general way the analysis of high-order one-step methods.

The idea is to be more accurate at constant computational cost, or more efficient in terms of computation at fixed accuracy. We shall therefore take up the notions covered in the previous chapter and deepen them within the framework of the presentation and the analysis of Runge-Kutta methods.

In the [notebook of this section](./explosion_euler.ipynb) we show the limits of first-order methods in the case of the thermal explosion, and the need to increase the order and to adapt the time step.
