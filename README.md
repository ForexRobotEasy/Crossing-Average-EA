# Crossing Average EA ReadMe File

## Description
This is a sample code for the Crossing Average EA, which is an Expert Advisor used in automated trading on the MetaTrader 5 platform. The Crossing Average EA generates buy and sell signals based on the crossing of two moving averages. It opens market orders at the next candle open after a signal is generated.

This code is provided as a reference and it is not the official product developed by Forex Robot Easy Team. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, you can visit the following link: [Crossing Average EA Review - Optimal Forex Software with Unique Signals](https://forexroboteasy.com/forex-robot-review/crossing-average-ea-review-optimal-forex-software-with-unique-signals/)

## Input Parameters
- FastMA_Period: The period for the fast-moving average (default: 10)
- SlowMA_Period: The period for the slow-moving average (default: 20)
- MagicNumber: Unique identifier for orders (default: 123456)
- LotSize: The lot size for market orders (default: 0.1)

## How it Works
1. The Expert Advisor initializes by setting the necessary moving average periods.
2. On each tick, it checks for the crossing of the moving averages.
3. If a crossing is detected, it generates a buy or sell signal based on the direction of the crossing.
4. It executes a market order at the next candle open after the signal is generated.
5. The signal variable is reset after the order is executed.

## Functions
- OnInit(): Initializes the Expert Advisor and sets the moving average periods.
- OnDeinit(): Deinitializes the Expert Advisor.
- OnTick(): Executes the main logic of the Expert Advisor, checking for crossing and generating signals.
- FastMovingAverage(): Calculates the value of the fast-moving average.
- SlowMovingAverage(): Calculates the value of the slow-moving average.
- CrossingAverages(): Generates buy and sell signals based on the crossing of moving averages.
- ExecuteMarketOrder(): Executes market orders at the next candle open after a signal is generated.

## Disclaimer
This code is provided as a sample and is not the official product developed by Forex Robot Easy Team. It serves as a reference for how the Crossing Average EA can work. For the official developer and more information about this product, please use MQL5.

For detailed reviews and trading results of this product, please visit the official review page: [Crossing Average EA Review - Optimal Forex Software with Unique Signals](https://forexroboteasy.com/forex-robot-review/crossing-average-ea-review-optimal-forex-software-with-unique-signals/)
