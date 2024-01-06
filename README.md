# IOMT Threat Analysis

## Overview
This repository contains a Jupyter Notebook (`IOMTthreatAnalysis.ipynb`) that focuses on implementing an Intrusion Detection System (IDS) for the Internet of Medical Things (IOMT) using an Artificial Intelligence (AI) approach.

## Notebook Sections

### 1. Data Acquisition and Preliminary Analysis
- The notebook starts with loading the dataset from Google Drive and performing an initial analysis.
- Data cleaning steps are applied to handle missing values and irregularities in column names.
  
### 2. Exploratory Data Analysis (EDA)
- Unique values and counts in the 'Label' column are displayed, followed by a visualization of the label distribution.
- A correlation matrix is computed, identifying highly correlated column pairs.
- The correlation matrix is visualized using a heatmap.

### 3. Data Preprocessing for Machine Learning
- Label encoding is performed for the 'Label' column.
- Numerical and object columns are identified for further processing.
- Robust scaling is applied to handle outliers.

### 4. Machine Learning Analysis
- The dataset is split into training and testing sets.
- Two machine learning models (XGBoost and Random Forest) are trained and evaluated.
- Confusion matrices and classification reports are generated for model evaluation.

### 5. Hyperparameter Tuning
- Grid search is performed to find optimal hyperparameters for XGBoost and Random Forest models.
- The best models with tuned hyperparameters are trained and evaluated.

## Machine Learning Results
1. **XGBoost Model**
   - Accuracy: 97.71%

2. **Random Forest Model**
   - Accuracy: 97.64%

## Usage
1. Load the notebook in a Jupyter environment.
2. Follow the sections sequentially for data analysis, preprocessing, and model building.
3. Adjust hyperparameters if needed for better model performance.

Feel free to contribute or raise issues for improvements!

*Note: This summary provides an overview. Refer to the notebook for detailed code and analysis.*
