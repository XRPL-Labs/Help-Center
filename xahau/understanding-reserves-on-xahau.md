---
description: What are 'reserves' on the Xahau network?
---

# Understanding Reserves on Xahau

## Xahau basics

In order to understand what reserves are, you should be aware of the four main properties of how an **account** on Xahau works.

1\) Accounts are the central data structure on the Xahau network. An account holds balances, signs transactions, and can issue assets on Xahau.&#x20;

2\) An account on Xahau has two basic states:

* Activated
* Un-activated&#x20;

3\) For an account to exist on Xahau, it only requires a valid keypair (also known as a private key or an account secret)

4\) If you wish to hold assets in a Xahau account, it must be activated and hold a minimum balance of XAH coins. This minimum balance is called the 'base reserve' or an 'account reserve".

### Two Types of reserves

The Xahau network actually has two types of reserves:

* Base reserve (called the wallet reserve or account reserve)
* Owner reserve

Both of these reserves are enforced by the Xahau network. (Xaman has no control over either of them.)

### **Base reserve**

In order to activate an account, it must receive 1 XAH which is used to meet the base reserve requirement of the Xahau network. The base reserve is the minimum amount of XAH an account must contain in order to remain active.&#x20;

{% hint style="info" %}
For example, if you activate a new account with 10 XAH, 1 XAH will be automatically be marked as 'un-spendable' and held by the Xahau network to cover the base reserve requirement, while the remaining 9 XAH will be free to use as you wish.

If you activated a new account with 1 XAH, it would be automatically will be automatically marked as 'un-spendable' and held by the Xahau network to cover the base reserve requirement, leaving no available XAH to be used.
{% endhint %}

#### Summary

* The base is reserve is required to activate an Xahau account and needs to be maintained in order to submit transactions to the Xahau network.
* The current base reserve is **1 XAH**.&#x20;
* The base reserve is a function of the Xahau network, not of Xaman.
* It can only be recovered by deleting account from the XRPL.

### &#x20;O**wner reserves**

These reserves apply to objects on Xahau that you own in your account. The owner reserve is currently set at **0.2 XAH** per object.

Here is a list of objects that require an owner reserve:

* An escrow
* An open offer on the Decentralized Exchange (DEX)
* A Trust Line for a token
* Signer list (Multi-sign)
* Checks
* Payment channels

Owner reserves can be recovered when the object is removed from the account. (i.e.. By finishing an escrow, deleting or fulfilling your offer on the decentralized exchange, removing your Trust Line, etc.)

Many of these operations can be performed in Xaman or by visiting Xahau Services at:

* [Xahau Services](https://xahau.services/)

### **Frequently Asked Questions**

#### **Can I access or recover the base reserve from my account?**

No. The base reserve can not be accessed or recovered. It will remain locked in your account forever. There is no way to recover it.

#### **Does Xaman control the reserves on my account?**

No. The base reserve and owner reserves are a function of the Xahau blockchain. They have nothing to do with Xaman. Reserves are automatically applied by Xahau.

#### **Where does the reserve amount go? Does Xaman hold it?**

Any reserve that is applied to your account, **stays in your account.** The Xahau network simply marks the reserve amount as 'un-spendable'. When the object is removed from your account, the reserve is marked as 'spendable' again. Xaman **does not** have access to your funds nor is Xaman involved in the Xahau reserves in any way.

#### **How can I see my account reserves in Xaman?**

On the main page of Xaman, press the **Reserved** button.

<figure><img src="../.gitbook/assets/Reserves - Screen 1.png" alt=""><figcaption></figcaption></figure>

Xaman should display the following screen:

<figure><img src="../.gitbook/assets/Reserves - Screen 2.png" alt=""><figcaption></figcaption></figure>
