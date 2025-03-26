# source

link: https://github.com/

# Molecule Solubility Prediction

A machine learning project to predict the solubility (logS) of molecules using descriptors.

## Project Overview

This project implements and compares two machine learning models:
- Linear Regression
- Random Forest Regression

to predict molecule solubility based on molecular descriptors.

## Dataset

The project uses the Delaney solubility dataset, which contains:
- Molecular descriptors (features)
- LogS values (target variable)

Data source: https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney_solubility_with_descriptors.csv

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- numpy

## Project Structure

- `first_project.ipynb`: Jupyter notebook containing the complete analysis
- Data preparation
- Model training and evaluation
- Results visualization

## Results

The project compares two models:
1. Linear Regression
2. Random Forest (max_depth=2)

Performance metrics include:
- Mean Squared Error (MSE)
- R-squared (R²)
for both training and test sets.

## Usage

1. Clone the repository
2. Install required packages
3. Run the Jupyter notebook `first_project.ipynb`

## License

This project is open source and available under the MIT License.
