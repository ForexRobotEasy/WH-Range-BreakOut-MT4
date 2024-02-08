# WH Range BreakOut MT4

This code is a sample implementation of the WH Range BreakOut strategy for the MetaTrader 4 (MT4) platform. It is provided by Forex Robot Easy, a website that offers unbiased reviews and analysis of various Forex software, including the WH Range BreakOut MT4.

To fully understand how this code works, it is recommended to refer to the detailed reviews and trading results of the WH Range BreakOut MT4 on Forex Robot Easy's website [here](https://forexroboteasy.com/forex-robot-review/wh-range-breakout-mt4-review-unbiased-forex-software-analysis/).

**Disclaimer:** ForexRobotEasy is not the official developer of this product. This code is merely a sample implementation that can work as described in the WH Range BreakOut MT4. To find the official developer of this product, it is recommended to use the MQL5 platform.

## Functions

### GetPreviousDayHigh()

This function is used to retrieve the previous day's high level. It is expected that the developer adds their own code to retrieve this information. The function returns the previous day's high level.

### GetPreviousDayLow()

This function is used to retrieve the previous day's low level. Similar to the previous function, the developer needs to add their own code to retrieve this information. The function returns the previous day's low level.

### IdentifyBreakoutLevels(double high, double low)

This function is responsible for identifying and highlighting potential breakout levels based on the provided high and low levels. The breakout levels are calculated using a formula that takes into account the difference between the high and low levels. The calculated breakout levels are then displayed using the `Print()` function.

### DisplayBreakoutLevels()

This function serves as the user interface to display the highlighted breakout levels and provide a clear plan of action. It first retrieves the previous day's high and low levels using the `GetPreviousDayHigh()` and `GetPreviousDayLow()` functions. It then calls the `IdentifyBreakoutLevels()` function to identify and highlight the potential breakout levels. Additional code can be added to display the breakout levels on the user interface. Lastly, it provides traders with a clear plan of action based on the highlighted breakout levels using the `Print()` function.

### LondonBreakoutStrategy()

This function implements the 'London Breakout Strategy'. It starts by retrieving the previous day's high and low levels using the `GetPreviousDayHigh()` and `GetPreviousDayLow()` functions. It then calls the `IdentifyBreakoutLevels()` function to identify and highlight the potential breakout levels. The developer can add their own code to implement the 'London Breakout Strategy'. In the provided code, there are conditional statements that check if the price is above `breakoutLevel3` or below `breakoutLevel1`. Based on these conditions, the developer can add their own code to execute buy or sell trades.

### OptimizeCode()

This function is used for code optimization to ensure smooth operation on the MT4 platform. The developer can add their own code optimization techniques in this function.

### OnTick()

This is the main function that is executed on each tick of the MT4 platform. It runs the `LondonBreakoutStrategy()` function to implement the 'London Breakout Strategy' and then calls the `OptimizeCode()` function for code optimization.

Please note that this ReadMe file provides an overview of the code and its functions. For detailed reviews and trading results of the WH Range BreakOut MT4, please refer to [Forex Robot Easy's website](https://forexroboteasy.com/forex-robot-review/wh-range-breakout-mt4-review-unbiased-forex-software-analysis/).
