# Awesome Tokenized Stocks & RWA [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**The most comprehensive curated list of platforms, protocols, apps, data tools and resources for trading tokenized stocks, equities, commodities and real-world assets (RWAs) on-chain — 2026.**

> Tokenized stocks let you trade equity exposure (AAPL, TSLA, NVDA, SPX…), commodities (gold, oil) and other real-world assets 24/7, on-chain, without a traditional broker. This list tracks where and how — across Hyperliquid, Solana, Ethereum, Arbitrum, Base and more — plus the data, oracles, custody and compliance rails underneath.

> PRs welcome — see [Contributing](#-contributing). Neutral, no referral spam.

---

## Contents

- [What Are Tokenized Stocks & RWAs?](#-what-are-tokenized-stocks--rwas)
- [Tokenized Equity Issuers](#-tokenized-equity-issuers-backed-assets)
- [Stock & RWA Perps (Synthetic Exposure)](#-stock--rwa-perps-synthetic-exposure)
- [Tokenized Treasuries & Money Markets](#-tokenized-treasuries--money-markets)
- [Mobile Apps for Tokenized Stocks](#-mobile-apps-for-tokenized-stocks)
- [Pre-IPO & Private Markets](#-pre-ipo--private-markets)
- [Commodities On-Chain](#-commodities-on-chain)
- [Infrastructure: Issuance, Custody & Compliance](#-infrastructure-issuance-custody--compliance)
- [Oracles & Price Feeds](#-oracles--price-feeds)
- [Data, Analytics & Dashboards](#-data-analytics--dashboards)
- [Research & Reports](#-research--reports)
- [Communities](#-communities)
- [Contributing](#-contributing)
- [License](#-license)

> **Legend** — 🟢 Live · 🟡 Beta/Testnet/Regional · 🔴 Inactive · ⚡ High-volume · 🆕 Launched 2025/26

---

## 📖 What Are Tokenized Stocks & RWAs?

**Tokenized stocks** are on-chain instruments that track the price of a real equity. Two dominant models:

- **Backed / asset-backed tokens** — each token is 1:1 collateralized by the real share held by a regulated custodian (e.g. xStocks/Backed, Dinari, Swarm). You hold a claim on the underlying.
- **Synthetic / perpetual exposure** — a derivative (usually a perpetual future) tracks the equity price via an oracle, with no share held (e.g. trade.xyz on Hyperliquid, Ostium, Gains Network). Capital-efficient, leverage-capable, 24/7.

**RWAs (real-world assets)** extend this to treasuries, credit, commodities and more. The appeal: 24/7 markets, global access, self-custody, and composability with DeFi.

> ⚠️ Availability and legality vary by jurisdiction. Many issuers geo-restrict (no US persons). This list is informational; nothing here is financial or legal advice.

---

## 🏦 Tokenized Equity Issuers (Backed Assets)

Issuers that mint 1:1 asset-backed equity tokens, custodied by a regulated entity.

| Project | Model | Chains | Notable | Status | Link |
| --- | --- | --- | --- | --- | --- |
| **xStocks (Backed Finance)** ⚡ | 1:1 backed | Solana, Ethereum | 60+ US stocks & ETFs as -x tokens; Liechtenstein FMA prospectus; >$10B volume in 6 months; Kraken agreed to acquire Backed (Dec 2025) | 🟢 Live | [xstocks.com](https://xstocks.com/) |
| **Ondo Global Markets** ⚡ | 1:1 backed | Ethereum, Solana, Ondo Chain | 100+ tokenized US equities (launched Sep 2025); one of the largest tokenized-equity platforms | 🟢 Live | [ondo.finance](https://ondo.finance/) |
| **Robinhood Stock Tokens** | 1:1 backed | Robinhood Chain (Arbitrum Orbit) | 200+ US stocks & ETFs incl. pre-IPO; live on Robinhood Chain since Jul 2026, 120+ jurisdictions | 🟢 Live | [robinhood.com](https://robinhood.com/) |
| **Dinari (dShares)** | 1:1 backed | Ethereum, Arbitrum, Base | SEC-registered transfer agent + broker-dealer; dividend-paying dShares; US-accredited + non-US; tZERO partnership (2026) | 🟢 Live | [dinari.com](https://dinari.com/) |
| **Swarm** | 1:1 backed | Polygon, Ethereum | Regulated (BaFin) tokenized stocks & bonds | 🟢 Live | [swarm.com](https://swarm.com/) |
| **Backed Finance** | Issuer/infra | Multi-chain | The issuance layer behind xStocks and many bStocks | 🟢 Live | [backed.fi](https://backed.fi/) |
| **Securitize** | Issuer/infra | Multi-chain | Tokenized funds (e.g. BlackRock BUIDL) and equities | 🟢 Live | [securitize.io](https://securitize.io/) |

---

## 📈 Stock & RWA Perps (Synthetic Exposure)

Trade equity/commodity price exposure as perpetual futures — leverage, 24/7, no share held.

| Project | Markets | Chain | Notable | Status | Link |
| --- | --- | --- | --- | --- | --- |
| **trade.xyz** ⚡ | Stocks (AAPL, TSLA, NVDA), S&P 500, oil, gold, silver | Hyperliquid L1 (HIP-3) | Perps arm of Unit; first HIP-3 deployment (Oct 2025); ~90% of all HIP-3 open interest | 🟢 Live | [trade.xyz](https://trade.xyz/) |
| **Ostium** ⚡ | SPX, NDX, FX, oil, gold, single stocks | Arbitrum | RWA + crypto perps, up to 200x | 🟢 Live | [ostium.app](https://ostium.app/) |
| **Gains Network (gTrade)** | FX, equities, commodities, crypto | Polygon, Arbitrum, Base | 150x on stocks/forex via gToken vaults | 🟢 Live | [gains.trade](https://gains.trade/) |
| **Helix (Injective)** | iAssets — tokenized stocks & RWA perps | Injective | On-chain orderbook for RWA perps | 🟢 Live | [helixapp.com](https://helixapp.com/) |
| **Synthetix** | Synths (historically sEquities) | Optimism, Base | Debt-pool synthetics powering multiple frontends | 🟢 Live | [synthetix.io](https://synthetix.io/) |

---

## 💵 Tokenized Treasuries & Money Markets

On-chain US treasuries and yield-bearing cash equivalents.

| Project | Product | Chains | Status | Link |
| --- | --- | --- | --- | --- |
| **Ondo Finance** | OUSG, USDY (tokenized treasuries) | Ethereum, Solana, others | 🟢 Live | [ondo.finance](https://ondo.finance/) |
| **BlackRock BUIDL** (via Securitize) | Tokenized money market fund | Ethereum, multi-chain | 🟢 Live | [securitize.io](https://securitize.io/) |
| **Franklin Templeton BENJI** | Tokenized US Gov money fund | Multi-chain | 🟢 Live | [franklintempleton.com](https://www.franklintempleton.com/) |
| **Superstate** | Short-duration treasury fund (USTB) | Ethereum, Solana | 🟢 Live | [superstate.com](https://superstate.com/) |
| **OpenEden** | T-Bill vault (TBILL) | Multi-chain | 🟢 Live | [openeden.com](https://openeden.com/) |

---

## 📱 Mobile Apps for Tokenized Stocks

Self-custodial apps to trade tokenized stocks & RWAs from your phone.

| App | Platform | Coverage | Notable | Status | Link |
| --- | --- | --- | --- | --- | --- |
| **Dexly** | iOS / Android | Hyperliquid | Self-custodial app for perps, spot, **tokenized stocks & commodities**, and prediction markets, with copy trading | 🟢 Live | [dexly.trade](https://dexly.trade/) |
| **Robinhood (EU)** | iOS / Android | Arbitrum | Tokenized US stocks & pre-IPO for EU users | 🟡 Regional | [robinhood.com](https://robinhood.com/) |
| **Kraken (xStocks)** | iOS / Android / Web | Solana | Trade xStocks tokenized equities | 🟢 Live | [kraken.com](https://www.kraken.com/) |

> Building a tokenized-stocks app? Open a PR to add it here.

---

## 🚀 Pre-IPO & Private Markets

On-chain exposure to pre-IPO / private companies.

| Project | Markets | Chain | Status | Link |
| --- | --- | --- | --- | --- |
| **Ventuals** | Pre-IPO equity perps (OpenAI, SpaceX, Anthropic…) | Hyperliquid L1 (HIP-3) | 🟢 Live | [ventuals.com](https://ventuals.com/) |
| **Robinhood (pre-IPO tokens)** | Tokenized pre-IPO exposure | Robinhood Chain | 🟢 Live | [robinhood.com](https://robinhood.com/) |
| **Republic** | Tokenized private-company notes | Multi-chain | 🟢 Live | [republic.com](https://republic.com/) |

---

## 🛢️ Commodities On-Chain

| Project | Markets | Chain | Status | Link |
| --- | --- | --- | --- | --- |
| **trade.xyz** | Gold, silver, oil (perps) | Hyperliquid L1 | 🟢 Live | [trade.xyz](https://trade.xyz/) |
| **Ostium** | Gold, oil, and more | Arbitrum | 🟢 Live | [ostium.app](https://ostium.app/) |
| **Paxos Gold (PAXG)** | Gold-backed token | Ethereum | 🟢 Live | [paxos.com](https://paxos.com/paxgold/) |
| **Tether Gold (XAUt)** | Gold-backed token | Ethereum, Tron | 🟢 Live | [gold.tether.to](https://gold.tether.to/) |

---

## 🏗️ Infrastructure: Issuance, Custody & Compliance

The rails under tokenized RWAs — issuance platforms, custody, transfer agents, KYC/compliance.

- [**Backed Finance**](https://backed.fi/) — Issuance layer for asset-backed tokens (bTokens, xStocks).
- [**Securitize**](https://securitize.io/) — Tokenization + registered transfer agent (BUIDL and more).
- [**Dinari**](https://dinari.com/) — SEC-registered transfer agent infrastructure for tokenized equities.
- [**Ondo Global Markets / Ondo Chain**](https://ondo.finance/) — RWA-focused issuance and settlement layer.
- [**Fireblocks**](https://www.fireblocks.com/) — Institutional custody & MPC key management.
- [**Chainalysis**](https://www.chainalysis.com/) — Compliance/AML screening used across RWA venues.

---

## 🔮 Oracles & Price Feeds

RWA perps and synthetics rely on high-quality equity/commodity price feeds.

- [**Pyth Network**](https://pyth.network/) — Sub-second equity, FX and commodity feeds (used by Ostium, trade.xyz-class venues).
- [**Chainlink Data Feeds / Data Streams**](https://chain.link/) — Decentralized price feeds incl. equities and commodities.
- [**Stork**](https://stork.network/) — Low-latency oracle for RWA & perp DEXs.
- [**RedStone**](https://www.redstone.finance/) — Modular oracle with RWA coverage.

---

## 📊 Data, Analytics & Dashboards

- [**DefiLlama — RWA**](https://defillama.com/protocols/RWA) — Canonical TVL/volume tracking for the RWA category.
- [**rwa.xyz**](https://www.rwa.xyz/) — The reference dashboard for tokenized RWAs (treasuries, credit, stocks).
- [**Dune — RWA dashboards**](https://dune.com/) — Community dashboards for tokenized-asset flows.
- [**Artemis**](https://artemis.xyz/) — Cross-chain analytics including RWA sectors.
- [**Tokenized**](https://tokenized.so/) — Research directory comparing tokenized stocks, stablecoins and commodities by underlying asset, issuer, backing model and network, with links to issuer sources.
- [**RWA Space**](https://rwaspace.app/) — Research terminal and catalog connecting underlying assets, tokenized issuances, observed markets, source documents, and pricing methodology.

---

## 📚 Research & Reports

- [**rwa.xyz Research**](https://www.rwa.xyz/) — Market data and category breakdowns.
- [**Messari — RWA sector**](https://messari.io/) — Research on tokenized assets and issuers.
- [**Binance Research — Tokenization**](https://research.binance.com/) — Market reports on RWA/tokenized stocks.
- [**a16z crypto — Tokenization**](https://a16zcrypto.com/) — Long-form on the tokenization thesis.

---

## 💬 Communities

- [**r/defi**](https://reddit.com/r/defi) — DeFi + RWA discussion.
- [**Hyperliquid Discord**](https://discord.gg/hyperliquid) — Home of HIP-3 stock/commodity markets.
- [**RWA-focused Telegram/X lists**](https://x.com/) — Follow rwa.xyz, Ondo, Backed, Ostium for updates.

---

## 🤝 Contributing

PRs welcome — the tokenized-stocks / RWA space ships fast.

1. **Fork** and create a feature branch (e.g. `feature/add-foo`).
2. **Match the column structure** of the section you're editing.
3. **Quality bar:** live (or clearly-marked beta), working website, genuinely offers tokenized-equity / RWA exposure or directly serves those traders.
4. **One row per project.** Use the legend (🟢 / 🟡 / 🔴 / ⚡ / 🆕) consistently.
5. **No referral spam.** Neutral descriptions; disclose affiliations.

For corrections (broken links, inactive projects), open an issue or a small PR.

---

## 📄 License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Made for the on-chain RWA community.

---

> **Maintainer note:** This list is maintained by the team behind [Dexly](https://dexly.trade/) (Hyper Lion LTD). Dexly is listed among many tokenized-stock venues; the goal is a genuinely useful, neutral directory of the whole category. Suggestions and competing projects are welcome via PR.
