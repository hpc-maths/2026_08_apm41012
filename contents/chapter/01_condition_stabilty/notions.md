# Essential notions

[The first notebook](./error.ipynb) of this section shows how working with a finite representation of numbers on a machine leads to the loss of certain mathematical properties and to "rules" for implementing certain sequences of operations.

A classical area of numerical analysis is the solution of linear systems, which will be the subject of Chapter 4 and for which we will define the notion of the conditioning of a matrix. In the meantime, [a second notebook](conditioning.ipynb) helps to understand the influence of the structure of the matrix on the conditioning of the problem and to have a graphical illustration of it. This interpretation clearly shows that conditioning is an intrinsic property of the problem being solved and has nothing to do with any particular numerical solution method.

In [the third notebook](stability.ipynb), we deal with the stability of an algorithm in the case:
- of evaluating a scalar function at a point where the evaluation is ill-conditioned: the reader will observe that the choice of the evaluation algorithm has an impact on the quality of the result when working with an ill-conditioned problem;
- of evaluating a scalar function where the evaluation is well-conditioned: in this case, the use of an algorithm that is not very backward stable can lead to a loss of precision, possibly catastrophic.
