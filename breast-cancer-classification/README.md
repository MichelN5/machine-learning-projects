# Breast Cancer Classification

This project was developed as part of an Introduction to Artificial Intelligence course during my Computer Science studies at the University of Balamand.

It uses the Wisconsin Diagnostic Breast Cancer dataset from the UCI Machine Learning Repository to classify tumors as benign or malignant using classical machine-learning techniques.

## Workflow

- Load and clean the dataset
- Explore feature distributions and correlations
- Split data into training and test sets
- Standardize features where appropriate
- Train and compare Decision Tree, Support Vector Machine, and Random Forest classifiers
- Tune Random Forest and SVM with `GridSearchCV`
- Apply PCA for dimensionality reduction and compare reduced-feature models
- Evaluate with accuracy, precision, recall, F1-score, confusion matrices, and ROC/AUC
- Inspect Random Forest feature importance

## Result

In the original coursework run, the tuned Random Forest achieved about 97% test accuracy and 93% recall for malignant cases.

## Tech

- Python
- scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- UCI ML Repository (`ucimlrepo`)

## Note

This is an academic machine-learning project and is not intended for clinical use.
