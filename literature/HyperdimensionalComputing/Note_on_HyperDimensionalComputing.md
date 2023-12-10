# Note on Hyper-Dimensional Computing

## Hyper-vectors

In order to illustrate the usefulness of hyper-vectors in modeling of semantic concepts we will consider simple example.
Let's find a vector to represent the variables `SHAPE` and `COLOR`. We will need vectors for the values which can be assigned to the variables: `CIRCLE`, `SQUARE`, `BLUE` and `RED`.

## Creating representations of concepts

In a space with large enough number of dimensions  we will be able to assign random vectors to represent the six items `SHAPE`, `COLOR`, `CIRCLE`, `SQUARE`, `BLUE`, and `RED` with large enough probability. Those random vectors will be _nearly orthogonal_. Near-orthogonality of the newly created vectors is an important property which will model the independence of semantic concepts such as `SHAPE` and `COLOR`. 

## Binding of concepts

A reasonable way of modeling a _binding_ of two concepts into a new bound concept is to multiply the hyper-vectors representing the original unbound concepts. The new vector representing the new bound concept "`SHAPE` is `CIRCLE`" will be nearly othogonal to both of the original vectors representing `SHAPE` and `CIRCLE`.  
