# Stock-Generator
The stock generator is designed to allow users to assess their list of tickers and select the valid tickers denominated in USD that best meet their needs using Python.

Users can choose volatility (whether they want to do safe, risky or wise investing), duration (short-term investment or long-term investment), number of stocks desired to choose and amount of money to invest.
Users would need to have a list of tickers csv file that they want to evaluate, data sanitization would ensure invalid tickers are filtered out.
The program extracts data from Yahoo Finance and assess financial metrics like market beta, standard deviation and expected return for each ticker provided.

Data analysis and integration were conducted to provide the companies that best meet user's criterias and expectations from the given list based on financial calculations.
From the financial analaysis above, it would assign the companies with better performance with a greater weight. 
The program would eventually return a DataFrame of chosen companies, their weights, current closing price and money allocation calculated based on weights.
