# 6-4PP-paper-data

Repository to store the models and scripts required to reproduce our paper "Minimum Energy Pathway for Lesion
Recognition and DNA Binding by RAD4/XPC". All simulations were performed using Amber18, and analysis was using done using MDAnalysis 2.7.0 and cpptraj V6.18.1.

The data is stored in 4 separate directories, models, analysis, scripts, and pathway. 

Models - Contains the non-solvated pdb of the endstates, as well as prmtop files and inpcrd files for both solvated and minimized endstates.

Scripts - Contains representative amber simulation scripts for model minimization, unbiased simulations in the NPT ensemble, umbrella sampling and restrained sampling, and NEB optimization. Also contains a groupfile for running NEB simulations.

Analysis - Contains notebook CV.ipynb, with all collective variable definitions used in the paper, and a cpptraj script using the NAstruct module to extract the twist angle.

Pathway - Stores a dcd file of the converged NEB pathway at 0 K.