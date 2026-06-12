# Formative 2 — Principal Component Analysis (PCA)
## Group 42 | African Leadership University

### Dataset
COVID-19 in African Countries
Source: Kaggle — 54 African countries, 10 columns
Contains missing values and one non-numeric column (Country)

### What this notebook does
Implements PCA from scratch using NumPy only.
- Loads and cleans the dataset (missing value imputation, encoding)
- Standardizes features using z-score normalization
- Computes covariance matrix and performs eigendecomposition
- Dynamically selects principal components based on explained variance
- Visualizes data before and after dimensionality reduction
- Benchmarks performance across different dataset sizes

### Libraries used
- NumPy (computation)
- Matplotlib (visualization)

### Files
- Template_PCA_Formative_2_Group_42.ipynb — main notebook
- covid_africa.csv — dataset
- contribution_sheet.pdf — For our contribution tracker

### How to run
1. Upload both files to Google Colab
2. Run all cells top to bottom (Runtime → Run all)