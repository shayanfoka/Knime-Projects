# QSPR Modeling Project - Winter Semester 2024-25

## Overview

This project is focused on predicting the **pLC50** values of chemical compounds using molecular descriptors.
The goal was to preprocess the data, handle outliers, perform feature selection, and develop a machine learning model that predicts compound toxicity. 
The **XGBoost** algorithm was chosen as the best-performing model, achieving an R² value of **0.92** on the test data.
The project provides a complete **KNIME** workflow, Python scripts for feature transformation, and example datasets to facilitate reproducibility and scalability for future work.

## Project Objectives

- Preprocess and clean molecular descriptor data for pLC50 prediction.
- Handle outliers and normalize data to improve model performance.
- Develop and validate a machine learning model using **XGBoost**.
- Create a modular workflow that is easily adaptable for future datasets.

## Requirements

To replicate and run this project, the following software and libraries are required:

- **KNIME Analytics Platform** (version 4.0 or higher)
- **Python 3.x** (required for feature transformation scripts)
- **RDKit** (installed within KNIME)
- **Python Libraries**:
  - `pandas`
  - `numpy`
  - `scipy`
  - `scikit-learn`
  - `xgboost`
  - `matplotlib`

### KNIME Extensions Needed:
- **KNIME Python Integration**
- **KNIME RDKit Nodes**

