# Thermodynamic-Modelling
This repository consolidates a structured collection of MATLAB Live Scripts, Thermo-Calc project files, and supporting datasets used for computational thermodynamics and phase-diagram analysis. The content is designed to support rigorous study, reproducible modelling, and future extension into more advanced materials design workflows.
This project explores the core components of computational thermodynamics using a combination of:

MATLAB (for numerical modelling, custom scripts, and visualisation)

Thermo-Calc (for CALPHAD-based thermodynamic and kinetic calculations)

The repository includes scripts and model files covering:

Unary, binary, and ternary phase diagrams

Heat capacity and thermodynamic property calculations

Iron–carbon system modelling

Magnetic transition temperature evaluation

Chemical potentials and phase compositions

These files collectively form a modular foundation for studying thermodynamic behaviour of engineering materials, with potential extensions toward alloy design, process simulations, and machine-learning-based property prediction.
##Repository Structure
Thermodynamic-Modelling/
│
├── Unary Phase Diagram/  
├── Heat Capacity/  
├── Iron-Carbon Phase Diagram/  
├── Thermodynamic Properties/  
├── Magnetic Transition Temperature/  
│
├── Phase Diagram/                 # Previous work (MATLAB Live Script)
├── Phase Composition/             # Last month’s scripts
├── Chemical Potential/            # Last month’s scripts
│
└── README.md


Each folder contains either:

MATLAB .mlx files (annotated, interactive computational notebooks), or

Thermo-Calc .tcs, .tcproj, or database files for CALPHAD simulations.
##Requirements
MATLAB R2023a or later

Thermo-Calc (minimum version depending on included project files)

Standard CALPHAD databases (TCFE, TCTI, etc., based on your usage)
