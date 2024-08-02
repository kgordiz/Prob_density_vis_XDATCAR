# Probability Density Visualization Based on XDATCAR

## Overview
This project visualizes the probability distribution of an atom in molecular dynamics (MD) simulations using XDATCAR files. It leverages the Pymatgen diffusion analysis package, which requires Python version 3.9 or higher.

## Setup
To set up the environment, we recommend using Conda to manage dependencies. Follow the steps below to create a virtual environment and install the necessary packages.

### Create and Activate the Virtual Environment
```bash
conda create -n env_for_pda1 python=3.9
conda activate env_for_pda1
```

### Install Required Packages
The `pymatgen` package cannot be installed directly via Conda, so we use the Conda-Forge channel instead:
```bash
conda install --channel conda-forge pymatgen
pip install pymatgen-analysis-diffusion
```

### Jupyter Notebook Integration
To connect the environment to Jupyter Notebook, use the following commands:
> ```bash
> pip install ipykernel
> python -m ipykernel install --user --name=env_for_pda1
> ```
> **Note:** If Jupyter Notebook is not already installed, you can install it with:
> ```bash
> pip install notebook
> ```

### Usage
Run the Jupyter Notebook provided alongside the `example` folder to generate the probability distribution in a related CHGCAR file, and then visualize the CHGCAR file in VESTA.
