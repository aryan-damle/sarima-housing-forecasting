# Long-Term Housing Market Prediction using SARIMA Model

## Overview
The housing market has become exponentially more difficult for first time home buyers to aquire their first house due to scarce supply and rising interest rates. The fundamental goal of this project is to predict the best time for a prospective buyer to lock in a low interest rate using historical data and a Seasonal- Autoregressive Integreated Moving Average (SARIMA) model.

## Introduction
The scope of the project is to produce reliable predictions for the national real estate market based on historical data provided by Federal Reserve Economic Data. The data comes from the S&P/Case Shiller 20-City Composite Home Price Index from 2000 to 2023. 

## Methods
For data forecasting in R, two popular models are ARIMA (Autoregressive Integrated Moving Average) and SARIMA (Seasonal AutoRegressive Integrated Moving Average). Both models are require the data set to be a time series object as both ARIMA and SARIMA are time series models. 
### Models 
- The **ARIMA** model uses historical data to predict future values. Autoregressive models implicitly assume that the future will resemble the past, which holds true when you look at the real estate market over a 10 year period. However, one weakness that ARIMA models have are that they can prove inaccurate under certain market conditions. If we had use an ARIMA model to predict the housing market in Summer of 2020, it would not have been able to predict the soar of the national real estate market. 
- **SARIMA** models however are able to take advantage of seasonal patterns that are present in the data. It can analyze these patterns and make more accurate predictions. Historically, the real estate market usually has a strong sales season from June to August. With this seasonal pattern, using the SARIMA model is more effective than an ARIMA model. 
