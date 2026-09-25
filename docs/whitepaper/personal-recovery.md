---
description: GenWealth personal crypto recovery — inactivity delay plus co-signers to assign a new vault owner if you lose your main wallet.
---

# Personal crypto recovery

With the app you can set a **Plan B**: if you lose the seed phrase of the wallet that owns the vault — or that wallet is compromised — co-signers you named can help assign a **new owner wallet** after an inactivity delay you chose. The vault (including will settings) stays under rules you published; you are restoring control, not asking GenWealth to hold keys.

## How recovery works in the product today

1. **Name recovery wallets in advance**

    Add up to five addresses — other wallets you control, trusted people, or a mix — and set how many must sign.

2. **Set an inactivity delay**

    Choose how long the vault must sit unused before recovery is allowed. Keep this **shorter** than your proof-of-life deadline when you also have a will.

3. **Recover when needed**

    On **Vault Recovery**, enter the new owner address, collect the required co-signatures after the delay, and submit. Co-signers need a little ADA to help with fees.


!!! info
    You have full control over wallets, thresholds, and deadlines when you create the plan.


!!! warning
    Do not set the signature threshold too low. Requiring a single signature would allow any one designated signer to complete recovery alone. Prefer a higher threshold and clear operational habits. See [Create and run a recovery plan](../guides/recovery-plan.md).


!!! info
    Earlier drafts described separate “slow” and “quick” products. The shipped flow combines inactivity with M-of-N co-signers in one recovery plan.

