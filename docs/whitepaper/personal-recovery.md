---
description: GenWealth personal crypto recovery — inactivity delay plus co-signers to assign a new vault owner if you lose your main wallet.
---

# Personal crypto recovery

With the app you can set a **Plan B**: if you lose the seed phrase of the wallet that owns the vault — or that wallet is compromised — co-signers you named can help assign a **new owner wallet** after an inactivity delay you chose. The vault (including will settings) stays under rules you published; you are restoring control, not asking GenWealth to hold keys.

## How recovery works in the product today

1. **Name recovery wallets in advance**

    Add up to five addresses — other wallets you control, trusted people, or a mix. Today the app requires **only one** of them to sign for recovery.

2. **Set an inactivity delay**

    Choose how long the vault must sit unused before recovery is allowed. Keep this **shorter** than your proof-of-life deadline when you also have a will.

3. **Recover when needed**

    On **Vault Recovery**, enter the new owner address, collect one co-signature after the delay, and submit. Co-signers need a little ADA to help with fees.


!!! info
    You choose the recovery addresses and the inactivity delay when you create the plan. A configurable multi-signature threshold is not available in the UX yet.


!!! warning
    Because only one signature is required today, treat every listed recovery address as able to complete recovery alone. Prefer wallets you also control, and only add people you fully trust. See [Create and run a recovery plan](../guides/recovery-plan.md).


!!! info
    Earlier drafts described separate “slow” and “quick” products and an M-of-N threshold. The shipped flow is inactivity delay plus co-signers in one recovery plan, with a single signature required.

