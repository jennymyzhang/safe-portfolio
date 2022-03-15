# Aegis

> Generates a portfolio of minimum risk for conservative investors

![Aegis Image](/Sprout.png)

## What is Aegis?

Aegis is a portfolio generation algorithm that produces a portfolio with the minimum possible level of risk.  

It analyzes stock data extracted through yfinance and evaluates such data to produce an optimal portfolio allocation for maximum stability.

This generator is primarily targeted towards risk-adverse investors.

## Namesake

In Greek mythology, Aegis is the name given to the shield carried by Zeus and Athena. This shield is known for protecting the bearer against all external threats. Similarily, the Aegis generator protects its clients' investments against all possible forms of market risk.

### Vision (objective)

The objective of Aegis is to provide an opportunity for safe investors to preserve the value of their assets during stock market downturns. Through the use of Aegis, investors are able to minimize the level of exposed risk through diversification.

### Key Features

The core functionality of the algorithm analyzes market cap, beta, standard deviation, and expected return to evaluate the **stability** of each individual stock in a list of given stock tickers.

The optimization is done through analysis of the **Sharpe Ratio**, which indicates the relative volatility, thus resulting in a portfolio allocation that minimizes the level of risk involved.

This optimization algorithm has shown success in the real world, as it **prevented a 10% net loss** during a 4-week testing period during January 2022. This metric is calculated by comparing the performance of Aegis to the S&P 500.

### Status

Aegis has been in development since December 2021, with new features and iterations currently in progress.

### Tech Stack

Sprout is built with the Python language and uses various Python libraries to optimize its functionality.

**Libraries Used:** Yahoo Finance, Numpy, Pandas, Matplotlib

## License

This repository is licensed under copyright.

Copyright © 2022 jennymyzhang. All rights reserved.
