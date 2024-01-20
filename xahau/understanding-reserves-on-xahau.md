---
description: What are 'reserves' on the Xahau network?
---

# Understanding Reserves on Xahau

### Xahau basics

Accounts are the central data structure on the Xahau network. An account holds balances, signs transactions, and can issue assets on Xahau.&#x20;

For an account to exist on Xahau it only requires a valid keypair (also known as private keys or an account secret), however, if you wish to hold assets in a Xahau account, it must hold a minimum balance of XAH coins. This minimum balance is called the 'base reserve' or an 'account reserve".

### Two Types of reserves

The Xahau network actually has two types of reserves:

* Base reserve (called the wallet reserve or account reserve)
* Owner reserve

Both of these reserves are enforced by the Xahau network. (Xaman has no control over either of them.)

**Base reserve**

An account on Xahau has two basic states:

* Activated
* Un-activated&#x20;

In order to activate an account, it must receive 1 XAH which is used to meet the base reserve requirement of the Xahau network. The base reserve is the minimum amount of XAH an account must contain in order to remain active.&#x20;

{% hint style="info" %}
For example,&#x20;
{% endhint %}

This reserve is required to activate an XRPL account and needs to be maintained in order to submit transactions on the XRPL. The current base reserve is **10 XRP**. Each XRPL account must contain at least 10 XRP, which is automatically marked as un-spendable by the XRPL, in order to be able to transact on the XRPL. The base reserve cannot be used or sent to other accounts. It can only be recovered by deleting account from the XRPL.

_Fun fact!_ When the XRPL was first created the base reserve was 1000 XRP! It was reduced to 200 XRP, then to 20 XRP and has now settled to 10 XRP. (The XRPL validators monitor the state of the network and can vote to change the reserve amounts as the blockchain evolves.)&#x20;

&#x20;

#### **Owner reserves**

These reserves apply to objects on the XRPL that you own in your account. The owner reserve is currently set at **2 XRP** per object.

Here is a list of objects that require an owner reserve:

* An escrow
* An open offer on the Decentralized EXchange (DEX)
* A Trust Line for a token
* SIgner list (Multi-sign)
* Checks
* Payment channels
* NFT's (minted prior to the XLS-20 amendment)
* NFTTokenpage ( 2 XRP per page)

Owner reserves can recovered when the object is removed from the account. (i.e.. By finishing an escrow, deleting or fulfilling your offer on the decentralized exchange, removing your Trust Line, etc.)

Many of these operations can be performed in Xumm or by visiting XRPL Services at:

* [XRPL Services](https://xrpl.services/tools)

### **Does Xumm impose the reserves on my account?**

No. The base reserve and owner reserves are a function of the XRP Ledger. They have nothing to do with Xumm. Reserves are automatically applied to your account or to the object you own in your account.

### **Where does the reserve amount go? Does Xumm hold it?**

Any reserve that is applied to your account, **stays in your account.** The XRP Ledger simply marks the reserve amount as 'unspendable'. When the object is removed from your account, the reserve is marked as 'spendable' again. Xumm **does not** have access to your funds nor is Xumm involved in the XRPL reserves in any way.

### **How can I see my account reserves in Xumm?**

On the main page of Xumm, press the **Reserved** button.

<figure><img src="../.gitbook/assets/v24 - Reserves -1.png" alt=""><figcaption></figcaption></figure>

Xumm should display your **Account balance**, the amount of XRP A**vailable for spending** and a list of **Reserved on ledger** on your account.

<figure><img src="../.gitbook/assets/v24 - Reserves -2.png" alt=""><figcaption></figcaption></figure>

In the above example, you can see that the account has 10 XRP marked as un-spendable to meet the wallet reserve and 2 XRP marked as un-spendable to meet the owner reserves for each of the Trust Lines created in the account. &#x20;

### **On my list is a line titled: NFTokenPages**

When a NFT is minted on the XRPL, an object called _NFTokenpage_ is created to 'store" it.

An NFTokenpage is an object on the XRPL so it requires a 2 XRP owner reserve.&#x20;

If you would like to recover the 2 XRP for this object you need to get rid of all of the NFTs stored on this page. The site where you minted/purchased your NFTs will have instructions on how to do this.

NFTokenpage concept is a bit of a complicated topic but if you are interested in learning more about it, here's a link to an excellent resource:

* [https://xrpl.org/nftokenpage.html](https://xrpl.org/nftokenpage.html)

### **How do I recover the Wallet reserve?**

As mentioned above, each XRPL account **must** contain at least 10 XRP to meet the base reserve requirement of the XRP Ledger. If you would like to recover the base reserve, the only way to do this is to delete your account from the XRPL.

There is a 2 XRP fee for doing this which is levied by the XRPL along with the normal transaction fee which applies to all transactions.

(These fees are part of the XRP Ledger and are in **not** related to Xumm.)

For more information about how to delete an account from the XRPL, please review this article:

*
