# Note on Hyper-Dimensional Computing

## Informal introduction to Hyper-vectors using analogies and simple examples

In order to illustrate the usefulness of hyper-vectors in modeling of semantic concepts we will consider simple example.
Let's find a vector to represent the variables `SHAPE` and `COLOR`. We will need vectors for the values which can be assigned to the variables: `CIRCLE`, `SQUARE`, `BLUE` and `RED`.

### Creating representations of concepts

In a space with large enough number of dimensions  we will be able to assign random vectors to represent the six items `SHAPE`, `COLOR`, `CIRCLE`, `SQUARE`, `BLUE`, and `RED` with large enough probability. Those random vectors will be _nearly orthogonal_. Near-orthogonality of the newly created vectors is an important property which will model the independence of semantic concepts such as `SHAPE` and `COLOR`. 

### Binding of concepts

A reasonable way of modeling a _binding_ of two concepts into a new bound concept is to multiply the hyper-vectors representing the original unbound concepts. The new vector representing the new bound concept "`SHAPE` is `CIRCLE`" will be nearly othogonal to both of the original vectors representing `SHAPE` and `CIRCLE`. Note that the individual components will be recoverable which is important requirement to extract information from bound vectors. For example, given a bound vector representing your `Chevy Cruze`, you should be able to unbind it and retrieve the vector of its color: `SILVER`. 

### Superposition of concepts

Superposition of concepts is modeled through addition of hyper-vectors. For example. we can take two bound vectors , "`SHAPE` is `CIRCLE`" and "`COLOR` is `RED`", and add them together to create a vector that represents a circular shape that is red in color.  As before, a requirement is to extract information from  the superposed vector via decompostion into its constituents.

### Building structures out of semantic concepts

To build structures out of semantic concepts represented by hyper-vectors we need to be able to rearrange individual elements (segments) of the hyper-vectors. Permutation allows to deal with sequences: consider two events represented by the hyper-vectors `A` and `B`.  Adding `A` and `B` blindly into a new hypervector would destroy information about the order of the events. Combining addition with permutation preserves the order; the events can be retrieved in order by reversing the
operations.


### Properties of semantic representations

Representation of semantic concepts must satisfy at least one condition - it must _discriminate_: 
the patterns representing different concepts or sub-concepts must differ from each other. 

* Hyper-dimensionality

* Robustness

   _Robustness_ as a tolerance to individual component failures. The robustness comes from redundant representation, in which many patterns are considered equivalent and mean the same thing. A property of hyper-dimensional representation is that the number of places at which equivalent patterns may differ can be come quite large. As a result , the _proportion_ of allowable "errors", that is - the number of _redundant_ representations, increases with dimensionality. Ways to achieve
   redundancy and rubstness are listed and discussed below.

   - Replication
     
     _Replication_ is a simple way to achieve redundancy and robustness.

## The Hyper-dimensional computer

