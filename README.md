# CPEN400Q-FinalProject

# Project Dependencies
1. Pennylane >= v0.29.1
2. Matplotlib >= v3.7.1

# How To Run
- To reproduce any results, just run the notebook in order until "Reproducing Results"
- Reproducing results contains the simulations for the following and you can run whichever result you would like to reproduce
    - Bitflip Noise Model
    - Phaseflip Noise Model
    - Training Wasserstein on Alpha, Beta from Fidelity
    - Training Fidelity on Alpha, Beta from Wasserstein
- Note that running the entire notebook could take a long time (~30 hours potentially) due to the number of iterations and simulations needed for gradient descent

# Contributions
## Claire Song
- Understanding the calculation of Hamiltonians and Cost Functions for Fidelity and Wasserstein
- Implementation of Hamiltonian calculations
## Justin Hua
- Code for encoding and noise correction unitaries
- Kraus matrices for bit-flip noise
## Matthew Chow
- Code for running the simulations and results minus creating the unitaries
## Matthew Yen
- Kraus matrices for phase-flip noise
- Implementation of VQA with cost calculations

