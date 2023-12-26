# Time Range Breakout

[![Review and Trading Results](https://forexroboteasy.com/forex-robot-review/time-range-breakout-review-free-forex-ea-with-donation-option/)](https://forexroboteasy.com/forex-robot-review/time-range-breakout-review-free-forex-ea-with-donation-option/)

This code represents a trading algorithm known as Time Range Breakout, developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product.

## Product Description

Time Range Breakout is an automated trading system designed for the Forex market. It aims to take advantage of price breakouts that occur within a specific time range. By placing buy stop and sell stop orders, the algorithm attempts to capture potential profits when the price breaks out of the defined range.

### Input Parameters

- **volume**: The trading volume for each order. Default value is 0.01.
- **riskPercent**: The risk percentage for each trade. Default value is 2.0.
- **tpPoints**: The take profit in points. Default value is 100.
- **slPoints**: The stop loss in points. Default value is 50.
- **ti**: The time interval in minutes. Default value is 60.

### Global Variables

- **rangeHigh**: The range high price.
- **rangeLow**: The range low price.
- **ticketBuy**: The ticket number of the buy stop order.
- **ticketSell**: The ticket number of the sell stop order.

### Functions

1. **PlaceBuyStopOrder()**: Places a buy stop order at the range high price.
2. **PlaceSellStopOrder()**: Places a sell stop order at the range low price.
3. **AdjustTrailingStop()**: Adjusts the trailing stop for securing profits.
4. **CustomizeInputParameters()**: Handles user input parameter customization.
5. **HandleErrors()**: Handles errors during execution.
6. **OptimizeCode()**: Optimizes the code for efficient performance.
7. **OnTick()**: The main trading algorithm that executes every 'ti' minutes.
8. **OnStart()**: Handles MetaTrader 5 compatibility and customizes input parameters.
9. **OnDeinit(const int reason)**: Handles logical conclusion and smooth execution.

## Usage

To use this code, follow these steps:

1. Customize the input parameters through the user interface in the **CustomizeInputParameters()** function.
2. Optimize the code for efficient performance using the **OptimizeCode()** function.
3. Execute the algorithm by running the **OnTick()** function, which will place buy stop and sell stop orders within the defined time range.
4. The **AdjustTrailingStop()** function will adjust the trailing stop for securing profits.
5. Handle any errors during execution using the **HandleErrors()** function.
6. To conclude the algorithm, use the **OnDeinit(const int reason)** function.

Please note that this code is just a sample and should be further customized and tested before using it with real trading accounts. For more details, reviews, and trading results of this product, visit the [official developer's site](https://forexroboteasy.com/forex-robot-review/time-range-breakout-review-free-forex-ea-with-donation-option/).
