---
description: How GenWealth vaults, proof of life, beneficiaries, executors, fractionalization, and recovery fit together — updated to the live product.
---

# How it works

To use GenWealth you need a Cardano wallet. You connect that wallet to the app and create a **vault** where you can hold assets, create your blockchain will, and set a recovery plan. The vault is controlled by the wallet you connected; you approve actions with that wallet’s signature.

The vault lets you do what you expect from a wallet — hold, receive, stake, interact with supported dApps, and send assets — plus inheritance and recovery rules enforced on-chain.

## Inheritance trigger: proof of life

In the current product we start with a simple, trust-minimized trigger: **Proof of Life**.

- You set a deadline of your preference and must occasionally update it (or use the vault) to prevent inheritance from becoming available.
- Example: set a deadline and “show up” on a schedule you can keep.
- Using assets in the vault updates activity automatically.
- Chosen for reliability, low cost, simplicity, and avoiding intermediaries for the trigger itself.

### Optional executor trigger

You can nominate a professional or trusted person with permission to **trigger inheritance** according to delays you configure. Use carefully — this adds trust in that person for timing, not unlimited custody of your seed phrase.

### Future triggers

Decentralized ID / verifiable credentials for death documentation, and oracle links to public registers, remain **future** options for jurisdictions that demand them. They are not required for today’s proof-of-life product.

## Beneficiaries and assets

- Add beneficiaries by a label you recognize and the wallet addresses they control.
- For each beneficiary you can assign **specific assets**, a **share** of the vault, or both.
- On-chain you can have up to **nine** beneficiaries. Shares must total 100%.

## Executors and permissions

Optionally add an executor and grant only the powers they need:

- Change Inheritance Rules
- Spend (within the funding and rules you set)
- Close DeFi Positions
- Fractionalize Assets
- Trigger Inheritance State

Permissions are optional. You can create a will without executors; smart contracts still execute your published wishes.

## Claims and leftovers

Beneficiaries claim in **two stages**: reserved specific assets first, then percentage shares of what remains. After a long window you configure, remaining assets may go to a configured **community** address so value is not locked forever. Broader “recovery economy” DAO voting described in earlier drafts remains a **future** direction.

## Updates

Before inheritance starts you can edit beneficiaries, executors, permissions, proof-of-life timing, and recovery settings. After inheritance has started, that state cannot be turned off on-chain.

## Fractionalization

Owners (and executors with permission) can split a non-ADA asset into shares and later reunite all shares into the original asset — useful when several heirs should share one NFT or similar item.

For accurate screens and limits, prefer [How GenWealth works](../how-it-works/overview.md) and the [user guides](../find-a-guide.md).
