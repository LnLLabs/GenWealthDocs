---
description: Set up a GenWealth recovery plan with co-signers and inactivity delay, then run Vault Recovery if you lose your main wallet.
---

# Create and run a recovery plan

A **recovery plan** is your Plan B. If you lose access to the wallet that owns the vault, trusted co-signers can help you assign a **new owner wallet** after an inactivity delay you chose.

{% hint style="info" %}
Set the recovery inactivity period **shorter** than your proof-of-life deadline, so you can recover before a will would start.
{% endhint %}

## Create or update the plan

Open **Crypto Recovery** in the sidebar.

{% stepper %}
{% step %}
### Start a plan

If the page is empty, choose **Create Recovery Plan**. To change an existing plan, open the edit flow and use **Update Plan**.
{% endstep %}

{% step %}
### Add recovery addresses

Add up to **five** wallet addresses that may co-sign recovery. These can be other wallets you control and/or people you trust.
{% endstep %}

{% step %}
### Set the time period for recovery

Choose how long the vault must stay unused before recovery is allowed (days or months).
{% endstep %}

{% step %}
### Confirm create or update

Select **Create Plan** or **Update Plan** and approve in your wallet.
{% endstep %}
{% endstepper %}

You can delete a plan later with **Delete recovery plan** if you no longer want one.

{% hint style="warning" %}
Do not set the required number of co-signers too low. If only one signature is enough, that single person could help take control alone. Prefer several of your own wallets plus trusted people, with a threshold above one.
{% endhint %}

## Run recovery

Use this only when you need a new owner wallet and the inactivity delay has passed.

{% stepper %}
{% step %}
### Open Recover your Vault

From the vault hub choose **Recover your Vault**, or open **Vault Recovery**.
{% endstep %}

{% step %}
### Enter the new owner wallet address

Type the Cardano address that should control the vault going forward.
{% endstep %}

{% step %}
### Select enough co-signers

Tick at least as many recovery addresses as your plan requires (often all of them, or the M-of-N number you set).
{% endstep %}

{% step %}
### Start recovery and collect signatures

Choose **Start Recovery**. Each selected co-signer connects the matching wallet and signs. Co-signer wallets need a little ADA (about 10 ADA or more is a practical cushion) to help pay fees.
{% endstep %}

{% step %}
### Submit and open the vault

After signatures are collected, submit and continue to the vault wallet under the new owner.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
GenWealth’s live recovery flow is this single path: inactivity delay plus co-signers choosing a new owner. There are not separate “instant only” and “slow only” products in the app.
{% endhint %}

Background: [How recovery works](../how-it-works/recovery.md).
