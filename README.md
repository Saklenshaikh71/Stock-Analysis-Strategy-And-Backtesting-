### Comprehensive Stock Analysis Strategy and Backtesting Report

## Overview
This project evaluates the performance of the top 20 NSE (National Stock Exchange) stocks using a backtested trading strategy. It applies a Simple Moving Average (SMA) crossover strategy and analyzes historical data spanning the past five years. The goal is to assess the effectiveness of this strategy, understand its performance metrics, and derive actionable insights.

## Objective
The primary objectives of this report are to:

Evaluate the performance of the SMA crossover strategy on top NSE stocks.
Assess the strategy's performance metrics and impact of market conditions.
Suggest potential improvements for better performance.

## Scope
The analysis covers the following top 20 NSE stocks by market capitalization:

RELIANCE.NS - Reliance Industries Limited
TCS.NS - Tata Consultancy Services Limited
HDFCBANK.NS - HDFC Bank Limited
BHARTIARTL.NS - Bharti Airtel Limited
ICICIBANK.NS - ICICI Bank Limited
SBIN.NS - State Bank of India
INFY.NS - Infosys Limited
LICI.NS - Life Insurance Corporation of India
HINDUNILVR.NS - Hindustan Unilever Limited
ITC.NS - ITC Limited
LT.NS - Larsen & Toubro Limited
HCLTECH.NS - HCL Technologies Limited
ONGC.NS - Oil and Natural Gas Corporation Limited
BAJFINANCE.NS - Bajaj Finance Limited
TATAMOTORS.NS - Tata Motors Limited
SUNPHARMA.NS - Sun Pharmaceutical Industries Limited
MARUTI.NS - Maruti Suzuki India Limited
NTPC.NS - NTPC Limited
AXISBANK.NS - Axis Bank Limited
KOTAKBANK.NS - Kotak Mahindra Bank Limited
M&M.NS - Mahindra & Mahindra Limited

## Data Acquisition and Preparation
Data Source
The data was acquired using the nsepy library, which provides daily historical data from the NSE. The data includes the following fields:

Open Price
High Price
Low Price
Close Price
Volume
Data Collection Process
Data was collected for each stock over a 5-year period and saved in CSV format. Python scripts were used for automation to ensure consistency and accuracy.

## Data Cleaning and Preparation
Handling Missing Values: Missing data was interpolated or forward-filled. Rows with significant missing data were removed.
Date Alignment: Data was aligned to ensure consistency in trading dates.
Normalization: Adjustments were made for stock splits and dividend payments.
Validation: Consistency checks and statistical summaries were conducted.
Strategy Implementation and Backtesting
Strategy Description
The Simple Moving Average (SMA) Crossover Strategy involves:

Short-Term SMA: Calculated over a 50-day period.
Long-Term SMA: Calculated over a 200-day period.
Trading Signals:

Buy Signal: Short-Term SMA crosses above Long-Term SMA.
Sell Signal: Short-Term SMA crosses below Long-Term SMA.
Backtesting Procedure
Implementation: The strategy was coded using Python with libraries such as pandas and matplotlib.
Performance Metrics: Metrics include Total Returns, Annualized Returns, Maximum Drawdown, Sharpe Ratio, Win/Loss Ratio, and Number of Trades Executed.
Yearly Breakdown
Performance metrics were analyzed yearly to identify trends and variability.

## Analysis and Insights
Visualization of Results
Equity Curves: Show the cumulative return over time.
Drawdown Charts: Illustrate declines from peaks.
Distribution of Returns: Displays the frequency distribution of returns.
Monthly and Yearly Performance: Evaluate performance trends across different time frames.
Performance Analysis
Strengths: Consistent performers like TCS.NS and HDFCBANK.NS.
Weaknesses: Underperformers like ONGC.NS and NTPC.NS.
Market Conditions Impact: Better performance in bull markets; challenges in bear markets.
Strategy Improvements
Optimizing Moving Average Periods
Incorporating Additional Indicators
Risk Management Enhancements
Conclusion
The SMA crossover strategy showed varying performance across different stocks and market conditions. It performed well in bull markets but faced challenges in bear markets.

## Recommendations
Further research into other trading strategies and indicators.
Practical application with real-time market conditions and enhanced risk management.
Appendices
Appendix A: Data Tables
Detailed tables of raw data and performance metrics.
Appendix B: Additional Charts
Supplementary charts and visualizations.

## References
Data sources and libraries used, including yfinance, pandas, NumPy, and matplotlib.
Relevant literature and research papers on trading strategies and backtesting.
Feel free to adjust the sections according to your needs and ensure that all relevant information is included. You can create a file named README.md and place it in the root directory of your GitHub repository. This README will help others understand your project, replicate your results, or build upon your work.



