# Stock Trading Decision Model

This repository contains a Python implementation of a stock trading decision model based on pre-specified logic and historical data for the year 2023.

## Introduction

The stock trading decision model aims to make informed decisions on buying stocks based on market trends and historical data analysis. The model calculates the probability distribution of transitioning between bull, flat, and bear markets and recommends buy dates to maximize portfolio value.

## Data Acquisition

The data used for analysis includes daily closing prices of Apple (AAPL) stock for the year 2023. The data is sourced from Quantrocket and is provided in the form of:

- Daily closing prices (`p(d)`) for each trading day of the year.
- Buy dates (`Buy_Dates`) identified based on model analysis.

## Model Design

The model consists of the following components:

- **calculate_state**: Analyzes daily price changes to identify market trends (Bull, Flat, Bear).
- **calculate_portfolio_values**: Tracks portfolio values based on the specified buying and selling strategy.
- **transition_probability**: Analyzes historical data to determine transition probabilities between market states.
- **decide_buy**: Recommends whether it's a good day to buy stocks based on portfolio value changes.

## Implementation Details

The implementation is based on the provided data and includes modules for:
Defines the `Model` class with methods for analyzing market trends, calculating portfolio values, determining transition probabilities, and making buy decisions.
## Predictions

The model also provides predictions for future stock prices based on the ARIMA model. By inputting a specific date, the model can predict the stock price for that date, allowing users to plan their trading strategies accordingly.

## Results

The model outputs include transition probabilities and recommended buy dates based on historical data analysis. These outputs can be used to inform stock trading decisions and maximize portfolio value.
