---
description: Connect your wallet, create a GenWealth vault or enter an existing one, and save your vault ID safely offline.
icon: lock
---

# Create or enter a vault

A **vault** is your GenWealth smart wallet on Cardano. You control it with the Cardano wallet you connect. From the vault you can hold assets, set a blockchain will, and set a recovery plan.

## Create a new vault

{% stepper %}
{% step %}
### Connect your wallet

Open GenWealth and complete [Use your wallet with GenWealth](../cardano/use-wallet-with-genwealth.md). You land on the vault hub.
{% endstep %}

{% step %}
### Choose Create

On the vault hub, select **Create**. You open the vault creation screen.
{% endstep %}

{% step %}
### Name the vault

Enter a **Vault Name**. You may optionally add an **Owner Email** if you want email notifications later.
{% endstep %}

{% step %}
### Accept the acknowledgements

Tick the responsibility checkbox and **I've read and accept the Terms and Conditions**. Both are required.
{% endstep %}

{% step %}
### Confirm and create

Select **Create Vault**, review the fees, then **Confirm and Create**. Approve in your wallet. You may be asked to prepare collateral in the wallet first — follow the on-screen confirmations.
{% endstep %}

{% step %}
### Save your vault ID

After creation, your vault has an ID that looks like a long code ending with `#` and a small number (for example `…abc123#0`). Write it down offline. GenWealth cannot recreate this ID for you if you lose every copy.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Store the vault ID with the same care as important account numbers. You may need it to import the vault later.
{% endhint %}

## Enter an existing vault

{% stepper %}
{% step %}
### Choose Enter on the vault hub

Open **Your Vault** (vault selection).
{% endstep %}

{% step %}
### Select a known vault, or import one

If GenWealth already lists your vault, select it. Otherwise use **Find vaults** (you sign a message with your wallet) or **import by vault ID** using the ID you saved.
{% endstep %}

{% step %}
### Continue to the vault wallet

Once selected, you enter the vault and land on the vault wallet overview.
{% endstep %}
{% endstepper %}

## Other hub options

From the vault hub you can also open:

- **Inheritance** — claim flows for beneficiaries ([Claim your inheritance](claim-inheritance.md))
- **Will Execution** — enter as an executor ([Help as an executor](executor-guide.md))
- **Recover your Vault** — run a recovery plan ([Create and run a recovery plan](recovery-plan.md))

Next: [Use your vault wallet](vault-wallet.md).
