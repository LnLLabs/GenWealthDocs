---
description: Set up a GenWealth recovery plan with co-signers and inactivity delay, then run Vault Recovery if you lose your main wallet.
---

# Create and run a recovery plan

A **recovery plan** is your Plan B. If you lose access to the wallet that owns the vault, trusted co-signers can help you assign a **new owner wallet** after an inactivity delay you chose.

!!! info
    Set the recovery inactivity period **shorter** than your proof-of-life deadline, so you can recover before a will would start.


## Create or update the plan

Open **Crypto Recovery** in the sidebar.

1. **Start a plan**

    If the page is empty, choose **Create Recovery Plan**. To change an existing plan, open the edit flow and use **Update Plan**.

2. **Add recovery addresses**

    Add up to **five** wallet addresses that may co-sign recovery. These can be other wallets you control and/or people you trust. Today the app requires **only one** of them to sign — any listed address can complete recovery alone.

3. **Set the time period for recovery**

    Choose how long the vault must stay unused before recovery is allowed (days or months).

4. **Confirm create or update**

    Select **Create Plan** or **Update Plan** and approve in your wallet.


You can delete a plan later with **Delete recovery plan** if you no longer want one.

!!! warning
    Today only **one** co-signer signature is required for recovery, even if you listed several addresses. Treat every recovery address as able to help take control alone. Prefer wallets you also control, and only add people you fully trust.


## Run recovery

Use this only when you need a new owner wallet and the inactivity delay has passed.

1. **Open Recover your Vault**

    From the vault hub choose **Recover your Vault**, or open **Vault Recovery**.

2. **Enter the new owner wallet address**

    Type the Cardano address that should control the vault going forward.

3. **Select a co-signer**

    Tick one recovery address from your plan (only one signature is required today).

4. **Start recovery and collect the signature**

    Choose **Start Recovery**. The selected co-signer connects the matching wallet and signs. Co-signer wallets need a little ADA (about 10 ADA or more is a practical cushion) to help pay fees.

5. **Submit and open the vault**

    After the signature is collected, submit and continue to the vault wallet under the new owner.


!!! info
    GenWealth’s live recovery flow is this single path: inactivity delay plus co-signers choosing a new owner. There are not separate “instant only” and “slow only” products in the app.


Background: [How recovery works](../how-it-works/recovery.md).
