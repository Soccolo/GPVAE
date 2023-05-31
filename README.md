# GPVAE
In this repository is the code for the VAE code used as part of my M4R project. The CVAE applies Convolutional Variational Autoencoders on the contact intensity data, while the GPCVAE takes 2D GP priors and applies a dense VAE on them, afterward performing MCMC using the data from Polymod.

A legend of the files:
data.rds = simulated intensities for male-female interactions
pop = simulated population of females of each age
dt = simulated number of male participants of each age
Y_data = Polymod observed values of y
Polymod Participants = data on the Polymod participants, used to generate the participants matrix
