---
description: Understanding SPAM
---

# Spam on the XRP Ledger

### **What is spam?**

Spam on the XRP Ledger is any unsolicited transaction that someone broadcasts to you in bulk. It can be a payment of XRP or of a token, a message in the transaction's memo field, or an otherwise empty transaction sent only to fill the ledger.

Most spam falls into a few buckets:

* a marketing push to get you to join a project
* a scam that wants you to visit a website
* a scam that wants you to buy an NFT
* a scam that wants you to message the sender for "help"
* an empty transaction sent only to clog the network

The spam transaction itself is not the danger. **It is the bait behind it.**

### What the sender is trying to do

The goal is to reach you and get a reaction. Usually the sender wants you to click a link, buy a token, or reply to them. Some of it is empty: a blank transaction costs the sender almost nothing, and it exists only to make your history noisier.

A few details matter:

* The sender pays the network fee. Spam never costs you XRP to receive.
* The memo is the hook. It is where the link or the "help" request lives.
* If the spam is a token, it usually lands in your balance because you already hold a trust line to that issuer, so the sender picked an address they knew could receive it.

### What it looks like

* A message you did not ask for, often the same text many accounts received.
* A tiny token you do not recognize sitting in your balance.
* A memo with a link, an NFT offer, or a request to "contact support".
* Nothing at all: an empty transaction with no memo and no amount you care about.
* A sudden burst of several of the above, from addresses you have never dealt with.

### Is my account compromised?

No. A spam transaction:

* does not spend your XRP
* does not cost you network fees
* does not change any settings on your account
* does not give the sender any access to your account
* cannot be reversed, deleted, or "removed" by you or by anyone else — it is a completed, public transaction.

The only thing spam changes is your transaction history. Nobody can read your account secret from it. As long as you keep your account secret safe, your funds are safe.

### What to do

1. **Ignore it.** Spam cannot be used against you directly, and replying only tells the sender you are reading it.
2. **Do not click the links.** A link in a memo leads somewhere the sender chose. It is not a safe place.
3. **Do not return the token "to be polite".** Sending it back costs you a network fee, and it flags you as an active account for more targeted spam. If you do choose to return it, understand that you are paying to send it.
4. **Do not pay anyone to "clean it up".** On-chain transactions cannot be deleted, by anyone.
5. **If you clicked something or sent funds**, follow the steps in [_I've been scammed_](ive-been-scammed.md)_._

### How did they get my address?

The XRP Ledger is a public blockchain, and every account address is public. Senders build lists of addresses to spray in bulk. You can end up on one of those lists if you:

* sent or received XRP through a crypto exchange
* opened a trust line to a token
* took part in an airdrop
* or simply activated an account

That is why people who have "done nothing" can still receive spam. A fresh account can be targeted within minutes of its first transaction.

There is currently no way to make an address unfindable, and no setting that stops incoming spam at the account level.

### A red flag worth knowing

On the XRP Ledger, anyone can send anyone a transaction, and every transaction is public and permanent. A single spam transaction is not, by itself, evidence of anything.

The red flag is the _follow-up_. If someone contacts you about a "refund," "recovery," or "help" after spam, and asks you to send XRP first or to share your account secret, it is a scam. Spam is often the first step in a longer sequence, and the reply is where the real attempt starts. Treat any such follow-up as a scam, and route it to [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support).

### How Xaman handles spam

Xaman looks for the patterns that mark a spam account. When it finds one, it suppresses the memo field and marks the transaction so you can see that it may be dangerous before you tap it. The transaction stays in your history, because it is public and permanent, but the misleading memo is hidden by default.

If you are unsure whether a transaction is spam or something more, send it to [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support) and we will take a look.

**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md) · [_Dust attacks_](dust-attacks.md)
