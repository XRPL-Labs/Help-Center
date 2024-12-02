---
description: How to delete an XRP Ledger account from the XRPL.
---

# Deleting an XRPL account

### The instructions..

1\) Go to [<mark style="color:blue;">**XRPL Services**</mark>](https://xrpl.services)

2\) Sign in with Xaman using the account you would like to delete.

3\) Select the **Account delete** option.

<figure><img src="../.gitbook/assets/Delete your account.png" alt=""><figcaption></figcaption></figure>

4\) Enter the r-address where you would like your funds delivered to.

5\) Sign the transaction.

### Important things to consider

* If you plan to send your remaining funds to a crypto exchange or to another wallet, please make sure that they support the [_accountdelete_](https://xrpl.org/accounts.html#deletion-of-accounts) transaction on the XRPL. Quality exchanges such as [GateHub](https://gatehub.net/) support it, but many **do not**.&#x20;
* The XRP Ledger has a 0.2 XRP fee to delete an account. (In addition to the regular transaction fee.) This means that after you delete your account you should receive about 0.79999 XRP from your 1 XRP base reserve.
* A new account on the XRP Ledger **can not** be activated by the [_accountdelete_](https://xrpl.org/accounts.html#deletion-of-accounts) transaction. If you try to do this, it will be rejected and you will still be charged the 0.2 XRP fee.&#x20;
* Even after you delete your account, you should **not throw away your account secret**. Someone may send funds to your account in the future and you will need your account secret to access them.

### Frequently asked questions

#### **I removed my account from Xaman. Why didn't I get the base reserve?**

Removing an account from Xaman... (Settings -> Accounts -> Edit -> Remove from Xaman)

<figure><img src="../.gitbook/assets/Remove from Xaman.png" alt=""><figcaption></figcaption></figure>

...is not the same as deleting an account from the XRP Ledger.

When an account is removed from Xaman, the account secret (Secret numbers / Family seed / Mnemonic) is deleted from Xaman, but the XRPL account still exists on the XRP Ledger.

To delete an XRPL account, you need to follow the instructions above.

{% hint style="warning" %}
If your XRPL account was removed from Xaman in error, it can be imported back into Xaman using the account secret (Secret numbers / Family Seed / Mnemonic) by following the instructions here:\
\
[**Importing your account into Xaman**](../getting-started-with-xaman/importing-your-account/)
{% endhint %}

#### **I deleted my XRPL account and sent the funds to my exchange account**

If you already deleted your account and sent the remaining funds to a crypto exchange or wallet that does not support the [accountdelete](https://xrpl.org/accounts.html#deletion-of-accounts) transaction, you will need to **contact your exchange/wallet** and explain what happened.&#x20;

They will need to locate your funds in their system and deliver them to your exchange account.&#x20;

Unfortunately there is **nothing Xaman Support can do** to help you recover your funds. Only your exchange is capable of delivering your funds to your account.&#x20;

#### **I still have NFTs in my account so I can not delete it. What should I do?**

You can not own **any objects** in your XRP Ledger account, including NFTs, if you plan to delete it. This means that you need to either sell your NFTs or delete them. For instructions on how to do this, contact the site where you acquired the NFTs from and they should be able to assist you.

#### **I removed all the NFTs in my account but I still can not delete it. What should I do?**

If you have ever minted an NFT and it still exists on the XRP Ledger, you will not be able to delete your account until the NFT(s) that you minted have been burned. (This is a requirement of the the NFT implementation on the XRP Ledger (See the [XLS-20 amendment](https://github.com/XRPLF/XRPL-Standards/discussions/46)), and as a XRPL requirement, cannot be by-passed)  You will need to track down the NFT you minted and make arrangements for it to be deleted. Once you have done that you should be able to delete your XRPL account.
