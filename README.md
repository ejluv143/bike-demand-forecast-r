# 🚲 Bike Rental Demand Forecasting (Time Series Analysis in R)

## 📌 Project Overview
This project analyzes and forecasts hourly and daily bike rental demand using real-world data from the Capital Bikeshare system in Washington, D.C.

The goal is to understand demand patterns and build a time series forecasting model that can help optimize bike availability, pricing strategies, and operational planning.

---

## 📊 Dataset Description
The dataset contains two years of bike rental records (2011–2012), including:

- Hourly and daily bike rental counts  
- Weather conditions (temperature, humidity, windspeed)  
- Seasonal and temporal variables (hour, weekday, month, season)

Source: UCI Machine Learning Repository

---

## 🧠 Objectives
- Perform exploratory data analysis (EDA)
- Understand demand patterns over time
- Check stationarity of the time series
- Decompose time series into trend, seasonality, and noise
- Build forecasting models using ARIMA
- Generate future demand predictions

---

## 🛠️ Tools & Libraries
- R  
- tidyverse  
- ggplot2  
- lubridate  
- forecast  
- tseries  
- zoo  

---

## 📈 Methods Used

### 1. Data Exploration
- Summary statistics
- Missing value check
- Data structure analysis

### 2. Time Series Analysis
- Aggregation of hourly data into daily demand
- Visualization of rental trends over time

### 3. Smoothing
- 7-day moving average to reduce noise and highlight trends

### 4. Decomposition
- Trend component
- Seasonal component
- Random noise (residuals)

### 5. Stationarity Testing
- Augmented Dickey-Fuller (ADF) test
- Differencing applied when needed

### 6. Forecasting
- ARIMA model using auto.arima()
- Forecasting future demand (30 days)

---

## 🔍 Key Insights
- Bike demand shows strong temporal and seasonal variation.
- Clear weekly and seasonal patterns exist in usage behavior.
- Weather conditions significantly influence rental demand.
- The raw time series is non-stationary but becomes more stable after differencing.
- ARIMA provides reliable short-term forecasting performance.

---

## 📊 Business Impact
- Improves bike distribution across stations
- Helps reduce shortages during peak demand
- Supports dynamic pricing strategies
- Enhances operational efficiency

---

## 🚀 Future Improvements
- Add weather forecasting integration
- Compare ARIMA with machine learning models (Random Forest, XGBoost)
- Build an interactive dashboard using Shiny
- Explore Prophet forecasting model for comparison

---

## 👤 Author
EJ Loudale Canete 
Coursera Data Science Project  
