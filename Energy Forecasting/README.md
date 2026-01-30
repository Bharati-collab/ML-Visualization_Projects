# Electricity Demand Forecasting (Time Series)

## Overview: 

This project demonstrates a practical time-series forecasting approach to predict electricity demand using historical load data. A Naive baseline is benchmarked against an XGBoost regression model to validate real performance improvement.

The project highlights strong forecasting fundamentals, feature engineering, and model evaluation practices.

## Business Context: 

Accurately forecast future electricity demand to support operational planning and decision-making.
This is modeled as a supervised regression time-series problem with AEP_MW as the target.

## Approach: 

Converted datetime to index and preserved temporal order
Engineered time-based features (hour, day, month, seasonality)
Created lag features to capture short-term dependency
Used a time-based train/test split (no random shuffling)

## Tools:
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib

## ML-Models:

Naive Baseline: Last observed value (t-1)
XGBoost Regressor: Tree-based model using time & lag features

Results (Test Set)
Model	          RMSE

Naive Baseline	3970.76
XGBoost	        1644.39

## 59% RMSE reduction over baseline, confirming strong predictive lift.

## Prediction Preview
[!](Energy_forecast.png)


## Insight Generated: 

Electricity demand shows strong daily and seasonal patterns
Lag features significantly improve forecast accuracy
Benchmarking against baselines is essential for valid forecasting
XGBoost performs well on engineered time-series features

## Limitations & Next Steps: 

Weather and holiday effects not included
Seasonal naive baseline can be added
Future work: Prophet/SARIMAX comparison and Streamlit deployment





















