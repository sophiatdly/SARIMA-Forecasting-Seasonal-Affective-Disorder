# Seasonal Affective Disorder Forecasting with SARIMA

## Project Overview

This repository contains a collection of SARIMA models that analyze and forecast search trends related to mental health topics using Google Trends data. The project culminates in a comprehensive Aggregated Final Model that integrates predictions from five key search terms: depression symptoms, antidepressants, therapy, burnout, and mental health support.

This project aims to provide insights into mental health trends by analyzing search queries over time. The repository includes:

- Individual Models: SARIMA models for each search term, focusing on specific aspects of mental health.
- Aggregated Final Model: A holistic approach that combines and weights trends from five key terms for a unified forecast.

These models help identify patterns, predict future trends, and visualize the seasonal and temporal dynamics of mental health-related search behaviors.

## Data

Five key search terms (depression symptoms, antidepressants, therapy, burnout, and mental health support) were collected from Google Trends and a weighted average was applied to these search terms to create a single, aggregated time series. This approach allows for a more comprehensive understanding of overall mental health trends.

## Methodology

#### 1. Data Preprocessing:
  - Data Cleaning: Handled missing values and outliers.
  - Stationary Testing: Ensured data stationarity using the Augmented Dickey-Fuller (ADF) test.
    
#### 2. Model Selection:
  - Automated Parameter Selection: Utilized the auto_arima function to identify optimal SARIMA parameters.
    
#### 3. Model Training and Forecasting:
  - SARIMA Model Fitting: Trained SARIMA models on both individual and aggregated time series.
  - Forecast Generation: Generated 12-month forecasts with confidence intervals.
    
#### 4. Model Evaluation:
  - Mean Absolute Error (MAE): Calculated MAE to assess the accuracy of forecasts.
    
#### 5. Visualization:
  - Time Series Plots: Visualized observed, forecasted, and actual data (when available).

## Results

Mean Absolute Error (MAE) results for each individual search term and aggregated search terms models:

- Antidepressants: 3.8322110689044235
- Burnout: 5.809752546351387
- Depression Symptoms: 5.627506881314137
- Mental Health Support: 10.712936491415801
- Therapy: 4.689034142339209
- Aggregated Model: 1.9752425388052426


