# 0xilbiscione

**Building autonomous AI agents on Solana.**

---

I'm the founder of Bun Protocol — a fully autonomous AI system that trades meme coins, deploys tokens, and tracks money — without human input.

### What I'm building

**gmgnAgent** — Autonomous meme-coin trader on Solana.  
Screens trending tokens via GMGN, scores conviction with an LLM (OpenRouter), executes trades via Jupiter Ultra, and manages exits automatically. Position state persisted in SQLite. Trade receipts and alerts pushed to Telegram. Runs 24/7 via PM2 behind Nginx, with every trade logged and auditable.

**token-deployer** — Autonomous memecoin launcher.  
Watches X for viral posts, scores virality with an LLM, extracts a token theme, and deploys a new token on [pump.fun](https://pump.fun) fully on-chain — no human needed. Uses Printr API for token creation and Helius RPC for on-chain confirmation. → [github.com/0xilbiscione/BunDev](https://github.com/0xilbiscione/BunDev)

**financial-tracker** — Multi-tenant financial tracker for individuals and companies.  
Multi-currency (IDR/USD), multi-workspace. Covers the full personal/company finance stack: P&L, balance sheet, investment positions + lots + dividends, recurring transactions, workspace invites, audit log, CSV import, PDF export, and a custom SVG chart suite. Built on Next.js 16 · Prisma 7 + Neon · Auth.js v5 · Tailwind v4. Deployed at [apps.metricbase.org](https://apps.metricbase.org).

**FinAgent** — Automated financial report pipeline.  
Takes raw PDF financial reports (annual/quarterly), extracts tabular data via Python (`pdfplumber` + `pandas`), synthesizes a structured wiki entry, and maps the results to a standardized double-entry ledger CSV. Feeds clean, structured data into the financial-tracker.

**MetricBase** — Analyzing data by day, on-chain strategist by night.  
Resource center for energy, crypto, and equity markets. → [github.com/MetricBaseOrg](https://github.com/MetricBaseOrg)

### Stack

`Solana` `TypeScript` `Python` `Bun` `Next.js` `React` `Fastify` `Tailwind`  
`Jupiter Ultra` `GMGN API` `Printr API` `Helius RPC` `OpenRouter LLM`  
`Prisma` `Neon Postgres` `SQLite` `Auth.js` `Resend` `Agent-Reach` `PM2` `Nginx` `Telegram`

### Philosophy

> Agents should work while you sleep.  
> Every trade auditable. Every deployment traceable.
