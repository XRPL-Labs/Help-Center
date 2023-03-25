---
description: >-
  Account present on another device. Your XRPL account has been added to another
  device
---

# Account present on another device

You have just received the following message in Xumm:

<figure><img src="../.gitbook/assets/Account Present.png" alt=""><figcaption></figcaption></figure>

### Explanation

In most cases, this is an automated message sent when you get a new phone and install Xumm for the first time. Once you import your existing account secret into Xumm, it recognizes that you have a new device which sends this above notification.

If you just imported your account into a new device, there is nothing to worry about.

### Older versions of Xumm

For older versions of Xumm, when an account tries to reach out to our backend servers to interact with the XRPL via an xApp or a sign request, it would trigger an automated push notification and deliver the above message.&#x20;

It did not necessarily mean an account had been added to another device, it just meant that the account had contacted our backend for the first time. Xumm did not know which device it was, only that your r-address tried to connect to the XRPL via our servers.&#x20;

Normally the account was installed on two devices and one of those devices recently tried to use it. (E.g. mobile & second smartphone, or tablet)

### Take this warning seriously!

Are goal here is to warn you that something is possibly wrong with your account.

Try to think of think of ways your account secret could have been compromised. Have you shared it with someone? Was it stored on a cloud account? On your PC? Mobile device? Have you entered your account secret someplace? A google form? A crypto wallet? Website? Airdrop?&#x20;

If there is even a chance, it is time to act **immediately**. This warning means that your account secret is exposed &#x20;

[\
6:33 PM](https://mm.xrpledger.foundation/xrpl-labs/pl/snrjn8mntpb78xqba9etbksi5c)

We have to make sure they understand this does not just happen: this means that their secret is exposed, and that this is not a Xumm issue but that their entire security (usernames, passwords), etc. can be at risk.

As they have been compromised

you should consider re-keying your account as a safety precaution.

Here is how to do this:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">How to re-key your XRPL account</td><td></td><td></td><td><a href="../getting-started-with-xumm/how-to-rekey-your-account.md">how-to-rekey-your-account.md</a></td></tr></tbody></table>

Re-keying your account you should disable the master keys for your compromised account.

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th></th></tr></thead><tbody><tr><td align="center">How to disable the Master keys on an account</td><td></td><td></td></tr></tbody></table>
