# CMAAI-fluorescent-classification
2026 CMA AI Lab Research: fluorescent classification and interpretation of organic colorants

This repository contains the data, code, and analysis results for a machine learning-based classification study of fluorescent and non-fluorescent organic colorants using molecular structure information.

The molecular structures were represented using Extended-Connectivity Fingerprints (ECFP), and a multilayer perceptron (MLP) was used for fluorescence classification. Integrated Gradients (IG) was applied to interpret the molecular features utilized by the model during prediction.

## Graphical Abstract

<p align="center">
  <img src="GraphicalAbstract.png" width="850">
</p>

## Repository Structure

```text
.
├── code/
│   ├── 01_Data_Preprocessing.ipynb
│   ├── 02_Descriptor_Analysis.ipynb
│   ├── 03_Fluorescent_Classification_Model.ipynb
│   ├── 04_Fluorescent_Model_Interpretation.ipynb
│   └── 05_Draw_Graph_GlobalIG.ipynb
│
├── data/
│   ├── fluorescent.csv
│   ├── nonfluorescent.csv
│   └── fluorclass_dataset.csv
│
├── result/
│   ├── 02_Analysis/
│   ├── 03_Classification/
│   ├── 04_Interpretation/
│   └── 05_DrawGraph/
│
└── README.md
