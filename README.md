# Indice Trading Strategy 

## Overview

This is a custom trading strategy developed for TradingView's Pine Script, the purpose of this script is to add confluence to your decision.
The strategy focuses on identifying potential buy and sell signals on indices, applying filters for trend direction, and using customizable parameters.

## Strategy Details

- **EMA Length**: The strategy uses a 200-period Exponential Moving Average (EMA) as a key indicator for trend direction.
- **Range Filter**: A custom range filter is employed to smooth out price action and better define the trading range. This is determined using the 'Swing Source' and 'Swing Period' inputs, alongside a multiplier for range size.
- **Stop Loss & Take Profit**: The strategy features customizable stop loss and take profit levels for both long and short trades, defined as percentages of the position's entry price.

## Backtest Results

As of **August 1, 2024**, the backtest results for this strategy on major indices (e.g., S&P 500,) show promising performance:

- **Initial Capital**: $1,000 CAD
- **Backtest Period**: January 1, 2020 - January 1, 2024
- **Commission**: 0.075% per trade
- **Win Rate**: [69.81%]    ( 45m TF ) 
- **Max Drawdown**: [4.87%]
- **Total Net Profit**: [12.55%]

_Note: These results are based on historical data and may not accurately predict future performance._


