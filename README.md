# claude-research-skills

# Claude Research Skills

Institutional-quality crypto research built on equity-style valuation frameworks, generated in Claude. 

---

## Skills

### `token-research` — Token Tear Sheet & Investment Memo

Drop a token name, get a fully structured tear sheet or investment memo. Pulls live data from DeFiLlama, Token Terminal, and CoinGecko, runs a two-stage DCF, builds a comps table, generates scenario targets (bear / base / bull / probability-weighted), maps risks and catalysts. Rendered as a styled HTML artifact directly in Claude chat.

**prompt examples:**

"tear sheet on HYPE"
"investment memo on SOL"
"bull case for ARB"
"is AAVE overvalued?"
"analyze (any token)" 


### `crypto-pulse` — Macro Market Pulse

Weekly onchain market overview across five signal categories: stablecoin supply, spot DEX volume, Hyperliquid perp volume, chain fees, and CEX flows. Includes a 1D / 7D / 30D timeframe toggle, four stacked bar charts by chain, and a What to Watch synthesis section.

**Prompt examples**

"crypto market pulse"
"what's happening onchain this week?"
"macro crypto overview"
"give me a market update"

## more prompt examples
See `test-prompts.md` for a full list of prompts to try with each skill.

## Installation

**Option A — One click (recommended):**
1. Download the `.skill` file for whichever skill you want
2. Go to [claude.ai](https://claude.ai) → Settings → Skills → **Add Skill**
3. Upload the `.skill` file
4. Start a new chat and use one of the trigger prompts above

**Option B — Read first, then install:**
1. Open the `SKILL.md` file to read what it does
2. Copy the raw text
3. Go to [claude.ai](https://claude.ai) → Settings → Skills → **Add Skill** → paste

---

## Data Sources

No API keys required. Skills pull live data via Claude's web search from:
- [DeFiLlama](https://defillama.com) — fees, TVL, DEX volume
- [Token Terminal](https://tokenterminal.com) — protocol revenue, comps
- [CoinGecko](https://coingecko.com) — price, supply, market cap
- [Tokenomist](https://tokenomist.ai) — unlock schedules


---

Built by [@paultimofeev_](https://x.com/paultimofeev_)
