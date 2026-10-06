# AirGuard India

## Indian Air Quality Forecasting and Pollution Risk Prediction

AirGuard India is a machine learning project designed to forecast PM2.5 air pollution levels using historical Indian air-quality time-series data.

The project aims to build an end-to-end machine learning pipeline covering data collection, data validation, preprocessing, exploratory data analysis, feature engineering, model development, time-aware evaluation, error analysis, and API deployment.

## Problem Statement

Air pollution varies significantly across time, cities, seasons, and weather-related conditions. Accurate short-term PM2.5 forecasting can help identify upcoming pollution levels and support data-driven pollution monitoring.

The primary objective of AirGuard India is to predict the PM2.5 concentration for the next hour using historical air-quality observations and temporal patterns.

## Objectives

- Collect and prepare historical Indian air-quality data.
- Analyze PM2.5 patterns across cities and time.
- Perform data cleaning and validation.
- Engineer time-series and lag-based features.
- Establish a persistence baseline.
- Train and compare machine learning models.
- Evaluate models using time-aware validation.
- Perform error analysis.
- Convert predictions into pollution-risk categories.
- Develop a FastAPI prediction service.
- Prepare the project for deployment.

## Planned Machine Learning Pipeline

CPCB Air-Quality Data
        ↓
Data Validation
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Baseline Model
        ↓
Machine Learning Models
        ↓
Time-Aware Evaluation
        ↓
Error Analysis
        ↓
Model Optimization
        ↓
Final Model
        ↓
FastAPI
        ↓
Deployment

## Initial Models

1. Persistence / Naive Baseline
2. Linear Regression
3. Random Forest
4. Gradient Boosting / XGBoost
5. LSTM/GRU if justified by experimental results

## Evaluation Metrics

### Regression
- MAE
- RMSE
- R²

### Pollution Risk Classification
- Precision
- Recall
- F1-score
- Confusion Matrix

## Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- FastAPI
- Joblib
- Pytest
- Git/GitHub
- Docker

## Project Structure

```text
Airguard/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── models/
├── reports/
├── tests/
├── api/
├── .gitignore
├── .env.example
├── README.md
└── requirements.txt