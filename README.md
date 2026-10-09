# Insurance Claim Risk Predictor

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.36.0-FF4B4B)
![XGBoost](https://img.shields.io/badge/XGBoost-2.1.0-brightgreen)

A machine learning prototype designed to predict the likelihood of an insurance policyholder filing a claim within a specified time period (3, 6, or 12 months). 

This project was developed as part of a BSc Data Science Honours research thesis at the University of Namibia, focusing on applying advanced machine learning techniques (XGBoost) to improve predictive accuracy over traditional actuarial methods.

## Features

- **Three Prediction Horizons:** Separate XGBoost models trained for 3-month, 6-month, and 12-month claim windows.
- **Real-Time Predictions:** Interactive sidebar form that accepts policyholder details and instantly estimates claim risk.
- **Risk Visualization:** Color-coded gauge chart displaying predicted probability against the model's optimized decision threshold.
- **Feature Importance:** Dynamic charts showing the most influential factors driving the predictions for each horizon.
- **Model Performance Dashboard:** Expandable panel showing test-set metrics (Accuracy, Precision, Recall, F1, AUC-ROC, AUC-PR, Brier).

## Technology Stack

- **Frontend:** Streamlit, Plotly
- **Machine Learning:** XGBoost, Scikit-learn
- **Data Processing:** Pandas, NumPy
- **Model Persistence:** Joblib

