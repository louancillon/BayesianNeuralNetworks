# BayesianNeuralNetworks
Implementing a bayesian neural network for image recognition.

This project involves the implementation of a Bayesian neural network, utilizing the 'Bayes by Backprop' algorithm introduced by Blundell et al. (2015). The network is designed for multi-class classification on the MNIST dataset, with the test set incorporating added uncertainty through pixelation and random rotations. Additionally, the project includes calibration measurements for predictions, as outlined in Guo et al. (2017).

Key challenges include algorithm implementation, the selection of weight priors and variational posteriors, and considerations for calibration.

The baseline evaluation combines both accuracy and the empirical expected calibration error (ECE) to produce a compound score.
