# samindicator

A comprehensive, institutional-grade Pine Script indicator package for TradingView, built upon the original `CRT - Samusdtt` strategy.

## Overview

This repository contains a unified, all-in-one TradingView indicator script (`CRT-Samusdtt`) that consolidates multiple advanced trading concepts into a single optimized tool. 

### Key Features
- **Higher Timeframe (HTF) Candles:** Overlays configurable HTF candles directly on your chart with Range High/Low/Mid levels.
- **HTF Countdown Timer:** A dynamic clock format (HH:MM:SS) timer that counts down to the next HTF candle close. Auto-maps timeframe conversions.
- **SMT Divergences:** Automatically detects and labels structural divergences between two correlated assets (e.g., ES and YM). Includes a customizable statistical dashboard.
- **Seek & Destroy (S&D) Profile:** Highlights the Asian, London, and New York killzones. Identifies "Potential S&D Days" and "Valid S&D Days" with clean, transparent floating labels and a success rate warning table. Restricted to intraday charts (<= 1 Hour).
- **CISD (Change in State of Delivery):** Automatically maps and alerts on bullish and bearish market structure breaks and pullbacks, dynamically projecting levels forward.
- **Macro Tracker:** Visualizes key hourly and NY PM macro time windows (e.g., 09:50 - 10:10) on the chart. Cleanly hides itself on timeframes above 5 minutes.
- **Performance Optimized:** Heavy array processing and string formatting are deferred to `barstate.islast`, saving thousands of compute operations per bar to ensure blazing-fast load times.

## Usage

1. Open TradingView and open a chart.
2. Open the Pine Editor (v5).
3. Copy the contents of the `CRT-Samusdtt` file into the editor.
4. Click **Save** and then **Add to Chart**.

## Customization

The indicator provides a massive suite of inputs, neatly organized by group:
- **Higher Timeframe Candles** — Adjust timeframes, candle counts, and visual colors.
- **Extras** — Toggle auto-HTF mapping and the countdown timer.
- **Style / Dashboard** — Tweak the SMT Divergence styling and table layouts.
- **Seek and Destroy Profile** — Toggle the feature, adjust success criteria tolerances, and customize the transparent label text colors.
- **Macro Tracker** — Toggle specific hourly and PM macro windows on/off (only visible on 1-5min charts).

## License

- Pine Script portions are under the Mozilla Public License 2.0
- Additional contributions are under CC BY-NC-SA 4.0 as noted in source headers.

## Author

- Original: samusdtt
- Fork / advanced updates: harrysam11
- Source inspirations: Zeiierman, tradeforopp, LuxAlgo, toodegrees
