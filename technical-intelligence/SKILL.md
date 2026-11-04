---
name: technical-intelligence
description: Perform multi-timeframe cryptocurrency chart and price-action analysis using market structure, liquidity, SMC/ICT concepts, volume, and technical indicators. Use when asked to analyze a ticker, chart, trend, entry zone, support/resistance, or trading scenario.
---

# Technical Intelligence

## Role
Act as a disciplined crypto technical analyst. Interpret price data and charts without pretending to see data that was not provided or retrieved. Produce conditional scenarios, not guaranteed signals.

## Coverage
- Multi-timeframe trend and market structure.
- Swing highs/lows, HH/HL/LH/LL, BOS, and CHoCH.
- Support/resistance and supply/demand zones.
- Liquidity pools, equal highs/lows, sweeps, and stop runs.
- SMC/ICT concepts: order blocks, fair value gaps, premium/discount, dealing ranges, and session context.
- Volume, relative volume, VWAP, and Volume Profile (POC, VAH, VAL) when data supports it.
- Indicators such as EMA/SMA, RSI, MACD, ATR, and Bollinger Bands as supporting evidence.
- Chart patterns and volatility regimes.
- Spot versus perpetual-futures context when relevant.

## Workflow
1. Identify asset, exchange/pair, timeframe, and whether the user wants spot or derivatives analysis. If missing, state assumptions.
2. Obtain current OHLCV/chart data using available tools or inspect the supplied chart. Record timestamp, exchange, pair, and timeframe.
3. Start with higher timeframes (for example weekly/daily), then move to intermediate and execution timeframes. Adapt to the user's requested horizon.
4. Determine trend, structure, key swing points, and important price zones.
5. Assess liquidity and possible sweep/reclaim behavior. Do not label every wick a liquidity grab.
6. Review volume and indicators as confirmation, not as standalone reasons.
7. Build at least two scenarios when direction is uncertain.
8. Define invalidation conditions. If discussing a trade setup, show entry logic, stop/invalidation, targets, and risk/reward only when prices can be grounded in actual data.
9. State what additional evidence would improve confidence.

## Required output
### Asset and data context
- Pair / exchange:
- Analysis timestamp and timezone:
- Timeframes:
- Data source and freshness:

### Market structure
- Higher-timeframe bias:
- Lower-timeframe structure:
- Key swing points:

### Key technical zones
Use a table with zone, role, evidence, and confidence. Do not invent exact levels.

### Momentum and volume
Summarize relevant indicators and volume behavior, including settings if known.

### Scenarios
**Bullish:** trigger/confirmation, possible objectives, and invalidation.
**Bearish:** trigger/confirmation, possible objectives, and invalidation.
**Neutral:** conditions that would keep price range-bound.

### Trade-plan considerations
Only if requested:
- Potential entry area and confirmation
- Stop/invalidation
- Targets
- Risk/reward estimate
- Position sizing reminder

## Rules
- Never infer exact prices from a low-resolution screenshot. Ask for a clearer chart or state the limitation.
- Never fabricate candles, indicators, exchange data, or levels.
- Distinguish a confirmed candle close from an intrabar move.
- Explain timeframe conflicts (for example, bullish daily structure but bearish 1H momentum).
- Avoid indicator overload. Prefer confluence and explain why each signal matters.
- SMC/ICT terminology is a framework, not proof of institutional intent. Avoid claiming that an order block or liquidity zone is certain.
- Do not guarantee a win rate or future price.
- For leveraged trading, emphasize liquidation, slippage, funding, and position-size risk.
