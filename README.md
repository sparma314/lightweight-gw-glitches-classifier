# Gravitational-Wave Glitch Classification Notebook

This repository contains a Jupyter notebook used for exploring and classifying glitches in gravitational-wave detector data.

## Data

The data used in this notebook is taken from the Gravity Spy dataset, available on Zenodo:

- DOI: https://doi.org/10.5281/zenodo.1476156

Please refer to the Zenodo record for detailed information about the dataset, licensing, and citation instructions.

## Notebook

The main notebook in this repository demonstrates:

- Loading and preprocessing the Gravity Spy data
- Training and evaluating machine learning models on the glitch images
- Visualizing results and learned representations

## Environment / Dependencies

The code in this repository is intended to be run in a Python environment with the dependencies listed in `environment.yml`.

To create the environment with conda:

```bash
conda env create -f environment.yml
conda activate gravityspy
