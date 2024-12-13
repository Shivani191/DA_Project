# Federal Budget Trends Analysis

## Overview
This project analyzes historical U.S. federal budget allocations from 2010 to 2022 and applies various time series forecasting techniques to predict future spending patterns. The goal is to provide insights into budget trends across key government departments.

## Features
- **Data Preprocessing**: Handling missing values, filtering data, and consistency checks.
- **Exploratory Analysis**: Summary statistics, trend visualization, and correlation analysis.
- **Forecasting Models**:
  - Linear Regression
  - Naïve Baseline Model
  - Exponential Smoothing
  - ARIMA
- **Evaluation Metrics**: Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess model performance.

## Dataset
The dataset is sourced from Kaggle:
- [USA Budget Authority by Agency 1976–2022]([https://www.kaggle.com/datasets/mfaaris/usa-budget-authority-by-agency-19762022])

## Results
- Exponential Smoothing and ARIMA provided the most accurate forecasts.
- Visualizations demonstrate stable trends in certain departments and volatility in others.
- Model performance metrics (MSE and MAE) are included for comparative analysis.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn
- Jupyter Notebook / Google Colab

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository.git
Usage
Open the Jupyter Notebook or Colab file.
Run the preprocessing steps to clean the data.
Execute the forecasting models and analyze their performance.
Visualize the results for key departments.
Authors
Thirumala Devi Kola: Data preparation, linear regression forecasting.
Shivani Jilukara: Visualization, ARIMA model analysis, report writing.
