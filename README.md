# Financial-Modeling-and-Portfolio-Optimization

## Project Overview

This project aims to construct a diversified portfolio with a Sharpe ratio greater than 1.0 using technical trading strategies like Moving Average Crossover and Bollinger Bands. The portfolio consists of 8 financial instruments across different asset classes, including equities, fixed income, commodities, and currencies.

## Key Objectives

- Implement Moving Average Crossover and Bollinger Bands strategies
- Optimize portfolio performance using Mean-Variance Optimization
- Achieve a Sharpe ratio greater than 1.0
- Analyze strategy performance across different asset classes
- Compare portfolio performance to individual strategies and benchmarks

## Data Analysis

The team analyzed historical price data for multiple financial instruments, focusing on:

- Calculating moving averages and Bollinger Bands
- Implementing Go Flat and Go Short variations of Moving Average Crossover
- Evaluating strategy performance using Sharpe ratios
- Conducting Mean-Variance Optimization for portfolio construction

## Key Findings

### Strategy Performance

- Moving Average Crossover (Go Flat) performed well for equities and commodities
- Moving Average Crossover (Go Short) was effective for currencies and fixed income
- Bollinger Bands strategy showed moderate performance across instruments

### Portfolio Optimization

- Equal Weight Portfolio Sharpe Ratio: 1.285
- Maximum Sharpe Portfolio Sharpe Ratio: 1.352
- The optimized portfolio outperformed all individual strategies

### Diversification Benefits

The portfolio effectively balanced risk by combining low-correlated strategies with higher-performing equities, reducing overall volatility.

## Selected Instruments and Strategies

- Equities: AAPL, AMZN, GE, INTC, SPY
- Fixed Income: FBNDX
- Commodity: GOLD
- Currency: EUR

Strategies:
- Go Flat: AAPL, AMZN, GOLD, SPY
- Go Short: EUR, GE, FBNDX
- Bollinger Bands: INTC

## Performance Statistics

Maximum Sharpe Portfolio:
- Sharpe Ratio: 1.352
- Average Annual Return: 0.111
- Annual Risk: 0.082
- Max Drawdown: -0.125
- Success Ratio: 0.549
- Beta to S&P 500: 0.112

## Conclusion

The Max Sharpe Portfolio, with a Sharpe Ratio of 1.35, significantly outperformed all other portfolios and individual strategies, offering the best risk-adjusted return. Through Mean-Variance Optimization, optimal weights were identified that maximized the portfolio's Sharpe ratio while keeping risk at manageable levels.

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
