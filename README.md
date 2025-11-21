# CHE1147 Final Project – Predicting LogS

## Overview
This repository contains the code for my CHE1147 final project.
The goal is to predict the solubility (LogS) of compounds using experimental conditions
and molecular descriptors.

All preprocessing, model training, and figure generation are implemented in
`notebooks/Final_Project.ipynb`.

## Repository Structure
- `data/` – dataset file(s) or a link to the dataset.
- `notebooks/` – Jupyter notebook with all analysis steps.
- `results/` – generated figures and evaluation results.
- `environment.yml` – file to replicate the Python environment.

## How to Run
1. Create the environment (for local runs, optional if you only use Colab):

       conda env create -f environment.yml
       conda activate che1147-final-project

2. Open Jupyter:

       jupyter notebook

3. Open `notebooks/Final_Project.ipynb` and run all cells.

This project was developed and tested in Google Colab.  
The required packages are listed in `environment.yml`.
