# Introduction

Chapter 1 of the course introduces two notions that will be a common thread throughout the course: *the conditioning of a mathematical problem* and *the stability of an algorithm* used to solve it. These notions are part of the detailed study of algorithms and are often at the heart of the connection between numerical analysis and various branches of mathematics.

The study of algorithms assumes that one can predict how an implementation on a machine behaves, that is, that one can analyze the impact of a representation of real numbers on a machine and the associated rounding through these two notions.

In this context, a reminder about the representation of reals on a machine and the manipulation of arbitrary-precision floating-point numbers is in order, together with examples of potential errors that can be generated when implementing a numerical method on a computer and their connection, in simple cases, with conditioning and stability.

In this chapter of the JupyterBook, the reader will find examples illustrating this type of error generation, whether it leads to a loss of significant digits or to more dramatic errors.

In order to analyze the influence of rounding errors on the results, it is convenient to be able to carry out computations at a user-defined precision, and we rely on the mpmath module, which is presented in [the first notebook of this section](./mpmath.ipynb).