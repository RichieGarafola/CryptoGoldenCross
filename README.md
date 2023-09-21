# Cryptocurrency Algorithmic Trading Strategy

This Python script implements a simple cryptocurrency algorithmic trading strategy using historical price data and moving averages. The strategy is based on moving average crossovers and is intended for educational purposes only. Please exercise caution and conduct thorough research before using it for real trading.

## Table of Contents

- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Strategy Overview](#strategy-overview)
- [Results](#results)
- [Disclaimer](#disclaimer)

---

## Dependencies

To run this script, you will need the following Python libraries installed:

- `yfinance`: For downloading historical cryptocurrency price data.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For plotting the results.

You can install these dependencies using `pip` with the command:


pip install yfinance pandas numpy matplotlib

---

## Installation

- Clone this repository to your local machine:

        git clone https://github.com/yourusername/cryptocurrency-algo-trading.git
        

- Change into the project directory:

        cd cryptocurrency-algo-trading


- Run the Python script:

        python crypto_algo_trading.py

---

## Usage

- Modify the crypto_symbol, start_date, and end_date variables in the script to specify the cryptocurrency, start date, and end date for the historical data you want to analyze.

- Adjust the short_window and long_window variables to set your desired short-term and long-term moving average periods.

- Execute the script to see the historical price chart, moving averages, and buy/sell signals.

---

## Strategy Overview

This trading strategy is based on a simple moving average crossover approach. It uses two moving averages:

SMA50 (Short-Term Moving Average): This represents the short-term trend.
SMA200 (Long-Term Moving Average): This represents the long-term trend.

Buy Signal: When SMA50 crosses above SMA200, a buy signal is generated.
Sell Signal: When SMA50 crosses below SMA200, a sell signal is generated.

---

## Results

The script generates a historical price chart with buy and sell signals marked as green "^" and red "v" markers, respectively. Use this information for educational purposes and consider additional risk management and backtesting before using it for actual trading.

---

## Disclaimer

- This script is for educational purposes only and should not be considered financial advice.

- Cryptocurrency trading involves significant risk, and past performance is not indicative of future results.

- Always conduct thorough research and consider consulting with a financial advisor before implementing any trading strategy.