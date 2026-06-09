# Chapter 1 -  A Really Brief History of Financial Trading

## Main Idea
Trading in a way that is very much like today has been present since 1602 with the Dutch East-Company selling shares, it moved to shout out loud and handsignals ans then one of the biggests changes was in the 1970s with the introduction of digitalising the market, many companies making and profitting off of their own digital systems to make digital trades such  as Bloomsburg, this then lead to the formation of the New York Stock Exchange (NYSE) in the 80s and since then now there is an emphasis on getting news of changes in milliseconds, some companies even pay millions on millions for low-latency space in which they want their servers to be in the same room as NYSE servers because it can give them a millisecond heads up, lastly it talks about how social media has been used as a way to share information about stocks, this led to the SEC to place restrictionsin 2013, prohibitting Public Companies from making announcements on social media. An interesting note was also that whenever Donald Trump tweets frequently the Stock Exchange shows a negative return.

## Key Concepts
- Mean reversion
- Entry signals
- Exit signals
- Risk management

## New Terms
- Z-score
- Standard deviation

## Why Might This Work?
Traders overreact to information.

## How Would I Code It?
1. Calculate moving average
2. Calculate deviation from average
3. Buy when deviation exceeds threshold
4. Sell when price returns to average

## Data Required
- Historical prices
- Volume data

## Risks
- Trend markets may break the strategy

## Questions
- How should the threshold be chosen?
- What lookback period is best?

## Next Action
Build a simple backtest in Python.
