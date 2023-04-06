---
description: How to delete an XRP Ledger account from the XRPL.
---

# Deleting an XRPL account

### The instructions..

1\) Go to [<mark style="color:blue;">**XRPL Services**</mark>](https://xrpl.services)

2\) Sign in with Xumm using the account you would like to delete

3\) Select the **Account delete** option

4\) Enter the r-address where you would like your funds delivered to.

5\) Sign the transaction.

### Important things to consider

* If you plan to send your remaining funds to a crypto exchange or to another wallet, please make sure that they support the [_accountdelete_](https://xrpl.org/accounts.html#deletion-of-accounts) transaction on the XRPL. Many do not.&#x20;
* The XRP Ledger has a 2 XRP fee to delete an account. (in addition to the regular transaction fee) This means that after you delete your account you should receive about 8 XRP from your 10 XRP base reserve.
* A new account on the XRP Ledger **can not** be activated by the [_accountdelete_](https://xrpl.org/accounts.html#deletion-of-accounts) transaction. If you try to do this, it will be rejected and you will still be charged the 2 XRP fee.&#x20;
* Even after you delete your account, you should **not throw away your account secret**. Someone may send funds to your account in the future and you will need your account secret to access them.

### Frequently asked questions

#### **I removed my account from Xumm. Why didn't I get the base reserve?**

Removing an account from Xumm is not the same as deleting an account from the XRP Ledger.

When an account is removed from Xumm, the account secret (Secret numbers / Family seed / Mnemonic) is deleted from Xumm, but the XRPL account still exists on the XRP Ledger.

To delete an XRPL account, you need to follow the instructions above.

{% hint style="warning" %}
&#x20;If your XRPL account was removed from Xumm in error, it can be imported back into Xumm using the account secret (Secret numbers / Family Seed / Mnemonic) by following the instructions here:\
\
[**Importing your account into Xumm**](../getting-started-with-xumm/importing-your-account/)
{% endhint %}

#### **I deleted my XRPL account and sent the funds to my exchange account**

If you already deleted your account and sent the remaining funds to a crypto exchange or wallet that does not support the [accountdelete](https://xrpl.org/accounts.html#deletion-of-accounts) transaction, you will need to **contact your exchange/wallet** and explain what happened.&#x20;

They will need to locate your funds in their system and deliver them to your exchange account.&#x20;

Unfortunately there is **nothing Xumm Support can do** to help you recover your funds. Only your exchange is capable of delivering your funds to your account.&#x20;



**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the <mark style="color:blue;">**Xumm Support xApp**</mark> in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>

