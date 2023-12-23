# RSI Experiment Extended - ReadMe

This is the ReadMe file for the code of the RSI Experiment Extended indicator. This code is provided by Forex Robot Easy Team and can be used to calculate the RSI (Relative Strength Index) and analyze potential buy and sell signals based on floating levels.

## Indicator Parameters

- RSI_Period: The calculation period for the RSI.
- RSI_PriceType: The price type used for the RSI calculation.
- RSI_SmoothingMethod: The smoothing method used for the RSI calculation.
- Lookback_Period: The look-back period for the RSI calculation.
- Floating_Level1: The floating level 1 for determining buy and sell signals.
- Floating_Level2: The floating level 2 for determining buy and sell signals.

## Index Buffers

- RSI_FillBuffer: Stores the RSI values.
- RSI_UpLineBuffer: Stores the upper line values for the floating levels.
- RSI_MiddleLineBuffer: Stores the middle line values for the floating levels.
- RSI_DownLineBuffer: Stores the lower line values for the floating levels.
- TrendLineBuffer: Stores the trend line values for the buy and sell signals.

## Custom Indicator Initialization Function (OnInit)

This function is called when the indicator is initialized. It sets the buffer sizes and the indicator short name.

## Custom Indicator Iteration Function (OnCalculate)

This function is called for each bar to calculate the RSI values and analyze potential buy and sell signals based on the floating levels.

The function performs the following steps:

1. Calculates the RSI values using the iRSI function.
2. Iterates through each bar from the previous calculated bar to the current bar.
3. Calculates the average RSI value for the current look-back period.
4. Determines potential buy and sell signals based on the floating levels and assigns the corresponding values to the buffer arrays.

## Product Description

RSI Experiment Extended is an indicator that calculates the RSI and analyzes potential buy and sell signals based on floating levels. It is designed to help traders identify overbought and oversold market conditions and make informed trading decisions.

The indicator uses the RSI calculation period, price type, and smoothing method specified by the user. It also allows customization of the look-back period and floating levels for more accurate signal detection.

The RSI Experiment Extended indicator provides three lines for visual representation of the floating levels: the upper line, the middle line, and the lower line. When the RSI average value is above the upper line, it indicates a potential buy signal. When the RSI average value is below the lower line, it indicates a potential sell signal. When the RSI average value is between the upper and lower lines, it indicates no signal.

Please note that Forex Robot Easy Team is not the official developer of this product. We only provide this sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/rsi-experiment-extended-mt5-review-optimizing-forex-trades/).
