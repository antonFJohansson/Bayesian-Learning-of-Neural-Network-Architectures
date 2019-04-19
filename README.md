# Bayesian-Learning-of-Neural-Network-Architectures

This is an implementation of the method from the article Bayesian-Learning-of-Neural-Network-Architectures (https://arxiv.org/abs/1901.04436).


This is my own implementation and if any errors are discovered then that could be due to my implementation and not the authors method.

The program is most easily run by using the mainFile.py which will run the entire program and then display some results for a toy data set. 

Parameters which can be controlled to get different results are

- The initilization for the different parameters.
- The prior beliefs about those parameters.
- The weight_factor which controls how much the prior loss affects the total loss.
- The number of samples in the training loop (does not seem to affect the results much though).
- The usual parameters for a neural network like learning rate, optimizer, number of layers etc.

These parameters have been chosen mostly empirically.

There is a notebook version of the code in NotebookVersion_n.
