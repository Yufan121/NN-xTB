# NN-xTB: Neural-Network Extended Tight Binding

This repository accompanies the paper:

**Neural-network extended tight binding approach for DFT-level accuracy of main-group chemistry**

Yufan Xia, Albert Thie, Joshua Soon, and Giuseppe Barca

*Nature Communications* (2026). DOI: [to be added upon publication]

## Overview

NN-xTB is a neural-network extension of the GFN2-xTB semi-empirical quantum chemistry method. Rather than predicting molecular energies or forces directly, NN-xTB uses an equivariant graph neural network to predict environment-dependent corrections to Hamiltonian parameters, which are then used within a self-consistent field calculation to compute all molecular properties. This Hamiltonian-preserving approach achieves density functional theory-level accuracy at near semi-empirical cost.

## Code Availability

The source code for NN-xTB is not yet publicly available. We are working towards an open-source release and will make the code available in this repository when ready. Please watch or star this repository to be notified of future updates.

For questions or collaboration inquiries, please contact: giuseppe.barca@monash.edu

## License

To be determined upon release.
