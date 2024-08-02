# Prob_density_vis_XDATCAR

## Overview
This project visualizes the probability distribution of an atom in molecular dynamics (MD) simulations using XDATCAR files. It leverages the Pymatgen diffusion analysis package, which requires Python version 3.9 or higher.

## Setup
To set up the environment, we recommend using Conda to manage dependencies. Follow the steps below to create a virtual environment and install the necessary packages.

### Create and Activate the Virtual Environment
```bash
conda create -n env_for_pda1 python=3.9
conda activate env_for_pda1

### Install Required Packages
The `pymatgen` package cannot be installed directly via Conda, so we use the Conda-Forge channel instead:
```bash
conda install --channel conda-forge pymatgen
pip install pymatgen-analysis-diffusion
