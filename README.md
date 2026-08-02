# SPX Tail Hedge Strategy

This project evaluates whether a systematic long-put hedge can reduce downside risk in an S&P 500 portfolio.

## Project Overview

The analysis uses SPX data from March 31, 2008 through February 28, 2025.

The strategy combines:

- A long SPX position
- Three staggered put-option legs
- Approximately three-month option maturities
- A roll one business day before the third Friday
- Historical VaR, variance-covariance VaR, and Expected Shortfall
- Crisis-period and allocation-sensitivity analysis

## Key Findings

- The hedge reduced maximum drawdown compared with the unhedged SPX portfolio.
- Tail-risk measures improved at both the 95% and 99% confidence levels.
- The strategy was especially effective during the 2008–2009 financial crisis and the 2020 COVID shock.
- A 0.8% total hedge allocation produced the strongest return-to-volatility result among the allocations tested.
- Monthly staggered rolling performed better than the quarterly-only structure.

## Files

- `Tail Hedge Project Final Version.ipynb` — complete Python analysis
- `portfolio_growth_comparison.png` — portfolio growth comparison
- `drawdown_comparison.png` — drawdown comparison

## Tools Used

- Python
- pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Disclaimer

This project is for educational and analytical purposes only and is not investment advice.
