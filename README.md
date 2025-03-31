# Arkema
This repository is to track the code and results of Reactivity Rate Constants

## Version History

| Version  | Description                          | Features |
|----------|--------------------------------------|----------|
| **[Ver1](https://github.com/aakankshch/Arkema/blob/main/CISC848Ver1.ipynb)**  | Base Model                          | MACCS Fingerprints,MTE|
| **[Ver1.1](https://github.com/aakankshch/Arkema/blob/main/CISC848Ver1_1.ipynb)** | Hydrogen Abstraction Rxn Type | MACCS Fingerprints, MTE|
| **[Ver1.2](https://github.com/aakankshch/Arkema/blob/main/CISC848Ver1_2.ipynb)**|Hydrogen Abstraction Rxn Type |Descriptors & PCA|

## Version 1 - Model Performance

| Model             | MAE    | RMSE   | R² Score |
|------------------|--------|--------|----------|
| Linear Regression | 1.105  | 1.665  | 0.419    |
| Lasso Regression | 1.237  | 1.813  | 0.312    |
| Ridge Regression | 0.994  | 1.642  | 0.435    |
| Random Forest    | 0.846  | 1.411  | 0.583    |
| XGBoost         | 0.867  | 1.497  | 0.530    |

## Version 1.1 - Model Performance

| Model             | MAE    | RMSE   | R² Score |
|------------------|--------|--------|----------|
| Linear Regression | 0.718  | 0.984  | 0.731    |
| Lasso Regression | 1.209  | 1.534  | 0.346    |
| Ridge Regression | 0.707  | 0.980  | 0.733    |
| Random Forest    | 0.833  | 1.059  | 0.689    |
| XGBoost         | 0.803  | 1.120  | 0.652    |





