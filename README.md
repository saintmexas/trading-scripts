# trading-scripts
My Pine Script Ideas
Range Breakout Candles with Pullback Detection - Fixed

Pine Script v5 indicator grouping candles into breakout candles (new high/low) and detecting pullbacks in local trend (up/down based on 2 candles).​

Key Features:
Breakout Candles: Visual candles consolidating range until high/low breakout​

Pullback Detection:
Green circles (uptrend): close below ref low
Red circles (downtrend): close above ref high
Yellow diamonds: Bullish Engulfing Pullback
Orange diamonds: Bearish Engulfing Pullback​
Ref Levels: Optional high/low lines (toggle)​

Usage: Enter on pullbacks in breakout trend direction. Works on crypto/forex, 1H-1D timeframes. Fixed flags and arrays for realtime stability.
