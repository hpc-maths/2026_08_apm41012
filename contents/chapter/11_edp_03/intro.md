# Introduction

In this chapter, we focus our attention on linear and nonlinear advection equations, in the same spirit as in Chapter 9. We first focus on the linear advection equation and then on the Burgers equation (1948), introduced in the context of turbulence modeling. These equations are of hyperbolic type; they are simple representatives of the class of partial differential equations called systems of conservation laws (see the references in the lecture notes).

The key point of this chapter lies in the fact that these equations admit solutions in the classical sense, but also less regular solutions in the sense of distributions, which may contain singularities such as discontinuities (think of gas dynamics – the Euler equations and the notion of shock wave – see the illustrations in the lecture notes).

We do not dwell here on the theoretical part, which students interested in the functional analysis aspects will find in the course, but the notion of entropic weak solution makes it possible to guarantee the uniqueness of solutions in solution spaces that are very different from what we saw in Chapter 9. These solution spaces thus include discontinuous solutions that are much less regular than those studied previously.

Building a numerical scheme is then a somewhat more ambitious challenge, since the notions of consistency and order must be revisited in light of the notions of conservation and entropic weak solution.

The [notebook of this section](./limites.ipynb) shows the limits of first- and second-order schemes in the case of the linear advection equation.
