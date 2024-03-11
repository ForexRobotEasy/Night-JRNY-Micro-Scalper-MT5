# Night JRNY Micro Scalper MT5

Night JRNY Micro Scalper MT5 is an expert advisor designed for MetaTrader 5 platform. It is developed by Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com). Please note that ForexRobotEasy is not the official developer of this product, we are only showing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## Product Description

Night JRNY Micro Scalper MT5 is a fully automated trading robot that aims to profit from short-term market movements during the night session. It uses a scalping strategy to enter and exit trades quickly, aiming to capture small profits from the market.

### Features

- Lot size: You can define the lot size for each trade using the `lotSize` input parameter.
- Stop loss and take profit: You can set the stop loss and take profit levels in pips using the `stopLoss` and `takeProfit` input parameters.
- Maximum allowed spread: You can specify the maximum allowed spread in pips using the `maxSpread` input parameter.
- Risk percentage: You can set the risk percentage for each trade using the `riskPercentage` input parameter.

### How it works

The expert advisor follows a simple trading logic. It checks if the market is open during the night session using the `IsNightSession()` function. If the market is open, it calculates the lot size based on the risk amount using the `CalculateLotSize()` function. It also calculates the stop loss and take profit levels based on the input parameters and current symbol information.

If the spread is within the allowed range, it checks for market trend using the `IsMarketTrending()` function. If the market is trending, it enters a short position using the `OrderSend()` function. The order is opened with the calculated lot size, current bid price, and specified stop loss and take profit levels.

The expert advisor uses various built-in functions and indicators to perform its analysis and decision-making process. The specific trend analysis algorithm is not provided in the code and should be implemented separately.

### Installation and Usage

To use the Night JRNY Micro Scalper MT5 expert advisor, follow these steps:

1. Download and install MetaTrader 5 platform.
2. Open MetaEditor and create a new expert advisor file.
3. Copy and paste the provided code into the expert advisor file.
4. Adjust the input parameters according to your trading preferences.
5. Compile the expert advisor file.
6. Attach the expert advisor to a chart and enable automated trading.
7. Monitor the expert advisor's performance and make necessary adjustments if needed.

For detailed reviews and trading results of this product, please visit [this link](https://forexroboteasy.com/forex-robot-review/night-jrny-micro-scalper-mt5-unbiased-review-results/).

## Disclaimer

Please note that ForexRobotEasy is not the official developer of Night JRNY Micro Scalper MT5. We have provided this code as a sample that can work as described in the product. The official developer of this product can be found using MQL5.
