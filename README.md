# Lone Wolf Opening Range Breakouts & VWAP

A Pine Script v6 indicator combining opening-range breakout levels and targets with an anchored VWAP and optional deviation bands.

## Features

- Opening range based on a selected timeframe or a custom session and timezone.
- Historical opening ranges, breakout signals, directional bias, range-based targets, and an optional session moving average.
- Anchored VWAP for sessions, weeks, months, quarters, years, decades, centuries, earnings, dividends, or splits.
- Up to three VWAP bands, calculated by standard deviation or percentage, with optional fills.

## Add it to TradingView

1. Open TradingView's Pine Editor.
2. Paste the contents of [`lone-wolf-opening-range-vwap.pine`](lone-wolf-opening-range-vwap.pine).
3. Save the indicator and select **Add to chart**.

The script is intended for intraday charts below one day; it raises an error on daily and higher timeframes. VWAP requires volume data from the chart's data vendor. Event-based anchors depend on the symbol having the corresponding data.

## Attribution and license

The opening-range logic is adapted from LuxAlgo's open-source [Opening Range with Breakouts & Targets](https://www.tradingview.com/script/fCqLTp6r-Opening-Range-Breakouts-Targets-LuxAlgo/) script. The anchored VWAP section follows TradingView's built-in VWAP implementation. TradingView identifies code from its built-in scripts and documentation as public domain in its [script publishing rules](https://www.tradingview.com/support/solutions/43000590599-script-publishing-rules/).

This repository is licensed under the Mozilla Public License 2.0. See [`LICENSE`](LICENSE). The license includes a no-warranty provision. This indicator is for charting and educational use; it is not financial advice.
