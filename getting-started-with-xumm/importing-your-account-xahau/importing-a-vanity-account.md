---
description: How to duplicate a Vanity account on Xahau
---

# Duplicating a Vanity Account on Xahau

### Background

You might remember when you purchased your vanity account, we configured a regular key account to sign for your vanity address then we disabled the master keys for it.&#x20;

This meant that in order to sign transactions on your vanity address, you needed to have your regular key account imported into Xaman (formerly Xumm) with full access and you had to have your vanity address imported into Xaman in read only mode.

In Xaman, it would look something like this:

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>



{% hint style="info" %}
You may have noticed that the Vanity Account says, 'Full access" rather than 'Read only". That is becuase Xaman recognizes that the regular key account is present and in 'Full access" so it updates the Vanity account from 'Read only' to 'Full access'.
{% endhint %}



This article will walk you through the process of duplicating your vanity account (and your regular key account) on the Xahau network.

### How it works

In order to access an account on the XRP Ledger, you must know the account secret (private keys) for that account. Xaman (formerly Xumm) is an application that helps manage your account secret(s) and allows you to access your XRPL account. This processes will duplicate your vanity account on Xahau, activate it with 2 XAH and authorize Xaman to use the regular key account to sign for your vanity account.

### Getting started...&#x20;

The following process has two requirements:

* Your account must be [**activated**](../../getting-started/how-to-activate-a-new-xrpl-account.md) on the XRPL.
* Your account must be imported into Xaman with full access.

As long as both of these requirements are met, you can follow these instructions.

1\) Launch Xaman and switch to your Primary card account.

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

2\) Tap the following link, then scan the QR with Xaman to get the [Xahau Import xApp](https://xumm.app/detect/xapp:nixer.xahauimport).

{% embed url="https://xumm.app/detect/xapp:nixer.xahauimport" %}

3\) Launch the Xahau Import xApp.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4\) You must accept the _Terms and Conditions_ and the _Privacy Policy_ be
