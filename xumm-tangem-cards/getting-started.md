---
description: Just received your Xumm cards?
---

# Getting started with your new cards 🤗

If you just received your Xumm (Tangem) cards and you are not sure what to do with them or how to configure them, this is exactly where you want to be. We are going to go over the basics of the cards, how to use them, and answer some common questions related to the cards.

### Taking a look at the cards

Most people will receive two cards:

<figure><img src="../.gitbook/assets/Xumm Tangem card -3.png" alt=""><figcaption></figcaption></figure>

Just to confirm, the cards are exactly the same, other than their appearance. We sent you two different cards so you can easily tell them apart!&#x20;

### What are the cards for...

The main functions of a Xumm card are:

* to securely create an account secret for an XRP Ledger account
* to safely store that account secret on the card
* to sign transactions on the card's account

There are multiple use cases and ways to configure the cards, but the core feature of a card is that it allows you to sign transactions on the XRPL account that the card creates.

Keep in mind, since the account secret is stored on the card, this means that the only way you can sign transactions on the card's account, is if you **physically have** the card. While this feature certainly improves security, for some people it might be considered less convenient than a regular XRPL account. (Without the card, you can't interact with the XRPL.)

We make a couple of recommendations below which you should review to better understand this.

### What the cards are not for...

The cards **can not** be used:

* to connect to your bank account.&#x20;
* at an ATM or bank machine.&#x20;
* as a debit card or a credit card.

### Existing XRPL accounts

Most people will already have an existing XRP Ledger account and may not be sure how to integrate their existing accounts with their new Xumm cards. While this is possible to integrate the cards with existing accounts, it is not advised. Integrating hardware wallet accounts and software wallet accounts is not ideal.

For more information about this, please refer to this article:

{% content-ref url="how-to-link-a-xumm-tangem-card-to-an-existing-xrpl-account.md" %}
[how-to-link-a-xumm-tangem-card-to-an-existing-xrpl-account.md](how-to-link-a-xumm-tangem-card-to-an-existing-xrpl-account.md)
{% endcontent-ref %}

### Our recommendations...

#### Make a backup card

This is the main reason we send you two cards. We want you to create a "backup" card so you can still access your funds if your primary card is ever lost, stolen or damaged. Check out this article on how to do this:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">Xumm (Tangem) card backup</td><td></td><td></td><td><a href="../.gitbook/assets/Rocky stream.png">Rocky stream.png</a></td><td><a href="how-to-configure-a-backup-signing-account.md">how-to-configure-a-backup-signing-account.md</a></td></tr></tbody></table>

#### Create a pin on your backup card

If you decide to follow our first recommendation, creating a pin on your backup card is an extra security feature which makes sense to help protect your funds. Each Xumm card offers the ability to create a pin code which will need to be entered before you can sign a transaction using the card. If your card were ever stolen, a pin will help keep the card from being used by unauthorized people.

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">Creating a pin on your card</td><td></td><td></td><td><a href="../.gitbook/assets/Waterfall.png">Waterfall.png</a></td><td><a href="creating-a-pin-on-your-xumm-tangem-card.md">creating-a-pin-on-your-xumm-tangem-card.md</a></td></tr></tbody></table>

#### Read the following article

We have compiled a set of suggestions on how to use your Xumm (Tangem) cards. A sort of "Do's and Don'ts" list of things to avoid and things to try to practice when it comes to your cards.

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">Best security practices for your Xumm (Tangem) card</td><td></td><td></td><td><a href="../.gitbook/assets/Water fall - 2.png">Water fall - 2.png</a></td><td><a href="best-security-practices-using-a-xumm-card.md">best-security-practices-using-a-xumm-card.md</a></td></tr></tbody></table>

### Additional Questions

#### Tell me more about the "backup " process

The ideal way to configure the cards is to:

* Import two Xumm cards into Xumm
* Create a Primary and Signing account, then link them together using the Tangem Backup xApp.
* Move the majority of your assets to the Primary account, then put the card into a safe, secure storage location.

With the Xumm cards, we utilize the "regular key" feature on the XRP Ledger to accomplish the "link" between cards. You create a new XRPL account on one card. (the "Primary" account) then you create another XRPL account on a second card. (The "Backup" account). Once you have done this, you link the two cards together using the regular key feature on the XRP Ledger. The "link" allows you to sign transactions on the Primary account with the Backup account.&#x20;

If you were to lose the Backup card (or if it was damaged, stolen, destroyed, etc.) you would just disable to the card and use the Primary card to access the Primary account. You could easily configure or link the Backup card if you found it again, or you could just configure a new Backup card if you wanted to.

#### I have three cards. What do I do with the third one?

As mentioned above, we use the "regular key" feature of the XRP Ledger to "link' two card accounts together. (This effectively allows the "backup" card to sign transactions on the Primary card's account. ) The XRPL only allows for one regular key to be set per account, so this limits the number of backup cards that can be configured to one card.

So what can a third card be used for?

Basically it all depends on how you plan to interact with the XRP Ledger community. For some people. the third card is just put away in a safe place in case something happens to one of the other two cards. (Sort of like a spare card in case one of the others are damaged or lost.)

Some people use it as a dedicated account for gambling, or for NFTs or a dedicated trading account. Some use it for testing features on the XRPL or as a daily spending account.

Other people give it away to a friend or family member to introduce the XRP Ledger to them.

For advanced users, the XRP Ledger has a feature called [**Multi-signing**](https://xrpl.org/multi-signing.html) which allows multiple XRPL accounts to be linked together for signing purposes. The third card can be used in a multi-sign configuration if desired.

So it all comes down to how you are going to participate in the XRPL ecosystem.

From here, there are two main paths to follow:

#### Option 1

Once your assets have been moved to your Primary card account, you can delete your existing account (and [recover the base reserve](../learning-more-about-xumm/deleting-an-xrpl-account.md)).  This leaves you with one XRP Ledger account and just use your Signing card when you want to interact with the XRP Ledger. This is the simplest and easiest way to manage your XRPL accounts.&#x20;

**Option 2**

Once your assets have been moved to your Primary card account, you can continue to use your existing XRPL account in **conjunction** with your new Primary account. For example, you could transfer small amounts of XRP from your Primary card account to your existing account and use it for your daily interactions and leave your Signing card at home. This way, you never have to carry your Signing card, so there is no chance of it getting lost or stolen. As well, you will have access to some XRP in your existing account, but the majority of your XRP is safely stored in your Primary account. (In other words, your Primary card account is used for long term storage and your existing account would be used for day to day transactions.)

#### Option 3

There are several other ways to configure the cards as well, including: making a Xumm card a backup to an existing account, making an existing card a backup to an Xumm card account, managing multiple Xumm card accounts alongside multiple regular accounts or configuring multiple accounts using the multi-sign feature of the XRPL. Each of these options have their pros and cons, but for most people, the above two options will be the better solutions.



A Xumm (Tangem) card is basically an "account on a card", and that the only way to access the card account is if you physically possess the card, so consider this possibility...

What happens if your card is lost, stolen, damaged or destroyed?

{% hint style="danger" %}
If any of these situations happened, you would lose access to your account and your **funds would be lost**.  The only way to access your card account is if you have the card, unless you configure a backup.&#x20;
{% endhint %}

&#x20;This leads us to our recommendations...

### Summary

The Xumm card is a hardware wallet that offers peace of mind by providing a reliable and secure storage solution for your private keys for your XRPL account. Should you have any additional questions regarding this topic, you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm.
