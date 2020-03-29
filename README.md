# tSNE
An implementation of tSNE from scratch, following the algorithm described in the original tSNE paper.

tSNe, or t-Distributed Stochastic Neighbor Embedding, is a machine learning algorithm (unsupervised learning) that is used to reduce the dimensions of data in such a way that we can easily visualize clusters/neighborhoods in high-dimensional data sets.

The algorithm is at its core, gradient descent, but the complicated part in its implementation is implementing the loss function (based on Kullback–Leibler divergence, where we measure the difference between two probability distributions). 
