# FINOVA Quant & Trading Committee: 20/50 EMA Crossover Strategy

## Overview

The task given tests a simple 20/50 EMA crossover strategy on Reliance
Industries Limited (RELIANCE) using a 1D (daily) chart on TradingView.

Entry: When the 20-day EMA crosses above the 50-day EMA.

Exit: When the 20-day EMA crosses back below the 50-day EMA.

Testing period: The last 12 months (04-09-25 to 03-09-26)

Instrument: **Reliance Industries Limited (NSE: Reliance)**

## Trade Results

| Trade No. | Entry Date | Entry Price | Exit Date | Exit Price | P/L % |
|---|---|---:|---|---:|---:|
| 1 | 21-10-2025 | 1465.2 | 16-01-2026 | 1457.9 | -0.50% |
| 2 | 07-05-2026 | 1436.2 | 13-05-2026 | 1358.8 | -5.39% |

## Summary

Total trades: 2

Number of winners: 0

Win rate: 0%

Largest single winner: N/A

Largest single loser: -5.39%

## Method

I used TradingView with the 1D timeframe and added two Exponential
Moving Averages (EMAs), one with a length of 20 and the other with a
length of 50. I went through the 12-month chart and recorded each
full trade from upward crossover of the 20 EMA to the next
downward crossover.

The profit/loss percentage for each trade was calculated using:

*P/L % = ((Exit Price - Entry Price) / Entry Price) × 100*

## Verdict

RELIANCE | 2 | 0% | I would not trade this strategy with my own
money based on this test alone.

Both trades in my test showed losses, and the second trade had a large 
loss of 5.39%. The strategy looks simple and easy to follow, but I think 
it is too dependent on the EMAs confirming a trend after it has already 
started. Also, only having two trades means the sample is too small to 
confidently say that the strategy is reliable so I wouldn't really trade 
my money with this alone.

I think this strategy would work better in a market with a clear and 
sustained trend, because the EMAs can follow the direction of the price.
It would probably perform poorly in a sideways or rough market, where
the two EMAs can cross repeatedly and create trades that do not develop
into strong trends. Based on these results, I would want to test it over
a much longer period and possibly add risk management or another
confirmation before using real money.

## Files

Screenshots: Three TradingView screenshots:

- Full 12-month chart with both EMAs

- Best trade (Trade 1)

- Worst trade (Trade 2)


*trade_log_table_finova_task.xlsx->* Excel file containing the trade entries and
calculations.
