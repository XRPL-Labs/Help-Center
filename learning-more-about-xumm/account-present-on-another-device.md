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

### The other possibility

For older versions of Xumm, wh

Alternatively there is of course the possibility that someone indeed has access to your secret. Good thing the account has been rekeyed. In that case it would be interesting to try to find out / discover / think of ways the secret could have been compromised, e.g. accidentally shared, cloud account with key compromised, key entered some place (airdrop, name it) in the past. This year March would be when that happened.
