---
description: How to rekey an XRPL account
cover: ../.gitbook/assets/Large rock with Key.jpg
coverY: 0
---

# How to Rekey an XRP Ledger (XRPL) Account

### Concept and Implementation

The XRP Ledger allows an account to authorize a secondary key pair, called a [_regular key pair_](https://xrpl.org/cryptographic-keys.html), to sign transactions on  behalf of another account.&#x20;

It is often used to protect an account by securing the master key and using the regular key in its place. This has multiple advantages;

1. The primary account is safer because the master key does not need to be generally available
2. The regular key account does not need to be activated so has no value in and of itself
3. The regular key can be removed or swapped out as needed

### Example

A good example of how this works would be to look at the recommended configuration of a pair of [Xaman (Tangem) cards](../xumm-tangem-cards/xumm-tangem-cards.md).

In this case, you have a Primary account on one card and you have a Signing account on another card.

When you run the [Tangem Backup xApp](broken-reference), it creates a "link" between the two accounts which is called a regular key pair. It connects the Primary account to the Signing account which allows you to sign transactions on the Primary account **using the Signing account**.

The following steps explain how to manually configure a regular key pair between two XRPL accounts.

### Step 1: Make sure you have a Primary account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

The Primary account must be imported into Xaman (formerly Xumm) with **Full access**. (You must be able to sign transactions on this account.)

This is the account that will have your XRP, your Trust Lines, Escrows, DEX transactions, etc.

If you are new to Xaman and don't have an XRP Ledger account yet, you can create one by following the instructions in this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">How to Create an XRP Ledger account</td><td></td><td></td><td><a href="../.gitbook/assets/Creating in forest.png">Creating in forest.png</a></td><td><a href="your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md">how-to-create-an-xrpl-account.md</a></td></tr></tbody></table>

### Step 2: Make sure you have a Signing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

The Signing account must be imported into Xaman with **Full access**. (You must be able to sign transactions on this account.)

This account does not need to contain XRP and does not even need to be activated. As long as you have full access to the account, it can be used to sign transactions on the Primary account.

If you don't have signing account yet, you can create one by following the instructions in this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">How to Create an XRP Ledger account</td><td></td><td></td><td><a href="../.gitbook/assets/Creating in forest.png">Creating in forest.png</a></td><td><a href="your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md">how-to-create-an-xrpl-account.md</a></td></tr></tbody></table>



### Step 3: How to set a Regular Key Pair <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Once you have completed the following steps, you will be able to sign transactions on your Primary account using **both** your Primary account **and** your Signing account.

1\) Launch Xaman and switch accounts to your Signing account.

<figure><img src="../.gitbook/assets/regular keys -2 (1).png" alt=""><figcaption></figcaption></figure>

2\) Press the **Request** button then press the **Copy** button.

<figure><img src="../.gitbook/assets/regular keys -3.png" alt=""><figcaption></figcaption></figure>

3\) Switch accounts to your **Primary** account and go to [**XRP Ledger Services**](https://xrpl.services/)**.**

4\) Press the ![](<../.gitbook/assets/image (1) (6).png>) button then press **Open in Xumm App** and sign in.

<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>

5\) On the XRP Ledger Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/XRPL Services - Reg Key - 1.png" alt=""><figcaption></figcaption></figure>

6\) In the field below paste the r-address for the Signing account, then press the **Send Set Regular Key to Xumm** button.

<figure><img src="../.gitbook/assets/XRPL - Regular keys.png" alt=""><figcaption></figcaption></figure>

7\) Sign the transaction in Xaman and you're all done!&#x20;

Now when you look at your Signing account, notice how Xaman now reports "Regular key for Primary Acct".

<figure><img src="../.gitbook/assets/regular keys -4.png" alt=""><figcaption></figcaption></figure>

### Next steps..

If you configured the regular key so you would have a second signing account (E.g. as a "backup" account) you are all set to go. You should be able to sign transactions on your Primary Account with either your Signing account or your Primary account.

...but if you configured the regular key because your Primary account has been **compromised**, you are only half way there. The next step is to disable the master key for your Primary account.

&#x20;This article explains how to proceed:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">How to disable the Master key</td><td></td><td></td><td><a href="how-to-disable-the-master-key.md">how-to-disable-the-master-key.md</a></td><td><a href="../.gitbook/assets/Large rock with Lock -2.jpg">Large rock with Lock -2.jpg</a></td></tr></tbody></table>
