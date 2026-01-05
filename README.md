# Sales Forecasting with ARIMA & LSTM
## Project Overview

This project focuses on time series sales forecasting using both statistical and deep learning approaches.
The analysis begins with Exploratory Data Analysis (EDA) and stationarity testing, followed by the implementation of ARIMA and LSTM models to predict future sales.
By comparing traditional time series methods with neural networks, the project highlights the strengths and limitations of each approach.

## Objectives

* Understand historical sales patterns through EDA
* Test and enforce stationarity in the time series
* Build and evaluate an ARIMA model
* Build and evaluate an LSTM model
* Compare model performances for forecasting accuracy

## Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* TensorFlow / Keras


## Exploratory Data Analysis (EDA)

The EDA phase included:

* Time series visualization
* Trend and seasonality analysis
* Missing value handling


This step provided insights into sales behavior and informed model selection.

## Stationarity Testing

To prepare the data for time series modeling:

* Augmented Dickey-Fuller (ADF) Test was applied
* Differencing and transformations were used to achieve stationarity
* Stationary vs non-stationary behavior was visually and statistically validated

## ARIMA Model

* Identified optimal (p, d, q) parameters
* Fitted the ARIMA model on stationary data
* Generated short-term sales forecasts

ARIMA proved effective for capturing linear patterns and seasonality.

## LSTM Model

* Normalized time series data
* Created sequence windows for supervised learning
* Built and trained an LSTM neural network
* Produced multi-step sales forecasts

LSTM demonstrated strong performance in capturing non-linear and long-term dependencies.

## Model Comparison

ARIMA: Interpretable and effective for short-term forecasts
LSTM: Better at modeling complex patterns with sufficient data
Performance comparison highlighted trade-offs between interpretability and accuracy


Deploy as a forecasting API or dashboard
