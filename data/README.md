# Data

This directory contains the molecular datasets used for fluorescence classification.

## Files

- `fluorescent.csv`  
  SMILES data for fluorescent organic molecules.

- `nonfluorescent.csv`  
  SMILES data for non-fluorescent organic molecules.

- `fluorclass_dataset.csv`  
  Final processed dataset used for model development and evaluation.  
  It contains 5,466 unique molecules (2,912 fluorescent and 2,554 non-fluorescent).

Data preprocessing, including SMILES canonicalization and duplicate removal, is provided in `code/01_Data_Preprocessing.ipynb`.
