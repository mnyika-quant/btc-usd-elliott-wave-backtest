# BTCUSD Elliott Wave WXY Double Zigzag — Backtest with RSI Entry Confirmation

**Author:** Munyaradzi Nyika  
**Date:** March 2026  
**Asset:** BTCUSD (1-Hour Timeframe)

## Project Summary

This project presents a bearish short trade setup on BTCUSD identified using Elliott 
Wave analysis on the 1-hour timeframe. The price structure is proposed to be a WXY 
double zigzag correction. The entry logic requires two conditions to be simultaneously 
met — price must exceed the 0.618 Fibonacci minimum completion level for Wave Y and 
the RSI must cross below its RSI based moving average confirming momentum has shifted 
to the downside. The exit is triggered when RSI crosses back above its MA.

## Results

| Metric | Value |
|--------|-------|
| Market Return | -7.49% |
| Strategy Return | +0.27% |
| Outperformance | +7.76% |
| Strategy Sharpe | 0.44 |
| Market Sharpe | -1.48 |
| Max Drawdown | -1.9% |
| Win Rate | 43.75% |

## How To Run

1. Click the Colab link below
2. Click Runtime → Run All
3. All cells will execute automatically

## Open In Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mnyika-quant/btc-usd-elliott-wave-backtest/blob/main/btcusd_elliott_wave_backtest.ipynb)

## Libraries Used

- yfinance
- pandas
- numpy
- matplotlib


