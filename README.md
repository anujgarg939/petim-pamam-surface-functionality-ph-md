# petim-pamam-surface-functionality-ph-md
# Surface Functionality and pH Govern Structural Dynamics and Drug Binding in PETIM and PAMAM Dendrimers

This repository contains molecular dynamics (MD) simulation files and analysis data associated with the study:

**“Surface Functionality and pH Govern Structural Dynamics and Drug Binding in PETIM and PAMAM Dendrimers”**

## Overview

This work investigates how **surface functionalization, protonation state, dendrimer generation, and core architecture** influence the structural and dynamic properties of PAMAM and PETIM dendrimers.

All-atom molecular dynamics simulations were performed for different generations of PAMAM and PETIM dendrimers with **amine, carboxylic acid, and sugar terminal groups** and different protonation states.

## Dendrimer Systems

The repository contains simulation files for:

* **PAMAM:** G1–G5
* **PETIM:** G2–G6
* Amine-terminated dendrimers
* Carboxylic acid-terminated dendrimers
* Sugar-functionalized dendrimers
* Different protonation states
* O-core and N-core PETIM architectures

## Simulation and Analysis

The simulations were performed using **GROMACS**. The repository includes relevant molecular structures, topology files, force-field parameters, and simulation input files.

The structural and dynamical properties investigated include:

* Radius of gyration (Rg)
* Shape and asphericity
* Hydration and bound-water molecules
* RMSF and molecular flexibility
* Internal density and porosity
* Drug–dendrimer interactions and binding behavior

## Repository Organization

```text
PAMAM/
├── Amine_Termination/
├── Carboxylic_Termination/
└── Sugar_Termination/

PETIM/
├── Amine_Termination/
├── Carboxylic_Termination/
└── Sugar_Termination/
```

Each system directory contains the corresponding simulation and parameter files where applicable, such as:

```text
*.gro
*.top
*.itp
*.mdp
```

## Main Findings

The simulations show that surface functionality and protonation state have a strong influence on dendrimer structure, hydration, and flexibility. Protonated branch-point amines generally lead to increased dendrimer expansion, internal hydration, and conformational fluctuations, whereas non-protonated and carboxylate-terminated systems remain comparatively compact.

Sugar-functionalized dendrimers exhibit enhanced hydration and relatively higher structural rigidity. Differences are also observed between PAMAM and PETIM dendrimers and between the O-core and N-core PETIM architectures.

## Reproducibility

The provided GROMACS input, structure, topology, and parameter files can be used as a starting point for reproducing the molecular dynamics simulations and associated analyses.

Large trajectory and binary output files are not included in this repository where their size exceeds practical GitHub limits.

## Software

* GROMACS
* VMD
* MDAnalysis
* Python
* Xmgrace

## Citation

If you use the simulation files or data from this repository, please cite the associated publication:

> **Surface Functionality and pH Govern Structural Dynamics and Drug Binding in PETIM and PAMAM Dendrimers**

Publication details will be added after publication.

## Contact

**Anuj Garg**
Department of Physics
Sri Sathya Sai Institute of Higher Learning

For questions regarding the simulation files or analysis, please contact the corresponding author.
