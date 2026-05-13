# Crypto Market Pulse Skill

Produce a macro crypto market overview using live onchain data across the five core signal categories: stablecoin supply, DEX volume, chain fees, CEX flows, and perp open interest. Render as a single-page HTML artifact matching the design system below.


## Timeframe Toggle

The output always shows three timeframes: **1D**, **7D**, **30D**.

For each signal category, show the delta for each window:
- 1D = yesterday vs today
- 7D = week-over-week
- 30D = month-over-month

If 1D data isn't available for a metric, show "—" rather than fabricating it.


## Step 2: Synthesise the Headline

Before rendering, write one 2-3 sentence headline insight that captures the single most important macro signal from the data. This goes at the top in a highlighted box. It should be specific and data-backed, not generic.

Good: *"Trading rebounded sharply without a corresponding fiat influx. Spot DEX volume jumped 43% WoW and Hyperliquid perp volume rose 33%, but the four major stablecoin issuers added only $0.3B of supply — trading is recycling existing dollars, not new ones."*

Bad: *"Crypto markets showed mixed signals this week with some areas of strength."*


## Tone

Same as token-research: institutional sell-side analyst voice.
- Specific and data-backed
- Acknowledge what the data can't tell you ("stablecoin supply did not expand to match — trading is recycling existing dollars, not new ones")
- No hype, no retail newsletter language

