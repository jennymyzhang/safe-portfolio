# Aegis

> Generates a portfolio of minimum risk for conservative investors

![Aegis Image](/Sprout.png)

## What is Aegis?

Aegis is a portfolio generation algorithm that produces a portfolio with the minimum possible level of risk.  

It uses statistical analysis of stock data extracted from yfinance and evaluates such data to produce an optimal portfolio allocation for growth.

This generator is primarily targeted towards risk-adverse clients.

## Namesake

In Greek mythology, Aegis is the name given to the shield carried by Zeus and Athena. This shield is known for protecting the bearer against all external threats. Similarily, the Aegis generator protects its clients' investments against all possible forms of market risk.

### Vision (objective)

The objective of Sprout is to provide an opportunity for growth seeking investors to quantitatively achieve a high-growth portfolio allocation that maximizes the level of expected return for a given level of preferred risk. 

### Key Features

The core functionality of the algorithm analyzes market cap, beta, standard deviation, and expected return to evaluate the stability of each individual stock in a list of given stock tickers.

The optimization is done through analysis of the Sharpe Ratio, which indicates the relative volatility, thus resulting in a portfolio allocation that grants investors the highest level of return for their highest tolerable level of risk.

In addition, a Command Line Interface was built for clients to customize and adjust the generated portfolio to the preferred level of risk tolerance.

This optimization algorithm has shown success in the real world, as it **outperformed the S&P 500 by 70%** in a 4-week testing period during January 2022.

### Status

Sprout has been in development since November 2021, with new features and iterations currently in progress.

### Tech Stack

Sprout is built with the Python language and uses various Python libraries to optimize its functionality.

**Libraries Used:** Yahoo Finance, Numpy, Pandas, Matplotlib

## License

This repository is licensed under copyright.

Copyright © 2022 jennymyzhang. All rights reserved.


<!-- ![images](https://user-images.githubusercontent.com/97857205/158243696-6ef56e10-c610-44bf-92c9-e88f845da070.jpg)

It is a portfolio allocation algorithm that uses statistical analysis of stock data to generate a portfolio of minimal risk for risk-adverse clients.

During December 2020, It successfully achieved breakeven during a -10% market downturn.

I implemented market capitalization, beta, standard deviation and expected return analysis to evaluate the expected relative volatility of each stock.

Technologies used: Python, yfinance, NumPy, Pandas, Matplotlib -->


