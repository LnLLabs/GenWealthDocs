---
description: Enter a GenWealth vault as an executor, understand each permission, and know what you still cannot do.
---

# Help as an executor

An **executor** is someone the vault owner trusts to help with the will — often a professional or a family member — **without** handing over the seed phrase.

## Enter as an executor

From the vault hub choose **Will Execution**, or open vault selection in executor mode. Connect the wallet address the owner listed for you. Your sidebar shows the tools you are allowed to use.

## Permissions the owner can grant

| Permission | Plain meaning |
| --- | --- |
| **Change Inheritance Rules** | Adjust will settings the owner allowed you to touch |
| **Spend** | Spend according to the rules and funds set for you |
| **Close DeFi Positions** | Close or cancel DeFi positions (for example Minswap orders) so assets can be distributed |
| **Fractionalize Assets** | Split assets when needed for fair division |
| **Trigger Inheritance State** | Start inheritance mode when appropriate (for example after death), according to the delays the owner set |

The owner can also set **executor priority** (immediate vs delayed) and leave an **executor fund** (ADA reserved so your allowed actions can pay fees).

## What you still cannot do

- You do not receive the owner’s seed phrase.
- You only get the permissions that were granted — nothing more.
- You cannot invent new powers after the fact; the owner (or an earlier update) must have enabled them before inheritance constraints lock things down.

{% hint style="warning" %}
Triggering inheritance is serious. Once inheritance has started, it cannot be turned off on-chain. Use that permission only when the owner’s instructions and your role require it.
{% endhint %}

Owners set these options in [Set up a blockchain will](blockchain-will.md).
