---
description: GenWealth completed roadmap — from early inheritance contracts to the modular vault app with wills, recovery, executors, and DeFi.
icon: check-circle
---

# Completed roadmap

As with any startup, the roadmap may change as we search for product–market fit. This chapter records what has already been achieved.

## Early work and learnings

- **Early 2024:** first inheritance smart contracts and a basic proof-of-concept that validated feasibility.
- **First dApp release** on that architecture: create a vault, define proof of life, section assets for beneficiaries, issue claim receipts, keep self-custody, and experiment with admin/recovery tokens.
- **Private testing** with crypto users and inheritance professionals across countries. Professionals were enthusiastic and asked for capabilities that drove a major redesign.

## Architectural revamp

The contracts moved from a single large design to a **modular vault**: core vault control plus modules for inheritance, recovery, fractionalization, and DeFi integration (including Minswap owner flows).

That redesign enabled:

- Better DeFi compatibility for smart-contract wallets on Cardano
- Lawyer / executor permissions with limited powers
- Fractionalization of NFTs / RWA-style tokens
- Flexible division: specific assets, percentage shares, or both
- Time-based paths so unclaimed value is not locked forever

## Product today (relative to earlier “V2 still in design” wording)

The GenWealth application now includes, among other capabilities:

- Vault create / enter / discover, vault wallet (send, receive, deposit, stake, history)
- Blockchain will with proof of life, beneficiaries, executors, and settings
- Two-stage claiming for beneficiaries
- Crypto recovery plans and vault recovery execution
- Owner change with a delay, fractionalization, Minswap swap/earn on supported networks
- Contacts and optional email notification registration

Public testing continues on Cardano **preprod**. Mainnet launch follows audit and release readiness.
