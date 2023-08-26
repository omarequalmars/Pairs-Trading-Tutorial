# Pairs Trading Project

This repository contains my pairs trading project, where I explore the concept and implementation of a statistical arbitrage strategy based on the cointegration of pairs of stocks. Pairs trading is a market-neutral strategy that exploits the mean-reverting behavior of certain pairs of stocks that have a long-term equilibrium relationship.

## Data

The data used in this project consists of the daily closing prices of 30 stocks from the Egyptian Exchange (EGX) from January 2018 to July 2023. The data was obtained from Investing.com, The tickers of the stocks are listed in the file `Tickers`.

## Methodology

The main steps of the project are as follows:

- Preprocessing the data to handle missing values, outliers, and non-stationarity.
- Finding the optimal pairs of stocks using the minimum distance approach, which minimizes the sum of squared deviations between the normalized prices of each pair.
- Testing the cointegration of each pair using the augmented Dickey-Fuller (ADF) test and the Johansen test.
- Developing a trading strategy based on the z-score of the spread between each pair, which indicates the deviation from the long-term equilibrium.
- Evaluating the performance of the strategy using various metrics, such as cumulative returns, Sharpe ratio, maximum drawdown, and hit ratio.

## References

The project is based on the ideas and methods from the following books:

- Algorithmic Trading: Winning Strategies and Their Rationale by Ernest P. Chan
- A Signal Processing Perspective on Financial Engineering by Yiyong Feng and Daniel P. Palomar

## Future Work

The project is still a work in progress, and I plan to add more features and improvements in the future. Some of the planned tasks are:

- Developing a more professional and robust statistical arbitrage strategy that incorporates more factors, such as transaction costs, market impact, risk management, and portfolio optimization.
- Applying the strategy to other markets and asset classes, such as forex, commodities, and cryptocurrencies.
