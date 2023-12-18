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
You may have noticed that the Vanity Account says, 'Full access" rather than 'Read only". That is because Xaman recognizes that the regular key account is present and in 'Full access" so it updates the Vanity account from 'Read only' to 'Full access'.
{% endhint %}

### How it works

This processes will duplicate your vanity account on Xahau, activate it with 2 XAH and authorize Xaman to use the regular key account to sign for your vanity account on Xahau. It does this using an xApp called **Xahau Import** to create a _Setregularkey_ transaction on the XRP Ledger, then create an _Import_ transaction on the Xahau network. Signing both of these two transactions will duplicate your vanity account on Xahau, activate it with 2 XAH and authorize Xaman to use the regular key account to sign for your vanity account.&#x20;

### Getting started...&#x20;

The following process has two requirements:

* Your vanity account must imported into Xaman.
* The regular key account (for your vanity account) must be imported into Xaman with full access.

As long as both of these requirements are met, you can follow these instructions.

1\) Launch Xaman and switch to your vanity account.

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

2\) Tap the following link, then scan the QR with Xaman to get the [Xahau Import xApp](https://xumm.app/detect/xapp:nixer.xahauimport).

{% embed url="https://xumm.app/detect/xapp:nixer.xahauimport" %}

3\) Launch the Xahau Import xApp.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4\) You must accept the _Terms and Conditions_ and the _Privacy Policy_ be
