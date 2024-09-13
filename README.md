# Portfolio Optimization using Markowitz Model

This repository demonstrates how to optimize a stock portfolio using the Markowitz Model for efficient portfolio construction. The project involves selecting a set of high-performing stocks, simulating different portfolio allocations, and visualizing the efficient frontier to aid in decision-making for optimal portfolio management.

## Features

- **Stock Selection**: The project focuses on selecting stocks from different sectors to minimize correlation.
- **Monte Carlo Simulations**: Simulates thousands of different portfolio allocations to identify the optimal mix.
- **Efficient Frontier Visualization**: Plots the efficient frontier to show the trade-off between risk and return.
- **Risk/Return Metrics**: Calculates the expected return, volatility, and Sharpe Ratio for different portfolios.

## Libraries Used

The project makes use of the following Python libraries:

- `numpy`: For numerical calculations
- `pandas`: For data manipulation and analysis
- `matplotlib`: For plotting graphs
- `seaborn`: For enhanced visualizations
- `yfinance`: For fetching stock data from Yahoo Finance

## How to Run

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/Portfolio-Optimization-Markowitz.git
    ```

2. **Install the required Python packages**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Open the Jupyter notebook**: `Portfolio_Optimization_using_Markowitz_Model.ipynb` and execute the cells to see the portfolio optimization results.

## Dataset

The stock data is fetched directly from Yahoo Finance using the `yfinance` library for the following five stocks:

- GHCL Ltd (`GHCL.NS`)
- IDFC First Bank (`IDFCFIRSTB.NS`)
- Tata Motors (`TATAMOTORS.NS`)
- Narayana Hrudayalaya (`NH.NS`)
- Emami Ltd (`EMAMILTD.NS`)

You can modify the stock list based on your preference in the notebook.

## Key Variables

- `NUM_TRADING_DAYS`: Number of trading days in a year (set to 252).
- `NUM_SIMULATIONS`: Number of portfolio simulations to be run (set to 100,000).
- `start_date`, `end_date`: Defines the time period for fetching stock data (from 2015-10-01 to 2023-10-01).

## Visualization

The project generates visualizations including:

- Portfolio weight distribution
- Efficient frontier
- Risk vs return plot for different portfolios

## Conclusion

This project provides a practical implementation of the Markowitz Portfolio Theory, demonstrating how to apply quantitative methods to optimize portfolio allocation and visualize the efficient frontier for risk management.
