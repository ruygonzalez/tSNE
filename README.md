# tSNE
An implementation of tSNE from scratch, following the algorithm described in the original tSNE paper.

tSNe, or t-Distributed Stochastic Neighbor Embedding, is a machine learning algorithm (unsupervised learning) that is used to reduce the dimensions of data in such a way that we can easily visualize clusters/neighborhoods in high-dimensional data sets.

The algorithm is at its core, gradient descent, but the complicated part in its implementation is implementing the loss function (based on Kullback–Leibler divergence, where we measure the difference between two probability distributions). We view Euclidean distances between points as probabilities in the high dimensional space and we try to find a low-dimensional probability distribution that captures the probability distribution of the high-dimensional space. 

I test out the implementation of tSNE by generating points from a 3-component Gaussian mixture model with centroids that are clearly spaced out in 10-dimensional space, and show that tSNE produces visualizations with 3 clear clusters in 2-dimensional space (moreover, we color the points with the component aka. Gaussian distribution that generated the point to show that the clusters exactly represent the 3 components). 
