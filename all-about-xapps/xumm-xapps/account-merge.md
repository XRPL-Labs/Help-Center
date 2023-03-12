---
description: How to use the Account Merge xApp
---

# Account Merge

{% hint style="info" %}
This article is currently under construction
{% endhint %}

### **Background**

The Account Merge xApp is used to delete an XRP Ledger account and send the remaining XRP balance to another XRPL account managed by Xumm.

### **Criteria**

In order to use the Account Merge xApp the following criteria needs to be met:

1\) Both accounts must be managed by Xumm.

* This means that you must have [**imported**](../../getting-started-with-xumm/importing-your-account/) both of your accounts (the one being deleted and the one that will receive the deleted account’s XRP) into Xumm using the account secrets. (Secret numbers / Family seed / Mnemonic)

2\) Xumm must have full access to both accounts.

* You can not use the Account Merge xApp if either account has been imported with read only access.

3\) Both account must be activated.

* This means that both accounts must have met the XRPL base reserve requirement of 10 XRP.

4\) All Trust Lines, escrows, payment channels and other objects on the account to be deleted must be removed **before** running the Account Merge xApp.



### **How to find it**

Simply touch this link:

****[**Account Merge**](https://xumm.app/detect/xapp:xumm.accountmerge)****

or you can find it by pressing the <img src="../../.gitbook/assets/image (2) (5).png" alt="" data-size="line"> button at the bottom of the main screen in Xumm then select ![](<../../.gitbook/assets/image (2) (6) (1).png>)\


<figure><img src="../../.gitbook/assets/Account merge - xApp - 1.png" alt=""><figcaption></figcaption></figure>

### **Using the Account Merge xApp**

After launching Account Merge, you are presented with this screen:

<figure><img src="../../.gitbook/assets/Account merge - 1.png" alt=""><figcaption></figcaption></figure>
