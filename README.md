# portfolio-calculator
Python tool analysing a stock portfolio: returns, weights, concentration alerts 
# Portfolio Calculator

Python tool that analyses a stock portfolio and produces a report:
performance of each position, weights, and a concentration-risk alert.

## Why this project
Portfolio views in apps like Revolut or Sarwa show performance and
allocation at a glance. I rebuilt a simplified version to learn Python
fundamentals on a financial use case.

## Data
4 fictional positions (AAPL, MSFT, VWCE, TSLA) stored as a list of
dictionaries: ticker, quantity, purchase price, current price.
No real market data is used in this version.

## What it computes
- Invested value, current value, gain/loss in € and %
- Return of each position, labelled "loss / low / good"
- Best and worst position
- Weight of each position, with a warning above 40%

## Example output
(coller ici une capture d'écran de ton rapport)

## How to run
Open `portfolio_calculator.ipynb` in Jupyter, Kaggle or Google Colab
and run all cells from top to bottom.

## Limitations
- Prices are hard-coded, not fetched from the market
- Past returns say nothing about future performance
- Return does not account for purchase dates or dividends

## Next steps
- Fetch real prices with `yfinance`
- Add volatility, correlation and a benchmark comparison
- Charts with matplotlib
