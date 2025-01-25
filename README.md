# Time Series Forecasting of Carbon Monoxide and Nitrogen Dioxide Levels

## Overview

This project aims to forecast the levels of Carbon Monoxide (CO) and Nitrogen Dioxide (NO₂) using time series data. The workflow includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation of forecasting models. The final models help predict future levels of these pollutants to support environmental monitoring efforts.

---

## Steps Undertaken

### 1. Data Preprocessing
- Loaded and cleaned the dataset.
- Addressed missing values through interpolation techniques.
- Normalized and scaled features for model readiness.
- [View Notebook](notebooks/https://github.com/anikaanawer/DataAnalysis_ML_Project3/blob/main/Sentiment_Analysis_on_Amazon_Product_Reviews.ipynb)

---

### 2. Exploratory Data Analysis (EDA)
- Visualized trends, seasonality, and anomalies in the dataset.
- Examined correlations between pollutants and external factors.
- Generated summary statistics for each pollutant.
- [View Notebook](https://github.com/anikaanawer/DataAnalysis_ML_Project3/blob/main/Sentiment_Analysis_on_Amazon_Product_Reviews.ipynb)

---

### 3. Model Building
- Built forecasting models using:
  - Autoregressive Integrated Moving Average (ARIMA)
  - Long Short-Term Memory (LSTM) networks
  - Prophet for time series decomposition
- Split data into training and testing sets for validation.
- [View Notebook](notebooks/https://github.com/anikaanawer/DataAnalysis_ML_Project3/blob/main/Sentiment_Analysis_on_Amazon_Product_Reviews.ipynb)

---

### 4. Model Evaluation
- Evaluated models using metrics:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Plotted forecasts against actual values for comparison.
- [View Notebook](notebooks/https://github.com/anikaanawer/DataAnalysis_ML_Project3/blob/main/Sentiment_Analysis_on_Amazon_Product_Reviews.ipynb)

---

### 5. Results and Insights
- Insights:
  - Seasonal trends in NO₂ levels were observed during winter months.
  - CO levels showed consistent growth during peak traffic hours.

---

## Installation

### Requirements
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, scikit-learn, statsmodels, tensorflow, prophet

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/anikanawer/Time_Series_Forecasting.git
