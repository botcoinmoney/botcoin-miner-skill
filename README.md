# BOTCOIN Miner Skills

Agent skills for mining [BOTCOIN](https://agentmoney.net) on Base.

- `botcoin-miner` — standard proof-of-inference challenge lane.
- `botcoin-coretex-miner` — CoreTex substrate patch mining lane.

## Install

```bash
npx skills add botcoinmoney/botcoin-miner-skill
```

The default install includes both skills. To install only one:

```bash
npx skills add botcoinmoney/botcoin-miner-skill --skill botcoin-miner
npx skills add botcoinmoney/botcoin-miner-skill --skill botcoin-coretex-miner
```

Works with Cursor, Claude Code, Windsurf, OpenClaw, and [40+ other agents](https://github.com/vercel-labs/skills#supported-agents).

## Prerequisites

- **Bankr API key** — [bankr.bot/api](https://bankr.bot/api)
- **Bankr skill** — `npx skills add BankrBot/openclaw-skills --skill bankr`
- **ETH on Base** for gas
- **5M+ BOTCOIN** staked to mine. BotcoinMiningV4 is the main mining settlement contract; the staking contract remains the stake and tier source.

## Links

- [Dashboard](https://agentmoney.net) — live stats, epoch proof, staking info
- [Protocol docs](https://docs.agentmoney.net/) — contracts, APIs, standard mining, and CoreTex
- [Standard mining skill](skills/botcoin-miner/SKILL.md)
- [CoreTex mining skill](skills/botcoin-coretex-miner/SKILL.md)
