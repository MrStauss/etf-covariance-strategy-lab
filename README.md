# ETF Covariance Strategy Lab

## Overview
This project explores covariance-driven allocation strategies across ETF sectors.
The goal is to evaluate whether covariance structure between sector ETFs can be used to improve tactical allocation decisions relative to passive benchmarks.

The research focuses on identifying relationships between sectors and dynamically adjusting exposure based on market structure.

## Strategy Concept
The strategy is based on three components:

1. Covariance Structure Analysis

- Estimate covariance relationships between sector ETFs

- Identify dominant relationships between sectors

2. Sector Rotation

- Allocate capital based on covariance-driven signals

- Apply volatility and momentum filters

3. Risk Control

- Benchmark performance against SPY and sector benchmarks

- Evaluate drawdowns and Sharpe ratios

## Data
Market data is retrieved using:
-Yahoo Finance (yfinance)
-Daily ETF price data

Example ETFs used:

Sector	ETF
- Semiconductors	SOXX
- Technology	XLK
- Financials	XLF
- Energy	XLE
- Utilities	XLU
- Market Benchmark	SPY


## Benchmarks
- SPY (market benchmark)
- Sector-specific benchmarks (SOXX, XLK, XLE, etc.)

## Results
Include performance charts and summary statistics.

## Limitations
This project is research-oriented and does not include:
transaction costs
slippage
liquidity constraints

Results should be interpreted as exploratory research rather than production trading signals.

## Future Work
- Rolling covariance windows
- Transaction cost modeling
- regime-aware weighting

## Technologies Used
-Python
-Pandas
-NumPy
-Matplotlib
-SciPy
-yfinance
 
