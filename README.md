# FNTF_santander


## Overview

This repository contains scripts for conducting financial data analysis, specifically focusing on portfolio returns and market performance. The analysis includes regression models, return adjustments, and the application of transaction costs. Key functionalities include:

- Regression analysis between rolling volatility and next month's returns.
- Portfolio return adjustments and evaluations.
- Plotting cumulative returns against market benchmarks.
- Reporting key financial metrics such as Sharpe ratio, maximum drawdown, and average annual return.

## Prerequisites

Ensure the following Python libraries are installed:

- pandas
- numpy
- matplotlib
- statsmodels
- pathlib
- multiprocessing

You can install the required packages using:

```sh
pip install pandas numpy matplotlib statsmodels pathlib multiprocessing
```

## Key Functions

### `conduct_regression(df1, df2, name1, name2)`

Performs regression analysis on the provided data frames and prints the summary.

### `plot_returns(portfolio_returns, market_return)`

Plots the cumulative returns of the portfolio and compares it with the market returns.

### `prepare_for_reg(df1, df2, name1, name2)`

Prepares data for regression by flattening and concatenating the given data frames.

### `report_portfolio_returns(portfolio_returns, market_return, periods_in_year=12)`

## Example

Refer to the provided script for a comprehensive example that demonstrates the entire process from data preparation to plotting returns and reporting metrics.

## License

This project is licensed under the MIT License. See the LICENSE file for details.