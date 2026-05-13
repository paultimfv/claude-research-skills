# claude-research-skills

# Claude Research Skills

Institutional-quality crypto research, generated in Claude. Two skills built on equity-style valuation frameworks — the same approach used by onchain research teams at firms like Allium.

---

## Skills

### `token-research` — Token Tear Sheet & Investment Memo

Drop a token name, get a fully structured tear sheet or investment memo. Pulls live data from DeFiLlama, Token Terminal, and CoinGecko, runs a two-stage DCF, builds a comps table, generates scenario targets (bear / base / bull / probability-weighted), maps risks and catalysts. Rendered as a styled HTML artifact directly in Claude chat.

**Trigger with:**

"tear sheet on HYPE"
"investment memo on SOL"
"bull case for ARB"
"is AAVE overvalued?"
"analyze (any token)" 

### `crypto-pulse` — Macro Market Pulse

Weekly onchain market overview across five signal categories: stablecoin supply, spot DEX volume, Hyperliquid perp volume, chain fees, and CEX flows. Includes a 1D / 7D / 30D timeframe toggle, four stacked bar charts by chain, and a What to Watch synthesis section.

**Trigger with:**

"crypto market pulse"
"what's happening onchain this week?"
"macro crypto overview"
"give me a market update"


## Installation

1. Download the `.skill` file for whichever skill you want
2. Go to [claude.ai](https://claude.ai) → Settings → Skills
3. Click **Add Skill** → upload the `.skill` file
4. Start a new chat and use one of the trigger prompts above

> Requires Claude Pro, Max, Team, or Enterprise.

---

## Data Sources

No API keys required. Skills pull live data via Claude's web search from:
- [DeFiLlama](https://defillama.com) — fees, TVL, DEX volume
- [Token Terminal](https://tokenterminal.com) — protocol revenue, comps
- [CoinGecko](https://coingecko.com) — price, supply, market cap
- [Tokenomist](https://tokenomist.ai) — unlock schedules


---

Built by https://x.com/paultimofeev_ 
