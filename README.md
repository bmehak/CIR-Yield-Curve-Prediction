# CIR Yield Curve Prediction

## Overview

This project implements and extends the Cox-Ingersoll-Ross (CIR) short-rate model for Treasury yield curve reconstruction and prediction.

The objective is to predict Treasury yields using only the 3-Month Treasury yield as the observable short-rate proxy.

## Models Implemented

- Vanilla CIR
- Static CIR++
- Dynamic CIR++
- PCA-Enhanced CIR
- Feature-Engineered CIR + Linear Regression
- Ridge Hybrid Extension
- Polynomial Ridge Extension

## Final Selected Model

Feature-Engineered CIR + Linear Regression

Out-of-Sample R²: 0.8951

## Key Findings

- Vanilla CIR achieved strong baseline performance.
- CIR++ corrections did not improve out-of-sample generalization.
- Feature engineering significantly improved predictive accuracy.
- Ridge and Polynomial Ridge produced further gains but increased model complexity.
- The final selected model preserved the CIR structure while exceeding the required performance threshold.

## Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Scikit-Learn
- Statsmodels
- Matplotlib

## Repository Structure

```text
README.md
SIR_Modelling&Prediction.ipynb
requirements.txt
