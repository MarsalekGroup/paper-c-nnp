# Supplementary data for a paper on committee neural network potentials

This repository contains supplementary data supporting the findings of the paper:

Committee neural network potentials control generalization errors and enable active learning  
Christoph Schran, Kyrstof Brezina, and Ondrej Marsalek


## Contents

* `generation-1`  
All parameters and the associated training set of the C-NNP model from generation 1 of the active learning procedure.
* `generation-4`  
All parameters and the associated training set of the C-NNP model from generation 4 of the active learning procedure.
* `test-set`
The independently generated test set split into the various state points and conditions separately for classical and quantum nuclei.
* `setup-DFT`  
CP2K input examples with the settings used for reference revPBE0-D3 calculations and preparatory revPBE calculations. Based directly on the original ab initio setup in [10.1021/acs.jpclett.7b00391](https://www.doi.org/10.1021/acs.jpclett.7b00391).

All data sets are provided in the format used for by the n2p2 program. NNP training input files for n2p2 are provided together with the resulting models, which can be evaluated directly in n2p2 or using the LAMMPS simulation package compiled with support for n2p2.