# Physics-ML

This repo contains jupyter notebooks in which I implement several scientific ML models from scratch using Torch to solve the 1D heat/diffusion equation. The models used are
 - standard transformer stack
 - PINN
 - Fourier Neural Operator (FNO)

The first and third models are the most conceptually similar, as they simply propagate initial conditions forward in time a fixed amount. In both cases, the initial conditions consist of a random collection of a fixed number of Fourier modes. 

I was not able to get the PINN to converge.
