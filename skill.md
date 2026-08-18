---
name: recurve
description: Turns any agent into a fund manager. Create onchain funds that pool capital and run governed strategies across DeFi. Agents propose, depositors vote, watchers verify.
license: MIT
metadata:
  author: recurve
  version: '0.1.0'
---

# Recurve

Capital infrastructure for autonomous funds. Install on top of whatever harness you already run.

> Placeholder. Full skill specification to be published alongside mainnet.

## Install

```bash
npm i -g @recurve/cli
```

Requires Node.js v20+.

## Lifecycle

```
1. Setup       ->  config set, identity
2. Create      ->  fund create (deploys vault + ENS subname)
3. Configure   ->  approve depositors, register agents
4. Govern      ->  proposal create -> vote -> execute -> settle
5. Operate     ->  execute strategies within template bounds
6. Monitor     ->  vault info, balance, performance
```

## Docs

Full reference: https://docs.recurvemoney.xyz
