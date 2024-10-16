# FAANG Stock Analysis

## Overview
This project conducts a comprehensive analysis of the stock prices of FAANG companies (Facebook, Apple, Amazon, Netflix, Google) over the past three years. By leveraging Python’s data manipulation and visualization libraries, the project aims to understand price fluctuations, returns, and volatility, as well as provide a risk assessment for each stock.

## Objectives
- Analyze the historical stock data of FAANG companies.
- Compare the performance of these companies based on key financial metrics.
- Visualize trends and identify significant events that impacted stock prices.
- Calculate moving averages to smoothen stock price data and observe long-term trends.
- Assess stock risk based on daily returns and volatility.

## Tools and Libraries
- **Python**: Main programming language used for data analysis.
- **pandas**: Used for data manipulation and analysis.
- **numpy**: Utilized for numerical calculations.
- **yfinance**: For fetching historical stock data from Yahoo Finance.
- **matplotlib** & **seaborn**: Libraries for data visualization.
- **datetime**: Used to handle date-related data manipulation.

## Data Collection
Data for FAANG companies was collected using the `yfinance` library, which provides a simple interface to download financial data from Yahoo Finance. The historical stock prices from the last three years were retrieved for analysis.

## Data Analysis
### Stock Price Trends
For each stock, the project visualized the adjusted closing price over time to understand long-term price movements. This was complemented by volume plots to highlight periods of high trading activity.

### Moving Averages
The moving averages (10-day, 25-day, and 50-day) were calculated to smooth out short-term fluctuations and identify long-term trends. This is particularly useful for understanding the overall direction of the stock's price.

### Daily Returns
Daily returns were calculated to understand the day-to-day performance of each stock and assess its volatility.

### Volatility and Risk Assessment
To evaluate the risk associated with each stock, the standard deviation of the daily returns was used. Higher volatility suggests a higher risk.

## Key Insights
- **Major Drop (April-May 2022)**: Significant drop in Netflix’s stock price, coinciding with the company’s first reported subscriber loss in a decade.
- **Steady Recovery**: Following the drop, Netflix’s stock gradually recovered due to the introduction of new services like the ad-supported tier.
- **Volatility Patterns**: Observed volatility spikes align with major market announcements and earnings reports.

## Visualizations
Visualizations played a key role in analyzing the stock data. Below are some examples:
- Stock Price Over Time: Trends in adjusted closing prices for each stock.
- Moving Averages: Comparison of different moving averages to observe long-term stock performance.
- Daily Returns: Distribution of daily returns to assess volatility.
- Volume Analysis: Changes in trading volume to identify periods of high investor activity.

# This project provided valuable insights into the performance of FAANG stocks over the past three years, highlighting both their growth trends and risks. Moving averages, daily returns, and volatility analyses helped quantify the risk associated with each stock, enabling a thorough comparison.
