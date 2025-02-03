# Algorithmic_Trading
A simple trading strategy built using Exponential Moving Averages (EMA) and Relative Strength Index (RSI) in Backtrader and visualized using matplotlib. The strategy downloads stock data from Yahoo Finance, executes trades based on EMA crossovers and RSI thresholds, and analyzes performance with Sharpe Ratio, Drawdown, and Trade Analysis.
Buy when Fast EMA > Slow EMA and RSI < 30.
Sell when Fast EMA < Slow EMA and RSI > 70.
