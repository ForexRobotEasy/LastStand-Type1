# LastStand Type1 Forex Software

This is the code for the LastStand Type1 Forex Software, developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/laststand-type1-forex-software-review-optimized-for-eurcad-h1-trading/).

## Description

The LastStand Type1 Forex Software is an automated trading system designed to trade the EURCAD currency pair on the H1 timeframe. It utilizes the Ichimoku and Heiken Ashi indicators to determine trade entry and exit points.

## How it Works

1. The necessary libraries are included: Trade.mqh, Ichimoku.mqh, and HeikenAshi.mqh.
2. Input parameters are defined, including the lot size for each trade and the closing method.
3. A unique identifier, called magic number, is defined for each trade.
4. The trade object is initialized.
5. The Ichimoku and Heiken Ashi indicators are initialized.
6. The OnTick function is executed on each tick of the market.
7. If there is no open position for the symbol and magic number, the Ichimoku and Heiken Ashi indicators are calculated.
8. The last calculated values of the Ichimoku and Heiken Ashi indicators are obtained.
9. If the conditions are met for opening a trade (Ichimoku value is greater than the Heiken Ashi open and close values), a buy trade is opened. If the conditions are met for opening a sell trade (Ichimoku value is less than the Heiken Ashi open and close values), a sell trade is opened.
10. If there is an open position, the conditions are checked for closing the trade.
11. If the closing method is set to TP-SL-TSL, the trade is closed using this method.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
