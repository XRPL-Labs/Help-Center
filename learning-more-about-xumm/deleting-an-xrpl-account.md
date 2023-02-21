---
description: How to delete an XRP Ledger account from the XRPL.
---

# Deleting an XRPL account

#### **Before you get started...**

* The AccountDelete transaction is **not accepted** by many crypto exchanges or crypto wallets.
* Once you decide where you would like to send your remaining funds to, you will need to contact them **BEFORE** you attempt to delete your account.
* Even after you delete your account, you should **not throw away your account secret**. Someone may send funds to your account in the future and you will need your account secret to access them

#### **History**

All XRP Ledger accounts need to be activated with a minimum of 10 XRP before you can send and receive tokens to them. The first 10 XRP is marked as un-spendable and is used to meet the base reserve requirements of the XRPL. (Sometimes called the account reserve or wallet reserve)

The XRP Ledger applies these reserve requirements to all accounts in order to protect itself from spam, malicious use and denial-of-service attacks. There is no way around the base reserve. It is a requirement of the XRPL.

In May of 2020, the XRP Protocol was [amended to allow XRPL accounts to be deleted](https://xrpl.org/known-amendments.html#deletableaccounts).

&#x20;

#### **How much does it cost?**

The XRP Ledger has a 2 XRP fee to delete an account in addition to the regular transaction fee. (Which is normally about 0.000015 XRP.) Both of these fees are burned by the XRP Ledger. This means that after you delete your account you should receive about 8 XRP from your 10 XRP base reserve.

&#x20;

#### **Sending the base reserve to a non custodial wallet**

If you would like to send the base reserve to another non custodial account, make sure that the wallet supports the AccountDelete transaction. If they are wisely using Xumm, you are good to go since we support all transaction types on the XRPL, but many other wallets **do not**. Check with them **before** you try deleting your account!

&#x20;

#### **Sending the base reserve to an exchange account**

The XRP Ledger has more than one way to deliver value, so a **proper XRPL implementation** allows for all forms of value (that the XRP Ledger supports) to be accepted. Most crypto exchanges and crypto wallets have configured their systems to **only accept payment transactions.** Since the AccountDelete transaction is **not** a payment transaction, this means you can send funds via AccountDelete but they don't know how to handle it, since it's not a payment.

&#x20;

#### **Can I activate a new account with the AccoutDelete transaction?**

A new account on the XRP ledger **can not** be activated by the AccountDelete transaction. If you try to do this, it will be rejected and you will still be charged the 2 XRP fee. (Which the XRP Ledger will burn.)

&#x20;

#### **Here is the step by step guide to deleting an XRPL account.**

Remember: Most exchanges **do not** accept the Account Transaction

1. Go to: [https://xrpl.services](https://xumm.community/)
2. Sign in with Xumm using the account you want to delete.
3. Select the "Account Delete" option.
4. Enter the r-address where you want your funds to be delivered.
5. Sign the transaction.

#### **I removed my account from Xumm. Why didn't I get the base reserve?**

Removing an account from Xumm is not the same as deleting an account from the XRP Ledger.

(Settings -> Accounts -> Select the _Edit_ button beside the account to be removed -> Press the _Remove from Xumm_ button and confirm on the warning screen.

When an account is removed from Xumm, the account secret is deleted from Xumm, but the account still exists on the XRP Ledger.

&#x20;

If your XRPL account got removed from Xumm in error, it can be imported back into Xumm using the account secret (Secret numbers, Family Seed, Mnemonic) by following the instructions in the following article;

&#x20;

https://support.xumm.app/hc/en-us/articles/360019307399-How-to-import-an-XRP-Ledger-account-using-the-account-secret

#### &#x20;

#### **I already deleted my XRPL account and sent the funds to my exchange account**

If you already deleted your account and sent the remaining funds to a crypto exchange or wallet that does not support the AccountDelete transaction, you will need to **contact your exchange/wallet** and explain what happened. They will need to locate your funds in their system and deliver them to your exchange account. Unfortunately there is **nothing Xumm Support can do** to help you recover your funds. Only your exchange is capable of delivering your funds to your account.&#x20;

&#x20;

#### **Summary**

* **Do not throw away your account secret** (Secret numbers, Family Seed, Mnemonic) after you have deleted your account. You may need it in the future.
* Contact your crypto exchange or destination wallet **before** you delete your account.

&#x20;

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the <mark style="color:blue;">**Xumm Support xApp**</mark> in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>

