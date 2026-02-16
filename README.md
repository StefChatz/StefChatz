## Hi there 👋

Senior Full-Stack Engineer building production DeFi protocols and high-performance trading systems. I combine deep technical expertise (React, Next.js, Node.js, NestJS, PostgreSQL, Cosmos SDK) with a Master's in Finance to ship end-to-end products across the Web3 stack.

Currently Co-Founder & Tech Lead at **Hedgeway**, Senior Full-Stack Developer at **Mars Protocol** (Delphi Digital) and **Amber Finance**. I also create educational DeFi & finance content in Greek on YouTube, making sophisticated financial concepts accessible to everyday people.

---

### 🔭 Projects Designed, Developed and Led

- **[Hedgeway](https://hedgeway.xyz)**
  Delta-neutral yield protocol pairing DeFi yields with automated Hyperliquid hedges via senior/junior tranche vaults. I designed and built the full system:
  - Smart contract architecture: VaultFactory, TrancheVault, and Settlement Engine with Pendle PT-token integration
  - Node.js backend with PostgreSQL, Redis caching, and WebSocket feeds for live position monitoring
  - Real-time PnL computation and risk management across on-chain and off-chain components
  - Hyperliquid and Pendle protocol connectors for automated cross-protocol strategy execution

- **[Amber Finance](https://amberfi.io)** | [Docs](https://docs.amberfi.io/)
  Bitcoin DeFi yield platform on Neutron blockchain. I own the complete stack:
  - Leveraged looping strategies (up to 10x) with real-time health factor monitoring and liquidation protection
  - Cross-chain bridge supporting 50+ blockchain networks via Skip Protocol integration
  - Web3 wallet connectivity layer supporting 8+ Cosmos wallets (Keplr, Leap, Cosmostation, etc.)
  - Backend integration layer handling routing logic, transaction tracking, and multi-chain state management

- **[Delta-Mars](https://delta-mars.com)**
  Decentralized interface for deploying fully delta-neutral strategies on Neutron via Mars Protocol's Credit Manager:
  - Automatically balance lending positions with short perp trades to neutralize price exposure
  - Capture combined yield from lending APYs, perp funding rates, and incentive campaigns
  - Navigate market skew dynamics and optimize funding rate arbitrage
  - Real-time portfolio monitoring through a simple, intuitive UI

- **[Lore Capital](https://www.lore-capital.finance)**
  Delta-neutral yield fund delivering consistent, market-independent returns through DeFi strategies:
  - Total Annualized Return: 20% with 0.8% max drawdown
  - Sharpe Ratio: 14.35
  - Delta-neutral positioning across DeFi protocols to capture yield while minimizing directional exposure
  - Institutional-grade risk management with real-time monitoring and automated rebalancing

---

### 🛠 Open Source

- **[Ares Terminal](https://github.com/StefChatz/ares)** | [aresfi.xyz](https://aresfi.xyz)
  Production-ready perpetuals trading terminal for DeFi protocols. Originally built as a standalone perps product for Mars Protocol, open-sourced under MIT license so teams can ship professional trading interfaces in days, not months.
  - Next.js 16, TypeScript, shadcn/ui, Zustand, wagmi, TradingView integration
  - Draggable/resizable panel layout, keyboard-first execution, sub-50ms renders
  - Mobile-responsive design with full order types: market, limit, stop, TP/SL

- **[Hedgey CLI](https://github.com/hedgey-defi/hedgey)**
  DeFi position analyzer and risk management tool built with Bun and TypeScript:
  - Analyze Aave lending positions across multiple EVM chains (Ethereum, Polygon, Arbitrum, Optimism)
  - Real-time health factor monitoring, liquidation risk scenarios, and loop detection
  - DeFi "Greeks" calculations (delta, gamma, vega, theta) for lending positions
  - Hedge analysis module integrating Hyperliquid perp data for delta-neutral assessment

- **[Predator](https://github.com/StefChatz/predator)**
  Universal prediction market arbitrage engine. TypeScript monorepo for cross-platform arbitrage:
  - Platform connectors for Polymarket (EIP-712 signing) and Kalshi (RSA auth) with WebSocket orderbook streams
  - 3-tier market matching pipeline: tokenized slug similarity, sentence-embedding cosine sim, LLM-based verification
  - Real-time execution engine with circuit breakers, in-flight deduplication, and configurable daily loss limits
  - Next.js dashboard with live opportunity feed, P&L tracking, and position management

- **DeFi Yield Aggregator**
  Multi-chain backend platform for yield strategy discovery and computation:
  - NestJS backend with 15+ services: multi-source data ingestion (DeFiLlama, Pendle), leveraged strategy computation, risk scoring
  - PostgreSQL + TimescaleDB schema with Redis caching, Swagger-documented REST API, scheduled job processing
  - Docker-based infrastructure supporting Ethereum, Arbitrum, Base, Optimism, and Polygon

---

### 🤝 Projects Worked On as Core Contributor

- **[Mars Protocol](https://app.marsprotocol.io)**
  Sole engineer owning the full stack of Mars Protocol's Perpetual Futures trading platform (Delphi Digital):
  - Sub-50ms render-latency trading UI with Web Worker-based orderbook processing and SharedArrayBuffer state
  - WebSocket service with message batching, exponential-backoff reconnection, and multiplexed data channels
  - Backend integration for real-time price feeds, funding rate computation, and Cosmos SDK smart contract interaction
  - Perpetual derivatives features: margin engine, liquidation alerts, cross-collateral management

---

### ⚡ Tech Stack

```
Frontend      React · Next.js · Vite · TypeScript · Redux · Zustand · React Native · TailwindCSS · shadcn/ui
Build         Turborepo · pnpm · Bun · Vitest · GitHub Actions
Backend       Node.js · NestJS · Express · REST APIs · WebSocket Pipelines · GraphQL
Databases     PostgreSQL · TimescaleDB · Redis · Docker
Web3          Solidity · ethers.js · viem · wagmi · Cosmos SDK · CosmWasm · 50+ chain integrations
```

---

### 🎓 Education

**MSc Finance** - Alba Graduate Business School (2025)
**BSc Computer Science** - University of Surrey (2020)

---

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/stefanos-chatzakis)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/Monkmansteve)
[![Website](https://img.shields.io/badge/Website-000000?style=flat&logo=safari&logoColor=white)](https://stefchatz.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:chatzakis.stef@gmail.com)
