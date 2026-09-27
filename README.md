# 0xilbiscione

**Building autonomous AI agents on Solana — and shipping AI-assisted finance systems in public.**

---

I'm the founder of Bun Protocol — a fully autonomous AI system that trades meme coins, deploys tokens, and tracks money — without human input.

I use GitHub as a build log: tightening agent workflows, documenting repo context for AI coding tools, and turning repeated finance/crypto workflows into auditable software.

### What I'm building

**gmgnAgent** — Autonomous meme-coin trader on Solana.  
Screens trending tokens via GMGN, scores conviction with an LLM (OpenRouter), executes trades via Jupiter Ultra, and manages exits automatically. Position state persisted in SQLite. Trade receipts and alerts pushed to Telegram. Runs 24/7 via PM2 behind Nginx, with every trade logged and auditable.

**token-deployer** — Autonomous memecoin launcher.  
Watches X for viral posts, scores virality with an LLM, extracts a token theme, and deploys a new token on [pump.fun](https://pump.fun) fully on-chain — no human needed. Uses Printr API for token creation and Helius RPC for on-chain confirmation. → [github.com/0xilbiscione/BunDev](https://github.com/0xilbiscione/BunDev)

**MetricBase Platform** — Unified workspace for teams and their AI agents.  
Projects, Finance, Field ops, team chat, and AI agent members in one multi-tenant org, with multi-currency books, a transaction approval workflow, and an audit trail. Supersedes the standalone financial-tracker. Next.js 16 · Prisma 7 + Neon · Auth.js v5. Live at [apps.metricbase.org](https://apps.metricbase.org).

**FinAgent** — Automated financial report pipeline.  
Extracts tables from annual/quarterly PDF reports with Python (`pdfplumber` + `pandas`) and maps them to a standardized double-entry ledger CSV that feeds the platform's Finance module.

**MetricBase World** — Browser-native isometric MMO with a transparent on-chain economy.  
Gather, craft, trade, and build — free to play on the web or as a Telegram Mini App, with $BASE (Solana SPL) Season rewards. Phaser 3 + Colyseus · Neon Postgres. → [world.metricbase.org](https://world.metricbase.org) · [repo](https://github.com/MetricBaseOrg/metricbase-world)

**PumpBid** — Live on-chain auction for the @metricbase X header.  
Bid with any Solana token; fills are marked to USDC via Jupiter, the top 10 seats become stickers, and the banner restamps on X automatically. → [bid.metricbase.org](https://bid.metricbase.org)

**MetricBase** — Analyzing data by day, on-chain strategist by night.  
Research across energy markets, crypto, and Indonesian equities, plus a Monday Weekly Brief. → [metricbase.org](https://metricbase.org) · [github.com/MetricBaseOrg](https://github.com/MetricBaseOrg)

### Stack

`Solana` `TypeScript` `Python` `Bun` `Next.js` `React` `TanStack Start` `Fastify` `Tailwind`<br>
`Jupiter Ultra` `GMGN API` `Printr API` `Helius RPC` `OpenRouter LLM` `Phaser` `Colyseus`<br>
`Prisma` `Neon Postgres` `SQLite` `Auth.js` `Resend` `Agent-Reach` `PM2` `Nginx` `Vercel` `Railway` `Telegram`<br>
`Claude Code` `Codex` `GitHub` `AI-assisted development`

### Philosophy

> Agents should work while you sleep.<br>
> Every trade auditable. Every deployment traceable.<br>
> Ship small, document context, and let AI handle the repeatable work.
