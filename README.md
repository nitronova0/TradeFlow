# TradeFlow — Trading & Risk Calculator

A lightweight trading calculator built with vanilla HTML, CSS and JavaScript.

## Features

- Risk-per-trade calculation
- Win-rate and trade-count projections
- Average Win / Average Loss mode
- Profit Factor mode
- Expected return and compounded balance projection
- Break-even win-rate calculation
- Optional Twelve Data live market watch
- Manual market-regime classification
- Responsive 2D dashboard design

## Profit Factor

Profit Factor is:

`Gross Profit / Gross Loss`

In Profit Factor mode, the calculator derives an implied average win from:

`Average Win = Profit Factor × Average Loss`

The result is a mathematical projection, not a historical backtest.

## Live market data

No API key is included in this repository.

For a public production deployment, do not put a private API credential directly in browser JavaScript. Use a backend/serverless proxy.

## Tech

- HTML
- CSS
- JavaScript
- Twelve Data API (optional)

## Disclaimer

For educational and research purposes only. This is not financial advice.
