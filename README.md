# Tesla Stock Price Tracking Project

## Project Overview

This project aims to create a dataset for Tesla's stock prices, including daily updates, average monthly stock prices, daily closing figures, and the volume of stock traded for the last 3 months. This dataset is intended to help shareholders identify trends in Tesla's stock price.

## Prerequisites

- A Google account to access and update the dataset daily.
- Access to the Tesla logo for use in documentation and presentations.

## Tesla Logo

The Tesla logo can be found in the resources section of the lecture. Alternatively, you can download it from the link below:

[Download Tesla Logo](https://finch-groundhog-9245.squarespace.com/s/teslalogo.png)

## Data Collection

### Data Sources

- Daily stock price data will be collected from a reliable financial data provider (e.g., Yahoo Finance, Google Finance, or an API service like Alpha Vantage).
- The dataset will be updated daily to ensure the most recent stock prices and trading volumes are available.

### Data Fields

The dataset will include the following fields:
- **Date**: The date of the trading day.
- **Closing Price**: The closing price of Tesla's stock on the trading day.
- **Volume**: The number of shares traded on the trading day.
- **Average Monthly Price**: The average closing price of Tesla's stock for each month.

## Data Storage

The dataset will be stored in a Google Sheet, which allows for easy updates and sharing. The Google Sheet will be structured as follows:

```plaintext
.
├── Tesla_Stock_Data.xlsx
├── README.md
└── logo
    └── teslalogo.png
