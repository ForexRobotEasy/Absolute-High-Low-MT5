# Absolute High Low MT5 ReadMe File

This code is for the 'Absolute High Low MT5' indicator, developed by the Forex Robot Easy Team. This indicator calculates the highest and lowest points in a specified time frame and displays them as lines on the chart.

## Indicator Input Parameters
- `timeFrame`: Time frame for calculating the high and low points. Default is PERIOD_H1 (1 hour).
- `sensitivity`: Sensitivity for identifying extreme points. Default is 10.

## Global Variables
- `highest`: Holds the highest points calculated by the indicator.
- `lowest`: Holds the lowest points calculated by the indicator.

## Initialization Function
The `OnInit()` function is responsible for initializing the custom indicator. It sets the indicator name, style, and buffers for drawing the highest and lowest lines.

## Iteration Function
The `OnCalculate()` function is called on each new tick or bar to calculate the highest and lowest points. It uses the `iHighest()` and `iLowest()` functions to find the extreme points based on the input parameters. The highest and lowest points are then stored in the `highest` and `lowest` arrays.

### Product Description

The 'Absolute High Low MT5' indicator is a powerful tool for identifying the highest and lowest points in a specified time frame. It provides traders with valuable information about price extremes, which can be used for various trading strategies.

Key Features:
- Calculates the highest and lowest points in the specified time frame.
- Displays the highest and lowest lines on the chart for easy visualization.
- Customizable input parameters for adjusting the time frame and sensitivity.

This product is developed by the Forex Robot Easy Team and is available for review and trading results on [Forex Robot Easy - Absolute High Low MT5 Review](https://forexroboteasy.com/forex-robot-review/absolute-high-low-mt5-review-optimize-for-real-results/). Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer and obtain the complete product, please use MQL5.

For more information and support, please visit [Forex Robot Easy](https://www.forexroboteasy.com).
