# GA and PSO libraries in Python

> Practice training a simple neural network (MLP) using the [geneticalgorithm](https://pypi.org/project/geneticalgorithm/) and [pyswarm](https://pypi.org/project/pyswarm/) libraries in Python, to solve a simple sum problem.

Genetic algorithms and Particle Swarm Optimization are approaches for optimizing the parameters of very complex, often highly dimensional functions, which are virtually impossible to be optimized analytically. 

In some circumstances, they lend extremely well to the training of neural networks, where we are looking to optimize the parameters to the network- the weights- in order to minimize a loss function, which represents error over a training dataset. This is a radically different approach to backpropagation plus gradient descent, which is a much more commonly used technique.
