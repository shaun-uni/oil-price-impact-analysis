# Sensitivity Analysis of Canadian Oil and Gas Companies' Stock Prices to WTI Price Fluctuations

## Project Overview
This Jupyter Notebook conducts a sensitivity analysis to understand how the stock prices of major Canadian oil and gas companies, specifically large-caps, respond to fluctuations in crude oil prices. 
Large-cap companies are public companies with a market cap over $10 billion. These companies are typically leaders in the Canadian Energy space with substantial resources and major operations in the Canadian oil sands.

### Significance of Using WTI
WTI crude oil is a benchmark of crude oil that serves as a reference price for buyers and sellers of oil worldwide, especially in the North American oil markets. 
I used WTI prices as a way to gauge the economic factors impacting the global oil market and how these factors correlate with the stock performance of these companies. 
By analyzing the relationship between WTI prices and stock prices, we can infer how global oil price changes affect financial health and stock market performance.

## To run this notebook:
1. Clone the repo to your local machine.
2. Install required Python packages using pip:
     ```bash
     pip install yfinance pandas matplotlib scipy
     ```
4. Open and Run the Jupyter Notebook

## Results Overview
The analysis includes:
- **Correlation Coefficient**: Indicates the strength and direction of the linear relationship between WTI prices and company stock prices.
- **Slope of Linear Regression**: Measures the sensitivity of the company's stock price to changes in WTI prices.

The notebook concludes with a detailed visualization of each company's stock price in relation to WTI prices and a summary table of correlation coefficients and slopes.
