# epilepsy-diagnosis-classifier
ML models to predict epilepsy type from clinical and seizure-related features.

## Overview
Built and compared 7 classification algorithms on a dataset of 4,856 patients 
across 6 epilepsy types (Absence, Normal, Complicated, Focal, Generalized, Unknown).
Best model: Gradient Boosting — 82.4% accuracy, weighted F1 of 0.823.

## Approach
- Preprocessed 30 clinical features (one-hot encoding, standardization)
- Visualized class distributions, UMAP clusters, and feature correlations
- Trained and compared: Gradient Boosting, CatBoost, XGBoost, Logistic Regression, 
  Random Forest, SVM, k-NN
- Tuned top models; performed feature selection — top 15 features captured 98.3% 
  of predictive signal

## Key finding
A compact set of clinically meaningful features (led by seizure type) is sufficient 
for accurate classification — useful for fast, interpretable diagnostic support.

## Tech stack
Python, Scikit-learn, XGBoost, CatBoost, Pandas, UMAP

## Files
- `Final_Project_Code.ipynb` — full modeling pipeline
- `Final_Project_Report.pdf` — write-up with findings
