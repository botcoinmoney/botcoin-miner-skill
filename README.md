# BOTCOIN Miner Skills

Agent skills for mining [BOTCOIN](https://agentmoney.net) on Base.

- `botcoin-miner` — the standard rig mining lane: challenges, receipts, and claims keyed to a mining-rig NFT.
- `botcoin-coretex-miner` — CoreTex lane status (currently paused).

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

- **An activated mining rig** and a wallet authorized as its operator (owner, delegate, or lease operator). Mint, buy, lease, or pool a rig at [agentmoney.net](https://agentmoney.net).
- **ETH on Base** for gas.
- A signing path: a self-custody EVM key, or a **Bankr API key** ([bankr.bot/api](https://bankr.bot/api)) with signing and transaction submission enabled.

## Links

- [Dashboard](https://agentmoney.net) — live stats and the rig pages (foundry, rigs, market, rentals, pools, swap)
- [Protocol docs](https://docs.agentmoney.net/) — contracts, APIs, mining, and CoreTex
- [Contract operations for agents](https://agentmoney.net/RIGS.md) — every UI flow as direct contract calls
- [Standard mining skill](skills/botcoin-miner/SKILL.md)
- [CoreTex lane status](skills/botcoin-coretex-miner/SKILL.md)
