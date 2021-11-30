# Project Title - WHALE OFF PORTFOLIO
Analyzing different portfolio's volatility, returns , risk and sharpe ratios using historical datas. the main problem is to visualize the major metrics of the portfolios across all of these areas and determine which one is outperforming others. 




# Technologies 
In this project , I will be using pandas library, numpy, matplotlib, datetime to get the results. 




# Installation Guide
used pandas as pd, numpy as np, datetime as dt and matplotlib inline. 





# Usage
Use Pandas to read the following CSV files as a DataFrame. Be sure to convert the dates to a DateTimeIndex.


whale_returns.csv: Contains returns of some famous "whale" investors' portfolios.


algo_returns.csv: Contains returns from the in-house trading algorithms from Harold's company.


sp500_history.csv: Contains historical closing prices of the S&P 500 Index.




Detect and remove null values.


If any columns have dollar signs or characters other than numeric values, remove those characters and convert the data types as needed.


The whale portfolios and algorithmic portfolio CSV files contain daily returns, but the S&P 500 CSV file contains closing prices. Convert the S&P 500 closing prices to daily returns.


Join Whale Returns, Algorithmic Returns, and the S&P 500 Returns into a single DataFrame with columns for each portfolio's returns.




# Resources 
Pandas API docs 
Googlefinancehelp