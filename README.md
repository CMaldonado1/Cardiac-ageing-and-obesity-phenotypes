# Cardiac-ageing

This repository contains the code associated with the paper:
**"Compartment-specific Fat Distribution Profiles have Distinct Relationships with Cardiovascular Ageing and Future Cardiovascular Events"**, currently under review in Nature Communications.

### 📂 Environment Setup

We recommend using the provided environment.yml file to reproduce the computational environment.
To create and activate the environment:

conda env create -f environment.yml
conda activate cardiac-ageing

### 📂 Repository Overview

## 🔬 Machine Learning Models
- ML_methods.ipynb
  Contains the code for model selection experiments, including:
  - Grid search for optimal model selection.
  - Hyperparameter tuning procedure and final selected hyperparameters.
  - Results for both female and male cohorts.

- xgboost.ipynb
  Implements the best-performing model (XGBoost), along with:
  - Training and evaluation workflow.
  - Performance metrics and model interpretability analyses.
  - Separate analyses for female and male participants.

## 🧪 Experimental Analyses

- K-means Clustering (clusters_analysis.ipynb)
  - Implementation of unsupervised clustering for both sexes.
  - Visualization of cluster characteristics and distributions.
- Association by Sex (Associations_by_sex.ipynb)
  - Sex-stratified statistical analyses.
  - Group comparisons and effect size calculations.
- Mediation Analysis (mediation_analysis.ipynb)
  - Code to perform mediation analysis.
  - Sensitivity analysis and tuning procedures.

## 📊 Reproducibility

- All notebooks are designed to be executed sequentially.
- Figures and results in the manuscript can be reproduced by running the notebooks in the order described above.
- Please ensure all dependencies are installed before running any notebook.

## 📜 Citation

If you use this code or data in your own work, please cite our paper once published:
