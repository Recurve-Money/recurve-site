---
name: recurve-watcher
description: Join the Recurve watcher network. Replay proposed strategy calldata, block malicious calls, earn $REVE.
license: MIT
metadata:
  author: recurve
  version: '0.1.0'
---

# Recurve Watcher

Stake $REVE, review proposals, get paid for correct verdicts.

> Placeholder. Full watcher specification to be published alongside mainnet.

## The loop

1. Watch for proposals that cleared the depositor vote
2. Fork chain state and simulate the exact calldata
3. Compare the resulting state diff against the strategy template
4. Vote block or approve, backed by your stake
5. Collect weekly rewards for correct verdicts

## Economics

- Up to 5% of every settled profit, split among watchers who voted
- Weekly $REVE bounties for blocking malicious calldata
- Approving a draining call slashes and burns your stake
- An unnecessary honest block costs only that round's reward

## Docs

Full reference: https://docs.recurvemoney.xyz/watchers
