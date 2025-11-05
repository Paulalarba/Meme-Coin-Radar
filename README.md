# 🪙 MemeCoin Radar

A **Next.js + React** web app that scans decentralized exchanges (DEXs) for **new meme coin listings**, filters them by liquidity and volume, and flags potential risks or early opportunities using contract safety checks and social buzz signals.

This is designed as a **research tool for blockchain enthusiasts and developers** who want to spot meme coins *early* and perform their own due diligence — not a trading bot or financial advice engine.

---

## 🚀 Features
### 🧭 Core Scanning
- 📊 **DEX Pair Scanner** — Fetches new pairs from APIs like Dexscreener or Birdeye.
- 💧 **Liquidity & Volume Filters** — Adjustable thresholds to screen quality launches.
- ⏱️ **Real-Time Updates** — Auto-refreshes to catch coins right after deployment.
- 🔍 **Multi-Chain Support** — Works with Ethereum, BSC, Solana, and Base.

### 🧠 Analysis & Research Tools
- 🛡️ **Smart Contract Safety Audit** — Scans for blacklist, mint, or ownership risks.
- 🧾 **Holder Distribution Tracker** — Checks top wallet holdings & whale concentration.
- 🧩 **Tax Analyzer** — Detects buy/sell tax rates to avoid honeytraps.
- 📜 **Dev History Checker** — Uses blockchain explorers to detect reused wallets or rug histories.

### 📢 Social & Market Sentiment
- 💬 **Twitter/X Mentions Tracker** — Pulls real-time social buzz for trending tokens.
- 📈 **Hype Momentum Score** — Combines volume, holder growth, and tweets for ranking.
- 🧠 **Community Health Meter** — Detects spam or bot-heavy Telegram activity.

### 🔔 Alerts & Integrations
- 📢 **Discord/Telegram Alerts** — Get pings for new high-potential launches.
- 📬 **Email Summaries** — Daily digest of top early meme coins.
- 🔗 **Wallet Tracking** — Follow specific dev or influencer wallets across chains.
- 💻 **Custom Webhooks** — Integrate alerts with your own trading scripts (non-automated).

---

## 🧰 Example Filters
| Filter | Default | Description |
|---------|----------|--------------|
| `minLiquidity` | $5,000 | Minimum liquidity threshold |
| `minVolume` | $1,000 | Minimum daily volume threshold |
| `refreshInterval` | 30s | Data refresh rate |

---

## 🛡️ Security & Ethics
This tool is **for educational purposes only**. Always DYOR (Do Your Own Research). Don’t deploy auto-trading scripts or promote unverified tokens. The author is not responsible for financial losses.

---

## 🧩 Roadmap
- [ ] Add Dexscreener & Birdeye API integration
- [ ] Add real contract safety scanning (Etherscan/Solscan)
- [ ] Add social signals from X (Twitter API)
- [ ] Implement caching & server API routes
- [ ] Add Telegram/Discord alert system
- [ ] Deploy on Vercel with ENV variables

---

## 🧑‍💻 Author
**Paul** — 3rd year IT student specializing in Blockchain Development.

*“If it doesn’t feel right on-chain, it isn’t right off-chain either.”*

---

## 🧾 License
MIT License — Free to use, modify, and share. Just credit the author and don’t use this for malicious or deceptive projects.
