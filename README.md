# CSA_Martini3
This github repository contains a coarse-grained Martini 3 model of chondroitin sulfate A (CSA) and simulation files related to manuscript:
  - Coarse-grained Martini 3 model of chondroitin sulfate A. Paulius Greicius, Frauke Graeter, Fabian Gruenewald, Camilo Aponte-Santamaria. bioRxiv 2025.10.20.683363; doi: https://doi.org/10.1101/2025.10.20.683363
    
If you use or wish to cite this model, please refer to the publication above.

## Repo Overview

This repository contains:  
  - Martini 3 model of chondroitin sulfate A (.ff and .map files): [./CSA_model](https://github.com/PaulGreic/CSA_Martini3/tree/main/CSA_model)
  - Files associated with single 21-mer CSA chain simulatoin in CHARMM36m (AA) and Martini 3 (CG) force-fields (.itp, .tpr, .mdp, .gro, .top files): [./21mer](https://github.com/PaulGreic/CSA_Martini3/tree/main/21mer)
  - Files assoacited wtih 4 21-mer CSA chain simulation in CHARMM36m (AA) and Martini 3 (CG) force-fields (.itp, .tpr, .mdp, .gro, .top files). CG directory contains simulations under different conditions: salt ion size (Q5 or TQ5), electrostatic potential (PME or Reaction-field) and salt ion charge ( $\pm 0.75$ or $\pm 1.0$): [./4Chains](https://github.com/PaulGreic/CSA_Martini3/tree/main/4Chains)
  - Files associate with Martini 3 simulation of CSA bound by VAR2CSA in equilibrium (EQ) and under pulling force (pull) (.itp, .tpr, .mdp, .gro, .top files): [./VAR2CSA](https://github.com/PaulGreic/CSA_Martini3/tree/main/VAR2CSA)
  - Files assocaited with Martini 3 simulation of single 123mer CSA chain (.itp, .tpr, .mdp, .gro, .top files): [./123mer](https://github.com/PaulGreic/CSA_Martini3/tree/main/123mer)
