---
description: Split a non-ADA asset into shares in GenWealth, or reunite all shares to restore the original asset.
icon: pie-chart
---

# Fractionalize assets

**Fractionalization** splits a vault asset (not ADA) into a number of shares. You can later **un-fractionalize** when you hold all shares again. This helps when several beneficiaries should share one NFT or similar asset.

Open **Fractionalization** in the sidebar.

## Create shares

{% stepper %}
{% step %}
### Open the Fractionalization tab

Select the asset to split. ADA cannot be fractionalized here.
{% endstep %}

{% step %}
### Define the number of shares

Enter how many shares to create (the app may default to 100). Confirm **Fractionalize** and approve in your wallet.
{% endstep %}
{% endstepper %}

## Restore the original asset

Open **Un-Fractionalization**. You need **all** shares. Confirm and approve to reconstitute the original asset.

{% hint style="info" %}
Executors with the fractionalize permission may only fractionalize in limited cases (for example leftovers that cannot be divided cleanly for inheritance). Owners have full access to the screen while they control the vault.
{% endhint %}
