---
description: How to migrate from Toast Wallet to Xaman
---

# How to migrate from Toast Wallet to Xaman

### Disclaimer

The information contained in this article is provided on a "best effort" basis. We do not provide technical support for Toast wallet.

### Prerequisites

This article assumes the following:

* You have an existing XRP Ledger account managed by Toast Wallet
* You know the "passphrase" for your XRP Ledger account

If you have lost your passphrase or do not have the correct one for your account, we will not be able to assist you. You **must** have the correct passphrase otherwise this process will not work.

### Instructions

1\) Launch Toast wallet and sign in using your passcode.

<figure><img src="../.gitbook/assets/Toast wallet - 5.png" alt=""><figcaption></figcaption></figure>

2\) Select your XRP Ledger account.

<figure><img src="../.gitbook/assets/Toast wallet - 6.png" alt=""><figcaption></figcaption></figure>

3\) Select the '**Show Secret**' button.

<figure><img src="../.gitbook/assets/Toast Wallet - 2.png" alt=""><figcaption></figcaption></figure>

4\) Enter the passphrase for your XRPL account then select '**Reveal Secret**' button.

<figure><img src="../.gitbook/assets/Toast Wallet - 3.png" alt=""><figcaption></figcaption></figure>

5\) Copy the 'Account Secret'.

<figure><img src="../.gitbook/assets/Toast Wallet - 4.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
The account secret is the private key for your XRP Ledger account. It is vital that you **do not** share it will anyone. If someone was able to learn your account secret, they would have complete access to your XRPL account. It is very important that no one else can see or access it.&#x20;
{% endhint %}

### 3. Copy the Account Secret string (starting with 's') <a href="#h_b12d96d811" id="h_b12d96d811"></a>

_Now you are ready to import the secret into XUMM. Open_ [_XUMM_](https://web.archive.org/web/20220121231212/https://xumm.app/)_, and:_&#x20;

### 4. **Select "Switch account" in the home screen (upper right corner** <a href="#h_0b9dd3604b" id="h_0b9dd3604b"></a>

### **5. Select "Add Account"** <a href="#h_d314a908af" id="h_d314a908af"></a>

**6. Select "Import existing" » "Full access" » "Family Seed"**

Select **"Import existing account"**

Select **"Full access"** account type

Select a **"Family Seed"**

### **6. Enter the s... code copied from Toast** <a href="#h_f4d69ffb83" id="h_f4d69ffb83"></a>

Now type or or **paste** your **"Family Seed" (the code starting with a lower case "s")** you got from Toast, in **Step 4**.

### Done 🎉 <a href="#h_d6f25015ac" id="h_d6f25015ac"></a>

**Now PLEASE CLEAR your clipboard**

&#x20;

It is possible to use the XUMM camera function by restoring the backup code to a browser version of Toast revealing the secret there and scanning the QR code by selecting the rectangle on the left of the Account Seed input field in XUMM.
