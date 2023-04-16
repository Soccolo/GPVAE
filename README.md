# CVAE
In this repository is the code for the Convolutional Variational Autoencoder used as part of my M4R project. The CVAE applies Convolutional Variational Autoencoders on the contact intensity data, while the GPCVAE takes 2D GP priors and applies the CVAE on them, afterward performing MCMC using the data from the Bayesian Rate Consistency Model paper.

A legend of the files:
data.rds = simulated intensities for male-female interactions
pop = simulated population of females of each age
dt = simulated number of male participants of each age
