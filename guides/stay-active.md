---
description: Keep your GenWealth vault active, update proof of life, and understand the phases after inheritance starts.
---

# Stay active and understand inheritance phases

Your blockchain will uses **proof of life**: if the vault is unused for longer than the deadline you set, inheritance can start. Using the vault (or updating the deadline) shows you are still in control.

## Before inheritance starts

- Use the vault wallet (send, deposit, and similar actions) so the “last used” time stays fresh.
- Open **Blockchain Will** → **Settings** and choose **Update Deadline** if you want a longer quiet period without waiting for normal use.
- Set a **recovery** inactivity period that is **shorter** than proof of life, so you can recover before a will would start. See [Create and run a recovery plan](recovery-plan.md).

{% hint style="info" %}
Think of proof of life as a calendar reminder baked into the vault. Miss it for too long, and the will can open for beneficiaries.
{% endhint %}

## After inheritance starts

Once inheritance mode begins, the vault moves through phases. Exact timing follows the settings you chose.

1. **Executor adjust window** — if you named executors, they may act within the permissions and delays you gave them.
2. **Claim stage 1 (specific assets)** — beneficiaries claim assets you reserved for them personally.
3. **Claim stage 2 (shares)** — beneficiaries claim their percentage of what remains.
4. **Social claim window** — after a long period you configured, leftovers can go to the community address GenWealth configures (not back into a personal “off” switch for the will).

{% hint style="warning" %}
Inheritance that has started cannot be cancelled on-chain. Plan deadlines carefully while you still control the vault.
{% endhint %}

Beneficiaries should follow [Claim your inheritance](claim-inheritance.md). For a deeper explanation, see [Inheritance phases](../how-it-works/inheritance-phases.md).
