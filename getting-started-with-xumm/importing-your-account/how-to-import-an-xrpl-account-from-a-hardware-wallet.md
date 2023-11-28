---
description: Importing an XRPL account created on a hardware wallet
---

# How to import an XRPL account from a hardware wallet

### The Concept

A "cold wallet" generates and stores an XRP Ledger account secret on a USB device. Some people feel that this is a safer way to generate and store account secrets. The assumption is that since the device is not directly connected to the internet, it is less vulnerable to potential attack vectors and therefore 'safer' than a "hot wallet" like Xumm.

### Bringing your cold wallet online

It is important that you understand how this works.

By bringing your hardware wallet account into Xumm, you are changing the nature of how you plan to interact with the XRP Ledger.  Hardware wallets are largely about **long term storage** of your assets. Xumm is largely about participating in the the XRPL community.&#x20;

By following these instructions, you will be able to access all of your XRPL assets stored in your&#x20;

{% hint style="warning" %}
By following these instructions, you will be able to access all of your XRPL assets stored in your hardware wallet using Xumm. This means that you will not need your hardware wallet to access your XRP. You will be able to access it with Xumm.
{% endhint %}

&#x20;

### Importing your XRP Ledger account created on your Ledger device

There are cases where you might want to import a XRPL account create on a hardware wallet into Xumm. Here is how to do it:

1\) On your phone, create a new XRP Ledger account in Xumm.&#x20;

{% content-ref url="../your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md" %}
[how-to-create-an-xrpl-account.md](../your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
{% endcontent-ref %}

2\) Press the **Request** button on the main page of Xumm. You should see a screen that looks like this:

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

3\) Get your **hardware wallet,** go to a computer and press [**here**](https://www.xrptoolkit.com/) to go to [**XRP Tool Kit**](https://www.xrptoolkit.com/)**.**

4\) Sign into XRPToolkit.com with your hardware wallet then choose the **Account** menu and select **Signers**.

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

5\) In the **Assign Regular Key** section, press the QR code button in the _Regular key_ field, then scan the QR code from Xumm on your phone. (The one from Step 2 above.) Alternatively, you can manually enter your Xumm r-address in the _Regular key_ field.

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

7\) Sign the transaction with your hardware wallet.

8\) On your phone, import your XRPL account create on your hardware wallet into Xumm in **read only mode**.&#x20;

{% content-ref url="...in-read-only-mode.md" %}
[...in-read-only-mode.md](...in-read-only-mode.md)
{% endcontent-ref %}

{% hint style="info" %}
Importing your hardware wallet account into Xumm in read only mode **does not** require entering your mnemonic (private key) into Xumm. It only requires that you enter your r-address (public key).&#x20;
{% endhint %}

### How it works

If you successfully followed the above instructions, you should be able to sign transactions on your hardware wallet account, using the new XRP Ledger account you created in Xumm. Since you imported your hardware wallet account into Xumm in **read only** mode, your private key was not brought "online" and still remains on your hardware wallet.

If you are interested in learning more about how regular key pairs work on the XRP Ledger, please visit this site:

{% embed url="https://xrpl.org/assign-a-regular-key-pair.html" %}

&#x20;&#x20;
