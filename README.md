# Modeling and Simulation of a PEM Electrolyzer for Energy Management Control
This repository contains the MATLAB/Simulink model, simulation scripts, and documentation developed for the article:

“Modeling and Simulation of a PEM Electrolyzer for Energy Management Control”

Suárez Mendoza, Nelson Mauricio; García Guarín, Pedro Julián

University of Pamplona, ​​Colombia (2025)

The model represents the electrical, thermal, and electrochemical dynamics of a proton exchange membrane (PEM) electrolyzer designed for hydrogen production from renewable energy sources.

It was implemented in MATLAB/Simulink (R2021a) and allows for the reproduction of the results presented in the publication.
# System Requirements

MATLAB/Simulink: Version R2021a or later
Operating System: Windows 10/11 (64-bit)

# Model Overview

The dynamic model includes:

Reversible voltage: calculated using the Nernst equation

Activation surge: using the Butler-Volmer approximation

Ohmic losses: derived from membrane conductivity (Springer model)

Concentration surge: diffusion and gas transport limitations

Thermal model: based on the energy balance

The model simulates the electrolyzer's response to variations in current (0-40 A) and feedwater flow rate, allowing for the evaluation of its performance under dynamic operating conditions.

# Simulation flow:
Input: Stack current.
Initial parameters of variable subsystems.

1) Initialization: Define operating ranges and parameters.

2) Single variable current source.

3) Current density calculation.

4) Reversible potential.

5) Overpotentials.

6) Cell voltage and efficiencies.

7) Hydrogen production.

8) Thermal dynamics.

9) Recording and visualization.
