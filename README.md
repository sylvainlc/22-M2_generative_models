# Simulation methods for generative models
## Table of contents

This course proposes an overview of classical methods to solve sampling-related problems for generative models.
Exercises and notebooks in Python are provided to understand the practical challenges in classical settings.

### [Lecture notes](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Lecture/poly.pdf) 
- Target distributions and examples  
- Variational Autoencoders
- Score-based diffusion models
- Basics in Markov chains (invariant probability measures, ergodicity and law of large numbers)
- Metropolis-Hastings algorithm
- Pseudo-maginal algorithms and Hamiltonian Monte Carlo

### Labs
- [VAE basics](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Lab/vae_basics.ipynb)\
Training of a simple VAE with detailed building blocks and example from Keras
- [Score-based diffusion models](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Lab/diffusionmodels_toy.ipynb)\
Full training of a score-based diffusion model on a toy example
- [Random walk Metropolis-Hastings algorithm](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Lab/mcmc_mh.ipynb)\
Introduction to invariant distributions and MH algorithms
- [MALA and Hamiltonian Monte Carlo](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Lab/mh_mala_hmc.ipynb)\
More Advanced MCMC algorithms using Hamiltonian and Langevin dynamics


### Exercises
- [Importance sampling and sequential Monte Carlo](https://github.com/sylvainlc/22-M2_generative_models/blob/main/Exercises/training_SMC.pdf)
