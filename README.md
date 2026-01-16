# trading-scripts

### TradingView indicators (Pine Script v5) 

---

### Range Breakout Candles with Pullback Detection

Pine Script v5 indicator grouping candles into breakout candles (new high/low) and detecting pullbacks in local trend (up/down based on 2 candles).

**Key Features:**
- Breakout Candles: Visual candles consolidating range until high/low breakout
- Pullback Detection:
  - Green circles (uptrend): close below ref low
  - Red circles (downtrend): close above ref high
  - Yellow diamonds: Bullish Engulfing Pullback
  - Orange diamonds: Bearish Engulfing Pullback
- Ref Levels: Optional high/low lines (toggle)

**Usage:** Enter on pullbacks in breakout trend direction. Works on crypto/forex, 1H-1D timeframes. Fixed flags and arrays for realtime stability.


### Block of Candles (BoC)

Indicator groups consecutive candles into a single “block of candles” (BoC) to highlight consolidation zones and their eventual breakouts on any timeframe.
It merges candles while price stays inside a reference range, counts block length and volume, and closes a block only when price breaks above/below the range, 
optionally drawing mitigation zones for future retests. It also offers MTF view, stats table (avg length, range, bullish/bearish breaks) and alerts for block close, directional breakout and long consolidations.

**Usage:**
- Identify consolidation blocks where price is absorbed in a tight range before a strong move.
- Use closed bullish blocks and their mitigation zones as potential demand areas for long entries on retests.
- Use closed bearish blocks and their mitigation zones as potential supply areas for short entries on retests.
- Filter signals by minimum candles in block, minimum range % and volume spike to keep only meaningful consolidations.
- Combine LTF BoC with HTF BoC (MTF mode) to trade in the direction of higher‑timeframe structure.
- Set alerts for block close, bullish/bearish breakout or long blocks to automate monitoring of consolidation and breakout conditions.

**Note:** Blocks with a higher candle count typically represent stronger consolidation zones with better-tested levels, making their mitigation zones more significant for entries. Consider using block length as a scoring/weighting factor when prioritizing setups.
