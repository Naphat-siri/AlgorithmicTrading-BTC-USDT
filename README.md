# Algorithmic Trading on BTC/USDT 

This project involves developing algorithmic trading agents to trade Bitcoin (BTC) against Tether (USDT) using different time intervals. The project is part of a Financial Engineering assignment and focuses on applying various trading strategies to both historical and live BTC/USDT data to optimize trading performance.

## Overview

The project contains multiple Jupyter notebooks that implement and analyze algorithmic trading strategies for BTC/USDT across different timeframes:

- **1-minute (1m)**
- **1-hour (1h)**
- **4-hour (4h)**
- **1-day (1d)**

The notebooks explore trading strategies by testing different indicators, backtesting results, and optimizing performance using machine learning and statistical methods.

## Files in the `agents` Folder

1. **agent_1m.ipynb**:
   - Implements trading strategies for BTC/USDT on a 1-minute interval.
   - Tests the performance of high-frequency trading strategies.
   - Analyzes short-term patterns and uses indicators such as moving averages, RSI, and Bollinger Bands.
   - Includes backtesting and visualization of trading results.

2. **agent_1h.ipynb**:
   - Develops and evaluates trading strategies on a 1-hour interval.
   - Suitable for intraday trading strategies, taking advantage of hourly trends and patterns.
   - Applies various technical indicators and uses backtesting to assess strategy performance.

3. **agent_4h.ipynb**:
   - Focuses on strategies using a 4-hour interval, balancing between intraday and longer-term trading.
   - Utilizes swing trading techniques and considers multi-hour trends.
   - Includes risk management measures and strategy optimization.

4. **agent_1d.ipynb**:
   - Implements trading strategies based on daily (1-day) intervals.
   - Targets longer-term strategies that capture broader market trends.
   - Uses technical indicators, moving averages, MACD, and sentiment analysis for decision-making.

5. **agent_All_Intervals_1m,1h,4h,1d.ipynb**:
   - Combines strategies across multiple timeframes (1m, 1h, 4h, 1d) to create a more comprehensive trading approach.
   - Evaluates how different timeframes interact and affect overall strategy performance.
   - Provides an analysis of multi-timeframe strategies and their risk-adjusted returns.

## Data Collection and Preprocessing

- **Live Data**: The function `fetch_live_data()` pulls the current price of BTC/USDT from the Binance API.
- **Historical Data**: The function `fetch_historical_data()` retrieves historical data for specified intervals using the Binance API.
- **Data Processing**: The notebooks preprocess the data, compute returns, and remove any missing values to prepare it for analysis.


## Improving the Model
The trading models can be improved by adjusting the following parameters and techniques:

1. **Hyperparameter Tuning**: Adjust the parameters for indicators like moving averages, RSI, and MACD to find the optimal values for each strategy.

2. **Feature Engineering**: Create new features from existing data (e.g., custom indicators, sentiment analysis) that may provide a predictive edge.

3. **Data Augmentation**: Expand the dataset by including more historical data or using synthetic data to simulate different market conditions.

4. **Ensemble Methods**: Combine predictions from different models to reduce volatility and improve overall strategy performance.

5. **Risk Management**: Incorporate advanced risk management techniques such as stop-loss, take-profit, or trailing stops to minimize downside risk.

## Disclaimer
This project is intended for educational purposes only. It is not financial advice and should not be used for live trading in financial markets. The project pulls live data from the Binance API,and users should be aware of the associated risks. Algorithmic trading carries significant risks, and users should fully understand these risks before attempting any trading activities.
