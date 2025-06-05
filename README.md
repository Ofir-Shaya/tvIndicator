# TV Indicator

This repository contains a Pine Script indicator for TradingView. The script colors candles based on momentum, trend strength, and volume conditions. Blue and pink candles highlight potential bullish or bearish shifts using a short moving average (10-day) compared to a volume-adjusted mid-length moving average (20 to 50 days).

## Usage
1. Open TradingView and create a new blank indicator script.
2. Copy the contents of `indicator.pine` into the TradingView editor.
3. Add the indicator to your chart to visualize the colored candles and cues.

## Notes
- The indicator does not execute trades; it only displays visual cues.
- Blue candles require the short MA to be rising above the mid MA with higher volume.
- Pink candles require the short MA falling below the mid MA with higher volume.

