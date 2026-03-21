0 # samindicator

A Pine Script indicator package for TradingView, developed from the original `CRT - Samusdtt v1` strategy.

## Overview

This repository contains a TradingView indicator script (`sam11`) which displays:
- Higher timeframe candlestick panels
- Configurable candle count and style
- Range high/low/mid levels
- Optional HTF external panels
- HTF candle countdown timer and auto-timeframe mapping

## Usage

1. Open TradingView and open a chart.
2. Create a new indicator script in Pine Script v5.
3. Copy the contents of the `sam11` file into the editor.
4. Save and add it to the chart.

## Inputs

- `Higher Timeframe Candles` — timeframe, candle count, colors
- `Range` section — high/low/mid display toggles and colors
- `Table` section — show/hide table, size, position, text color
- `Extras` toggles:
  - `Enable All New Features`
  - `Auto-change HTF & Separators`
  - `HTF Candle Countdown`

## License

- Pine Script portions are under the Mozilla Public License 2.0
- Additional contributions are under CC BY-NC-SA 4.0 as noted in source headers.

## Author

- Original: samusdtt
- Fork / updates: harrysam11
- Source inspiration: Zeiierman
