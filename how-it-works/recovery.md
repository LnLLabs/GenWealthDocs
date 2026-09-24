---
description: How GenWealth crypto recovery works — inactivity delay, M-of-N co-signers, and assigning a new vault owner wallet.
icon: key
---

# Crypto recovery

Recovery is separate from inheritance. It answers: “I lost my main wallet, but I still want this vault (and my will settings) under a wallet I control.”

## What you set in advance

- Up to **five** recovery addresses (co-signers)
- How many of them must sign (**M** of those addresses)
- An inactivity **delay** (usually shorter than proof of life)

## What happens at recovery time

1. The vault has been unused at least as long as the recovery delay.
2. You (or helpers) open **Vault Recovery**.
3. You enter the **new owner** wallet address.
4. Enough co-signers sign.
5. Control moves to the new owner wallet. The recovery step itself is about restoring control, not emptying the vault to random addresses.

{% hint style="info" %}
The shipped product is this combined flow. Older whitepaper wording about two fully separate “quick” and “slow” products is outdated; see the corrected [Personal crypto recovery](../whitepaper/personal-recovery.md) chapter and the [recovery guide](../guides/recovery-plan.md).
{% endhint %}

## Recovery vs inheritance

| | Recovery | Inheritance |
| --- | --- | --- |
| Goal | New owner for the same vault | Beneficiaries receive assets |
| Typical delay | Shorter | Longer (proof of life) |
| Who acts | Co-signers you named | Beneficiaries (and optional executors) |
