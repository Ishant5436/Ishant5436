# Ishant Panchal

**Systems engineer and Web3 security researcher.** I build low-latency trading infrastructure and autonomous agents, and I audit smart contracts for a living on the side.

Engineering student at K. J. Somaiya College of Engineering, Mumbai.

---

### What I work on

- **Low-latency systems** — zero-allocation C++20 data structures, deterministic execution, and honest backtesting harnesses for crypto markets.
- **Smart-contract security** — audit contests and bug bounties on Code4rena, Sherlock, Cantina, and Immunefi across EVM, Solana/Anchor, Soroban, and Hedera. Every finding ships with a Foundry or Rust proof of concept.
- **Autonomous agents** — LLM tool use, multi-agent orchestration, and the infrastructure that keeps AI coding agents reliable in production.
- **Solana & Web3 products** — payment-gated services, DeFi tooling, and on-chain settlement.

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [alpha-engine](https://github.com/Ishant5436/alpha-engine) | Zero-heap C++20 core for market-data processing and backtesting — cache-aligned ring buffers, monotonic queues, online variance; ~120M ticks/sec, sanitizer-clean, CI-enforced safety invariants | C++20 · Python |
| [pyrycode](https://github.com/Ishant5436/pyrycode) | Process supervisor for Claude Code — crash recovery, session resume, attach/detach, and a Unix-socket control plane | Go |
| [polymarket-btc-bot](https://github.com/Ishant5436/polymarket-btc-bot) | Gasless trading bot for Polymarket's 5-minute BTC markets — LightGBM inference on live Binance streams, post-only maker execution on Polygon | Python |
| [SolCloud](https://github.com/Ishant5436/SolCloud) | Auto-provisions isolated Cloudflare R2 buckets, gated by a Solana payment indexer — no human in the loop | TypeScript · Solana |
| [FundWise](https://github.com/Ishant5436/FundWise) | Reverse Splitwise on Solana — pooled group funds with on-chain settlement | Rust · Solana |

### Toolbox

**Languages** — C++ · Rust · Go · Python · TypeScript · Solidity  
**Web3** — Foundry · Anchor · Slither · Mythril · cargo-audit  
**Backend & infra** — FastAPI · NestJS · Docker · GitHub Actions
**Data** — NumPy · LightGBM  

### How I work

Minimal, surgical diffs scoped to the problem. Tests pass locally before anything goes up, and claims in a README are claims I can reproduce.

### Get in touch

Open to collaborating on low-latency systems, security research, and Solana projects.
[X / Twitter](https://x.com/IshantP38294) · or open an issue on any of my repos.
