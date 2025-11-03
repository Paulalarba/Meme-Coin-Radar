# Meme-Coin-Radar
# 🪙 MemeCoin Radar

A **Next.js + React** web app that scans decentralized exchanges (DEXs) for **new meme coin listings**, filters them by liquidity and volume, and flags potential risks or early opportunities using contract safety checks and social buzz signals.

This is designed as a **research tool for blockchain enthusiasts and developers** who want to spot meme coins *early* and perform their own due diligence — not a trading bot or financial advice engine.

---

## 🚀 Features
- 📊 **DEX Pair Scanner** — Fetches new pairs from APIs like Dexscreener or Birdeye.
- 💧 **Filter by Liquidity & Volume** — Set your own thresholds to ignore low-quality launches.
- 🔍 **Contract Safety Check** — Integrates with blockchain scanners (Etherscan, BscScan, Solscan) to detect risks.
- 💬 **Social Buzz Tracker** — Pulls Twitter/X mentions for hype analysis.
- ⚙️ **Configurable Refresh Interval** — Automatically polls new tokens every few seconds.

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
