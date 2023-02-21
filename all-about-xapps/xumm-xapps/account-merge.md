---
description: How to use the Account Merge xApp
---

# Account Merge

### **Background**

The Account Merge xApp is used to delete an XRP Ledger account and send the remaining XRP balance to another XRP Ledger account.

### **Criteria**

In order to use the Account Merge xApp the following criteria needs to be met:

1. Both accounts must be managed by Xumm.
   1. This means that you must have [**imported**](../../getting-started/importing-your-existing-xrpl-account.md) both of your accounts (the one being deleted and the one that will receive the deleted account’s XRP) into Xumm using the account secrets. (Secret numbers, family seed, mnemonic)
   2. As well, you must have **full access** to both accounts. You can not use the Account Merge xApp if either account has been imported with read only access.
2. The two accounts (the one being deleted and the one that will receive the deleted account’s XRP) must both be [**activated** ](../../getting-started/how-to-activate-a-new-xrpl-account.md)on the XRP Ledger. This means that both of them must have met the XRPL base reserve of 10 XRP.
3. All Trust Lines, escrows, payment channels and other objects on the account to be deleted must be removed **before** running the Account Merge xApp.
4. The XRP Ledger charges a 2 XRP fee for deleting an account on the XRPL.
   1. The “fee” for deleting an account on the XRPL is burned.
   2. This fee was implemented to prevent malicious use and discourage people from creating multiple accounts that serve no purpose.
   3. Xumm has nothing to do with this fee.

### **How to find the Account Merge xApp**

You can find the the Account Merge xApp by selecting the following link:

{% embed url="https://xumm.app/detect/xapp:xumm.accountmerge" %}

or simply press the ![](<../../.gitbook/assets/image (7).png>)button at the bottom of the main page then select **View more xApps**. &#x20;

### **Using the Account Merge xApp**

After launching Account Merge, you are presented with this screen:

<figure><img src="../../.gitbook/assets/Account merge - 1.png" alt=""><figcaption></figcaption></figure>
