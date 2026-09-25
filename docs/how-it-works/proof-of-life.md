---
description: How GenWealth proof of life works — inactivity deadlines, last-used updates, and why inheritance can start without a death certificate.
---

# Proof of life

GenWealth’s first inheritance trigger is **proof of life**, also called an inactivity deadline.

## The idea

1. You choose how long the vault may sit unused.
2. When you use the vault (or explicitly update the deadline), the clock resets.
3. If the quiet period passes, inheritance **can** start — either when someone triggers it, or when automation/helpers submit the trigger after the deadline.

There is **no** requirement to upload a death certificate for this trigger. That keeps the mechanism simple and trust-minimized. It also means you must pick a deadline you can keep, and use recovery if you lose access before the will should open.

## Why GenWealth starts here

Proof of life is reliable, low-cost, and does not depend on governments or oracles for version one. Other triggers (for example credential-based death verification) remain future options described in the whitepaper.

## Related settings

When you build a will you also choose waits that apply **after** inheritance starts (executor delays, grace period before claims, time before share claims can proceed, and a long social-claim window). Those are explained in [Inheritance phases](inheritance-phases.md).

Practical steps: [Stay active and understand inheritance phases](../guides/stay-active.md).
