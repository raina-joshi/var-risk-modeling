# Value-at-Risk (VaR) Modeling and Backtesting

## Objective
This project estimates potential portfolio losses using Value at Risk (VaR) and evaluates model reliability through backtesting and simulation techniques.

## Methods
- Historical VaR (percentile-based)
- Monte Carlo VaR (normal distribution-based simulation)
- Backtesting using violation analysis

## Approach
- Collected historical price data and computed daily returns  
- Estimated 95% and 99% VaR using historical distribution  
- Performed backtesting to evaluate model accuracy  
- Simulated future returns using Monte Carlo methods  

## Results
- 95% VaR ≈ -2.5%  
- 99% VaR ≈ -4.2%  
- Backtesting violation rates (~5% and ~1%) aligned with expected confidence levels

## Key Insights
- Historical VaR captures extreme market movements more effectively  
- Monte Carlo VaR underestimates tail risk due to normal distribution assumption  
- Backtesting is critical for validating model reliability  

## Tools Used
Python, pandas, NumPy
