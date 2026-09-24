---
description: Start a vault owner change in GenWealth, wait the 24-hour delay, then finalize or cancel from Vault Controls.
icon: user
---

# Change the vault owner

You can move control of a vault to a different wallet you choose. GenWealth builds in a **24-hour waiting period** so a rushed or mistaken change can still be stopped.

Open **Vault Controls** in the sidebar.

{% stepper %}
{% step %}
### Start the owner change

Choose **Change Owner** and enter the new owner’s wallet address. Confirm and approve in your current wallet.
{% endstep %}

{% step %}
### Wait 24 hours

The change cannot finish immediately. During the wait, you can still cancel if this was a mistake.
{% endstep %}

{% step %}
### Finalize or cancel

After 24 hours, finalize the change with the current owner wallet, or cancel to keep the existing owner. Approve the chosen action in your wallet.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Only finalize when you are sure the new address is correct and that wallet’s seed phrase is safe. After finalization, the old wallet no longer controls the vault.
{% endhint %}
