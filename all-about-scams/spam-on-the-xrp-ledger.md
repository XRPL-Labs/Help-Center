---
description: Understanding SPAM
---

# Spam on the XRP Ledger

### **What is spam?**

Spam on the XRP Ledger is an unsolicited transaction from an account you have not dealt with. It is a transaction you did not ask for, sent by someone you do not know. The sender is almost always trying to get you to buy a token, join an airdrop, or visit a project.

Most spam falls into a few categories:

* a marketing push to get you to join a project or airdrop
* a scam that wants you to visit a website
* a scam that wants you to buy an NFT
* a scam that wants you to contact the sender
* a dust payment, sent only to 'dust' your account. (See: [Dust attacks](dust-attacks.md))

The spam transaction itself is not the danger. **The real danger is the bait behind it.**

### Is my account compromised?

No. A spam transaction:

* does not spend your XRP
* does not cost you network fees
* does not change any settings on your account
* does not give the sender any access to your account

The only thing spam changes is your transaction history. Nobody can read your account secret from it. As long as you keep your account secret safe, your funds are safe.

### How did they get my address?

The XRP Ledger is a public blockchain, and every account address is public. A scammer can get your address if you:

* sent or received XRP through a crypto exchange
* opened a trust line to a token
* took part in an airdrop
* or simply activated an account

That is why people who have "done nothing" can still receive spam. A fresh account can be targeted within minutes of its first transaction.

There is currently no way to make an address unfindable, and no setting that stops incoming spam at the account level.

### How Xaman handles spam

Xaman looks for the patterns that mark a spam account. When it finds one, it suppresses the memo field and marks the transaction so you can see that it may be dangerous before you tap it. The transaction stays in your history, because it is public and permanent, but the misleading memo is hidden by default.

If you are unsure whether a transaction is spam or something more, send it to [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support) and we will take a look.

### What to do about spam transactions

1. **Ignore it.** Spam cannot be used against you directly, and replying only tells the sender you are reading it.
2. **Do not click the links.** A link in a memo leads somewhere the sender chose. It is not a safe place.
3. **Do not return the token "to be polite".** Sending it back costs you a network fee, and it flags you as an active account for more targeted spam. If you do choose to return it, understand that you are paying to send it.
4. **Do not pay anyone to "clean it up".** On-chain transactions cannot be deleted, by anyone.
5. **If you clicked something or sent funds**, follow the steps in [_I've been scammed_](ive-been-scammed.md)



**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md) · [_Dust attacks_](dust-attacks.md)
