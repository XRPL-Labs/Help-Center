---
description: How to upgrade your account to a stronger encryption algorithm
---

# Upgrading your encryption

{% hint style="info" %}
Before we continue, we want to assure you that the whichever version of Xumm that you are currently using, it is still **very** **safe**. Upgrading your accounts using our new algorithm simply increases the security from very secure to extremely secure. This process is completely optional and while we recommend that you go through the process, it is not required.&#x20;


{% endhint %}

### A Brief background

All versions of Xumm prior to v2.4 use the AES 256-CBC encryption algorithm to encrypt your secret keys on your phone. It is the same algorithm currently used by banks, large businesses and even governments all over the world and is extremely secure.  The AES 256 is also the standard encryption algorithm in the crypto industry and is widely used however...

### Pushing the envelope...

While the AES 256-CBC (Advanced Encryption Standard) still remains the encryption algorithm of choice for governments and financial institutions, it provides only confidentiality (encryption). AES-256-GCM is "state of the art", it's faster and provides both confidentiality and built-in authentication (integrity check). Updating Xumm to this enhanced standard just extends our lead in the crypto space and to be honest, Xumm users have come to expect nothing less than the best. If there was a better way to encrypt your private keys, we would have already implemented it.

### How to upgrade &#x20;

We have made the upgrade process super easy, so if you are ready to upgrade your accounts here are the steps:

Launch Xumm and press **Settings** then **Accounts**:

<figure><img src="../../.gitbook/assets/Encryption - 1.png" alt=""><figcaption></figcaption></figure>

Press the ![](<../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png>) button. Xumm will list your accounts that are eligible to be upgraded.&#x20;

<figure><img src="../../.gitbook/assets/Encryption - 2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You may have noticed in our example that the "Card 1" account is not displayed in the above image. The "Card 1" account is a Xumm (Tangem) card account so it **can not** be upgraded. (Since the private key is stored on the card itself, not in Xumm.)
{% endhint %}

Press the ![](<../../.gitbook/assets/image (3) (3) (1).png>) button beside the account you would like to update, then enter your 6 digit passcode.

<figure><img src="../../.gitbook/assets/Authenticate screen.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
If you have configured the "Extra Security" option for your account in Xumm, it will ask you for your **Signing Password** instead of your 6 digit passcode.
{% endhint %}

The upgrade only takes a few seconds... and.. all done, It's as easy as that!

<figure><img src="../../.gitbook/assets/Encryption - 3.png" alt=""><figcaption></figcaption></figure>

### Frequently asked questions

#### What if I create a new account in Xumm v2.4?

Any new account that is created with Xumm v2.4 uses the new encryption algorithm. There is no need to upgrade it.

#### What if I import an existing XRPL account into Xumm v2.4?

All accounts that are imported into Xumm v2.4 will be automatically upgraded to use the new encryption algorithm. There is no need to upgrade it.
