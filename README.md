# AQI-Prediction-ML-DL
Air Quality Prediction using Machine Learning (XGBoost, Random Forest) and Deep Learning (LSTM) with SHAP-based Explainable AI on the UCI Air Quality Dataset.

## Overview

This project investigates Air Quality Index (AQI) prediction using Machine Learning and Deep Learning techniques on the UCI Air Quality Dataset.

The following models were implemented and compared:

- XGBoost
- Random Forest
- Long Short-Term Memory (LSTM)

Explainable Artificial Intelligence (XAI) was incorporated using SHAP to improve model interpretability.

## Dataset

- Source: UCI Machine Learning Repository
- Target Variable: CO(GT)


## Methodology

### Data Preprocessing
- Missing value handling
- Feature engineering
- Lag feature generation
- Rolling statistics
- Feature scaling

### Models
1. XGBoost
2. Random Forest
3. LSTM

### Evaluation Metrics
- RMSE
- MAE
- R² Score

## Results

| Model | RMSE | MAE | R² |
|---------|---------|---------|---------|
| XGBoost | 0.463 | 0.307 | 0.888 |
| Random Forest | 0.497 | 0.334 | 0.871 |
| LSTM | 0.586 | 0.393 | 0.821 |

XGBoost achieved the best overall performance.


## Explainability

SHAP analysis identified lag-based features and pollutant measurements as the most influential predictors.


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- TensorFlow/Keras
- SHAP
- Matplotlib

## Author

Sandeep Patel
MSc Data Science
