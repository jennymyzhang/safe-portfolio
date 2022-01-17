# Stock-Generator
Please visit "Stock Generator.ipynb" for a clearer view and "Stock Generator.py" for scripts.


The stock generator is designed to allow users to assess their list of tickers and select the valid tickers denominated in USD that best meet their needs using Python.

Users can choose volatility (whether they want to do safe, risky or wise investing), duration (short-term investment or long-term investment), number of stocks desired to choose and amount of money to invest.
Users would need to have a csv file that contains a list of tickers they want to evaluate. Data sanitization would ensure invalid tickers are filtered out.
The program extracts data from Yahoo Finance and assesses financial metrics like market capitalisation, beta, standard deviation, expected return and sharp ratio for each ticker provided.

Data analysis and integration were conducted to provide the stocks that best meet user's criteria and expectations from the given list based on financial calculations above.
From the financial analaysis above, it would assign the companies with better performance with a greater weight. 
The program would eventually return a DataFrame of chosen companies, their weights, current closing price and money allocation calculated based on weights.
