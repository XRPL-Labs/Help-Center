---
description: Importing an XRPL account created on a hardware wallet
---

# How to import an XRPL account from a hardware wallet

### Bringing your hardware wallet online

It is important that you understand what this article does. It changes how you access your XRP Ledger account managed by your hardware wallet.

Hardware wallets are largely about **long term storage** of your assets. A hardware wallet stores the  private keys for your XRP Ledger account on a device that is not connected to the internet. You can only sign transactions on your XRPL account if you are in possession of the hardware device. By storing your private keys off line, it limits some potential attack vectors on your account.

Xumm is largely about enabling you to interact with the XRP Ledger ecosystem. Xumm stores your private keys for your XRP Ledger account on your mobile device, which is connected to the internet. It allows you to sign transactions on your XRPL account on your phone. By storing your private keys on a device that is "on line", it exposes your account to other types of potential attack vectors.&#x20;

{% hint style="warning" %}
By following these instructions, you will be able to access **all of your XRPL assets** stored in your hardware wallet **using Xumm**. This means that you will not exclusively need your hardware wallet to access your XRP. You will be able to access it with Xumm in addition to being able to access it with your hardware wallet.
{% endhint %}

We strongly recommend you read this article before continuing:

{% content-ref url="should-i-import-my-xrpl-account-into-xumm.md" %}
[should-i-import-my-xrpl-account-into-xumm.md](should-i-import-my-xrpl-account-into-xumm.md)
{% endcontent-ref %}

### Importing your XRP Ledger account created on your hardware device



1\) On your phone, create a new XRP Ledger account in Xumm.&#x20;

{% content-ref url="../your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md" %}
[how-to-create-an-xrpl-account.md](../your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
{% endcontent-ref %}

<figure><img src="../../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>



2\) Press the **Show account QR** button. You should see a screen that looks like this:

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

<figure><img src="../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Importing your hardware wallet account into Xumm in read only mode **does not** require entering your mnemonic (private key) into Xumm. It only requires that you enter your r-address (public key).&#x20;
{% endhint %}



### How it works

If you successfully followed the above instructions, you should be able to sign transactions on your hardware wallet account, using the new XRP Ledger account you created in Xumm. Since you imported your hardware wallet account into Xumm in **read only** mode, your private key was not brought "online" and still remains on your hardware wallet.

If you are interested in learning more about how regular key pairs work on the XRP Ledger, please visit this site:

{% embed url="https://xrpl.org/assign-a-regular-key-pair.html" %}

&#x20;&#x20;
