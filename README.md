# PINN for Conducting Casson Nanofluid Flow

## Overview

This repository contains the computational implementation of a Physics-Informed Neural Network (PINN) for studying conducting Casson nanofluid flow with thermal stratification and coupled momentum, heat, and mass transfer.

## Methodology

The implementation uses governing differential equations, boundary conditions, a composite loss function, and neural-network optimization using Adam and L-BFGS. Residual-based diagnostics and numerical validation are used to assess the computed solutions for the investigated parameter configurations.

## Requirements

Python 3.x and the libraries specified in `requirements.txt` are required. Please use the tested library versions and the installation instructions provided with the code.

## Execution

1. Clone or download this repository.
2. Install the required Python dependencies.
3. Open the Jupyter Notebook.
4. Run the cells in sequence.
5. Review the computed profiles, residual metrics, and validation results.

## Reproducibility

The code and numerical results are provided to support verification of the computational methodology described in the associated manuscript. Results may depend on the software environment, training configuration, and numerical settings.

## Associated Manuscript

Predictive Modelling of Conducting Casson Nanofluid Flow Using a Physics-Informed Neural Network: Effects of Thermal Stratification and Coupled Transport Mechanisms.
