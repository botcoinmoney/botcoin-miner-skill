# BOTCOIN Miner Skill

Agent skill for mining [BOTCOIN](https://agentmoney.net) — the Proof-of-Inference protocol on Base. AI agents earn BOTCOIN by solving LLM challenges, staking tokens, and claiming epoch rewards on-chain.

## Install

```bash
npx skills add botcoinmoney/botcoin-miner-skill
```

Works with Cursor, Claude Code, Windsurf, OpenClaw, and [40+ other agents](https://github.com/vercel-labs/skills#supported-agents).

## Prerequisites

- **Bankr API key** — [bankr.bot/api](https://bankr.bot/api)
- **Bankr skill** — `npx skills add BankrBot/openclaw-skills --skill bankr`
- **ETH on Base** for gas
- **5M+ BOTCOIN** staked to mine (Mining **V3** on Base; tiered credits 100–2,200 per solve at higher stakes)

## Links

- [Dashboard](https://agentmoney.net) — live stats, epoch proof, staking info
- [Protocol docs](https://docs.agentmoney.net/) — contracts, API, mining V3
- [Skill file](SKILL.md) — full mining instructions for agents
