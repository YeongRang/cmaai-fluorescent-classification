# Model Interpretation Results

This directory contains the outputs generated from the Integrated Gradients (IG)-based interpretation of the fluorescence classification model.

Generated from:

`code/04_Fluorescent_Model_Interpretation.ipynb`

## Data Files

- `mol_table.csv`  
  Molecule-level metadata and prediction results.

- `ig_matrix_raw.npz`  
  Raw IG attribution matrix for all molecules and 2,048 ECFP bits.

- `ig_long_table.csv.gz`  
  Long-format IG attribution data containing only active ECFP bits.

- `top_features_IG_*.csv`  
  Ranked ECFP bits based on IG attribution values.

## Figures

- `ConfusionMatrix.png`  
  Confusion matrix of the selected classification model.

- `Loss.png`  
  Training and validation loss curves.

- `IG_attribution_color_F.png`  
  Molecular-level IG attribution visualization for a fluorescent molecule.

- `IG_attribution_color_N.png`  
  Molecular-level IG attribution visualization for a non-fluorescent molecule.

- `IG_substructure_F.png`  
  ECFP substructures associated with IG attribution for a fluorescent molecule.

- `IG_substructure_N.png`  
  ECFP substructures associated with IG attribution for a non-fluorescent molecule.

- `Global_meanIG_bar_point.png`  
  Mean IG attribution values across all ECFP bits.
