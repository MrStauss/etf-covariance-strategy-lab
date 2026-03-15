# ETF Covariance Strategy Lab

## Overview
This project explores covariance-driven allocation strategies
across major ETF sectors. The goal is to test whether covariance
structure can improve tactical allocation decisions relative to
passive benchmarks.

## Data
- Yahoo Finance ETF data
- Daily prices
- Sample period: 2010–present

## Strategy Design
1. Estimate covariance matrix of ETF returns
2. Identify dominant sector relationships
3. Construct allocation weights based on covariance structure
4. Apply volatility and momentum filters

## Benchmarks
- SPY (market benchmark)
- Sector-specific benchmarks (SOXX, XLK, etc.)

## Results
Include performance charts and summary statistics.

## Limitations
This strategy does not include transaction costs
or live trading constraints.

## Future Work
- Rolling covariance windows
- Transaction cost modeling
- regime-aware weighting
 
