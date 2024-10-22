# Bull Bear Power (Quarterly Enhanced) - BBP-Q

## Introduction
This script calculates the Bull Bear Power (BBP) over a quarterly timeframe (60 days) with enhanced features, including normalization using ATR and additional technical indicators such as RSI and MACD.

## Features
- **Bull Bear Power Calculation**: Uses the difference between high and low prices relative to the EMA over a 60-day period.
- **Normalization**: BBP values are normalized over the past 60 days. An option to use ATR (Average True Range) for normalization is provided.
- **Tables**: Display the BBP values in tables with their respective changes from the previous bars.
- **Candle Coloring**: Candles are colored based on the normalized BBP values to visualize market trends.
- **Additional Indicators**: Includes normalized RSI and MACD for enhanced trend analysis.
- **Weighted Average**: A combined weighted average of the BBP, RSI, and MACD is calculated and plotted as a weighted BBP line.

## Inputs
- **Length (EMA 60 Days)**: Defines the period for the Exponential Moving Average.
- **Normalization Length**: Defines the period for normalizing the BBP values (default: 60 days).
- **Use ATR for Normalization**: Option to normalize BBP using ATR instead of its highest absolute value.
- **Show Tables**: Displays tables with BBP values and averages over the last 20 bars.

## Output
- **Colored Candles**: Candles are colored according to the BBP's normalized value to indicate bullish or bearish momentum.
- **Tables**: A table displays BBP values along with a visual summary of the trend (overbought or oversold levels).
- **RSI and MACD**: The script plots normalized RSI and MACD values.
- **Weighted BBP**: A line is plotted representing a weighted average of all the indicators to provide a comprehensive market trend signal.

## Usage
1. Load the script on a TradingView chart.
2. Adjust the input values according to your preferred settings.
3. Enable table display to view detailed BBP data.
4. Use the colored candles and the weighted BBP line for trading signals.

## License
This script is free to use for any purpose.
![Screenshot of BBP-Q Indicator](Bull_Bear_Power/bbp)
