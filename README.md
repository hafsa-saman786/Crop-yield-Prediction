 Crop Yield Prediction using Machine Learning

Author: Hafsa Saman   
Institution:University of Agriculture Faisalabad
Email :hafsasaman25@gmail.com

 Overview

This project uses machine learning (Linear Regression, Random Forest, XGBoost) to predict crop yield based on environmental factors. SHAP analysis is used for model interpretability.



Dataset

- Source: Agriculture Crop Yield Dataset (Kaggle)
- Sample:50,000 records
- Features: Rainfall_mm, Temperature_Celsius, Days_to_Harvest
- Target: Yield_tons_per_hectare



Results

| Model | MAE | RMSE | R² |
|-------|-----|------|-----|
| Linear Regression | 0.8829 | 1.0838 | 0.5928 |
| Random Forest | 0.9345 | 1.1451 | 0.5454 |
| XGBoost | 0.8876 | 1.0891 | 0.5887 |

Best Model: Linear Regression (R² = 0.5928)

 Feature Importance

| Feature | Importance |
|---------|------------|
| Rainfall_mm | 73.6% |
| Temperature_Celsius | 15.8% |
| Days_to_Harvest | 10.6% |

Key Finding: Rainfall is the most important predictor of crop yield.



 Repository Contents

- crop-yield-prediction.ipynb — Complete Jupyter Notebook
- shap_summary_plot.png — SHAP summary plot
- feature_importance.png — Feature importance plot
- predicted_vs_actual.png— Model accuracy plot
- shap_importance.csv — SHAP importance table


 How to Run

1. Open the notebook in Google Colab
2. Upload your CSV file
3. Run all cells



 Requirements
 Python 3.9+
Google Colab or Jupyter Notebook
Libraries: pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn


 Code Availability

Full source code is available at:  
[https://github.com/hafsa-saman786/Crop-yield-Prediction](https://github.com/hafsa-saman786/Crop-yield-Prediction

**Hafsa Saman** — [Your Email]  
**Saeed Rasheed (Supervisor)** — saeed.rasheed0211@gmail.com
