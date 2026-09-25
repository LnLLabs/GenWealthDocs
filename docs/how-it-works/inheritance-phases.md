---
description: GenWealth inheritance phases — trigger, executor window, specific-asset claims, share claims, and social claim for leftovers.
---

# Inheritance phases

Once inheritance mode is on, the vault follows a sequence. Exact lengths come from the settings the owner chose.

## 1. Trigger

After the proof-of-life quiet period, inheritance can be switched on. An executor with **Trigger Inheritance State** may be allowed to start it earlier according to the delays the owner configured. When inheritance is on, that state is **sticky** — it cannot be flipped back off on-chain.

## 2. Executor window

If executors exist, they may act inside their permissions (adjust rules where allowed, close DeFi, fractionalize in limited cases, and so on) during the delays and grace periods the owner set.

## 3. Claim stage 1 — specific assets

After the executor grace period, each beneficiary can claim assets that were reserved for them personally.

## 4. Claim stage 2 — shares

When stage-1 claims are done (or when the owner’s claim-time rules say the share step may proceed), beneficiaries claim their **percentage** of what remains. Shares are defined so the whole vault adds up to 100%.

## 5. Social claim

After a long window the owner configured, remaining assets may be claimable to GenWealth’s configured **community** address so value is not locked forever. Broader DAO voting ideas from early whitepaper drafts remain future product direction, not the day-one claim path.

!!! warning
    Maximum **nine** beneficiaries on-chain. Edit the will freely **before** trigger; after trigger, treat the plan as executing.


How to claim in the app: [Claim your inheritance](../guides/claim-inheritance.md).
