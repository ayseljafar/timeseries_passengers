# Time Series Analysis of Air Passengers Data

This project analyzes seasonal aviation passenger trends using Time Series Analysis techniques, specifically ARIMA and SARIMA models implemented with statsmodels.

## Overview

The analysis focuses on the monthly number of air passengers between 1949 and 1960. The project demonstrates various time series analysis techniques including:
- Seasonal decomposition
- ARIMA and SARIMA modeling
- Time series forecasting
- Trend analysis
- Seasonal pattern identification

## Data

The dataset (`AirPassengers.csv`) contains monthly air passenger counts from 1949 to 1960. The data shows clear seasonal patterns and an overall increasing trend in air travel during this period.

## Analysis Components

1. **Data Preprocessing**
   - Log transformation
   - Differencing (simple and seasonal)
   - Stationarity checks

2. **Time Series Decomposition**
   - Trend component
   - Seasonal component
   - Residual component

3. **Modeling**
   - ARIMA model implementation
   - SARIMA model implementation
   - Model diagnostics
   - Forecasting

## Results

The analysis reveals:
- Strong seasonal patterns in air passenger numbers
- Overall increasing trend in air travel
- Accurate forecasting capabilities of the SARIMA model

## Visualizations

![Seasonal decomposition](https://github.com/ayseljafar/timeseries_passengers/blob/main/images/seasonal%20decomp.png)
![PREDICTIONS](https://github.com/ayseljafar/timeseries_passengers/blob/main/images/prediction.png)

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- statsmodels

## Getting Started

1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebook `airpassengers (1).ipynb`

## Author

Aysel Jafarova
