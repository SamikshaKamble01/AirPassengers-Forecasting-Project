# ✈️ AirPassengers Forecasting Project
   
## 📖 Introduction

Forecasting future demand is one of the most important applications of Time Series Analysis. This project analyzes historical airline passenger data from 1949 to 1960 and uses statistical forecasting techniques to predict future passenger traffic.

The project demonstrates trend analysis, seasonal pattern detection, moving averages, ARIMA forecasting, and model evaluation using real-world time-series data.

---
## 🎯 Project Goals

* Analyze historical passenger traffic.
* Identify long-term trends.
* Detect recurring seasonal patterns.
* Smooth fluctuations using moving averages.
* Forecast future passenger demand.
* Evaluate forecasting performance using RMSE.

---

## 📊 Dataset Overview

**Dataset:** AirPassengers Dataset

**Time Period:** January 1949 – December 1960

**Frequency:** Monthly

### Features

| Column     | Description                  |
| ---------- | ---------------------------- |
| Month      | Observation Date             |
| Passengers | Number of Airline Passengers |

## 🔬 Methodology

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Converted Month column into datetime format
* Set Month as index

### 2. Exploratory Analysis

* Trend Visualization
* Time-Series Plot
* Passenger Growth Analysis

### 3. Seasonal Analysis

* Seasonal Decomposition
* Trend Component
* Seasonal Component
* Residual Component

### 4. Moving Average Analysis

* 6-Month Moving Average
* 12-Month Moving Average

### 5. Forecasting Model

* Train-Test Split
* ARIMA Model Training
* Future Forecast Generation

### 6. Model Evaluation

* RMSE Calculation
* Actual vs Forecast Comparison

## 📈 Results
<img width="1920" height="1080" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/774dac62-e7d7-485b-bacf-a26fae54616c" />
<img width="1920" height="1080" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/68d88252-989b-4a0e-b434-48bee7517a11" />
<img width="1920" height="1080" alt="Screenshot (137)" src="https://github.com/user-attachments/assets/71dde466-1798-434d-94b1-a12d3b550258" />
### Trend Analysis

A significant upward trend was observed in passenger traffic throughout the dataset.

### Seasonality Analysis

Passenger counts followed a repeating yearly seasonal pattern.

### Forecasting

The ARIMA model successfully captured historical trends and generated reliable future forecasts.

### Performance

Model accuracy was evaluated using Root Mean Squared Error (RMSE).

## 💡 Business Insights

* Passenger demand consistently increased over time.
* Peak travel months recorded significantly higher traffic.
* Seasonal demand should be considered when planning airline operations.
* Forecasting can help optimize capacity and resource allocation.

## 🚀 Future Scope

* Implement SARIMA forecasting.
* Compare ARIMA with Facebook Prophet.
* Build an interactive dashboard.
* Deploy forecasting model as a web application.

## 📂 Project Structure

```text
AirPassengers-Forecasting-Project/
│
├── AirPassengers_Forecasting.ipynb
├── AirPassengers.csv
├── README.md


## 🛠️ Requirements

```text
pandas
numpy
matplotlib
statsmodels
scikit-learn


## 👩‍💻 Author

**Samiksha Kamble**


