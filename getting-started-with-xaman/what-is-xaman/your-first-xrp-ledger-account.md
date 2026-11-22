---
description: The three ways to get started, and what to know before you use your account
---

# Your first XRP Ledger account

### Background

Everything you do in Xaman happens through an account on the [XRP Ledger](#user-content-fn-1)[^1]. Your account is where your XRP and tokens are held, and it has its own r-address[^2], which people use to send you funds. Most people create their first account while they install Xaman, but you can add one at any time, and you can have as many as you like.

This article explains the three ways to get your first account into Xaman, and the few things worth knowing before you use it. Each way has its own step-by-step guide, linked below.&#x20;

### Three ways to get your first account

Which way is right for you depends on what you already have:

* **You are new to the XRP Ledger: create a new account.** Xaman creates the account for you and gives you its [account secret](#user-content-fn-3)[^3] as Secret Numbers to write down. See [How to create an XRP Ledger account](how-to-create-an-xrpl-account.md).
* **You already have an account from another wallet: import it.** Enter its account secret in Xaman, and your account appears with its balance and tokens in place. See [Importing your account (XRPL)](../../your-account/importing-your-account/).
* **You have Xaman cards: add your card.** The card creates and keeps its own account secret, so there is nothing to write down. See [How to import your Xaman card](../../your-account/importing-your-account/...a-xaman-tangem-card.md).

### What to know before you use your account

#### Your account secret is the only way back in

Xaman is a self-custody[^4] wallet. Your account secret is stored securely on your phone, and no one else has a copy, including Xaman. If your phone is lost or replaced, your written account secret is the only way to get your account back. Xaman cannot recover it for you.

{% hint style="warning" %}
Without your account secret, a lost or broken phone means losing your account. Write your Secret Numbers down on paper as soon as Xaman shows them, and keep them somewhere private and safe. Never save them in a photo, a note, or a message.
{% endhint %}

#### A new account needs XRP before it can be used

A brand-new account does not exist on the XRP Ledger until someone sends it XRP. This first payment activates[^5] the account. Part of that XRP becomes the account's reserve[^6], which the account keeps for as long as it exists. You can activate your account by buying XRP in Xaman, sending XRP from an exchange, or receiving XRP from someone else. See [Activating an account (XRPL)](../../getting-xrp-into-xaman/how-to-activate-a-new-xrpl-account/) and [Reserves on the XRP Ledger](../../xrp-ledger-resources/xrp-ledger-concepts/about-reserves.md).

An imported account that already holds XRP is already active, so there is nothing more to do. A pre-funded Xaman card comes with enough XRP to activate its account.

#### Full access or Read only

When you add an account, Xaman asks how much control you want in the app:

* **Full access: you can send, sign, and receive.** This is what most people choose for their own accounts.
* **Read only: you can view the balance and receive, but not sign.** This is useful for watching an account you keep elsewhere. You can upgrade it to Full access later.

See [What do "Full" and "Read Only" mean in Xaman?](../../learning-more-about-xaman/what-do-full-and-read-only-mean-in-xaman.md) for more.

### Frequently asked questions

**Can I have more than one account in Xaman?**

Yes. You can create or import as many accounts as you like, and switch between them on the Home screen. Every account has its own account secret, so write each one down separately, and label which account it belongs to.

**Do I need XRP to create an account?**

No. Creating an account in Xaman is free. You only need XRP to activate it, before you can hold XRP or tokens in it.

**Is my account stored inside Xaman?**

No. Your account and its funds are on the XRP Ledger. Xaman keeps your account secret on your phone so you can sign transactions, which is why the same account works in any wallet that has its account secret. See [Where are your funds stored?](where-are-your-funds-stored.md)

**Should I create a new account or import my old one?**

If you already have an account you trust, importing it is simplest, since your funds come along. If you are not sure whether anyone else might have seen its account secret, create a new account in Xaman and send your funds to it. See [Should I import my XRP Ledger account into Xaman?](../../your-account/importing-your-account/should-i-import-my-xrp-ledger-account-into-xaman.md)

### See also

* [Installing Xaman](installing-xaman.md)
* [Self-Custody 101: Staying Safe with Xaman](self-custody-101-staying-safe-with-xaman.md)
* [Fast onboarding](fast-onboarding.md)
* [Xaman cards](../../xaman-cards/xaman-tangem-cards.md)

[^1]: A public network, run by independent computers around the world, that records who owns what. XRP is its native coin.

[^2]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.

[^3]: The secret that controls your account, as Secret Numbers, a family seed, or a recovery phrase. Never share it with anyone.

[^4]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^5]: Sending an account its first XRP, enough to cover its reserve. Until then, the account does not exist on the XRP Ledger.

[^6]: XRP that every active XRP Ledger account must keep and cannot spend. The network sets the amount, and it can change.
