# thousand brains hypothesis

Interesting talk which presents a collection of various concepts gleaned from recent developments in brain neuroscience.
 A new paradigm is presented serving as a counterpoint to the Deep Learning concept (aka hierarchical learning). So what if we build ML algorithms based on replicated building blocks (roughly corresponding to the brain's cortical columns) each of which is creating its own model of the reality based on a piece of the observed data it receives. The final representation of the reality is built based on voting and some consensus algorithm collecting the votes from thousands of replicated building blocks. Sparsity of the data and the size of the dimensionality leads to robustness of the representation (think compressed sensing). “Smart” neurons with built-in predictive reinforcement circuitry which can dynamically reconfigure the connections. Due to the predictive circuitry the network operates in unsupervised continuous learning mode. Since most of the computations are performed on sparse matrices we will be dealing with memory bandwidth issues when running these algorithms for which GPGPU architectures are not that helpful.

https://youtu.be/5LFo36g4Lug

For open source implementation of some of this concepts refer
to:

https://github.com/htm-community/htm.core
