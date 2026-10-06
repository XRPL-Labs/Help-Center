---
description: Understanding spam
---

# Spam on the XRP Ledger

#### What is spam?

Spam on the XRP Ledger is an unsolicited transaction from an account you have not dealt with, sent by someone you do not know. The sender is almost always trying to get you to buy a token, join an airdrop, or visit a project.

Most spam falls into a few categories:

* a marketing push to get you to join a project or airdrop
* a scam that wants you to visit a website
* a scam that wants you to buy an NFT
* a scam that wants you to contact the sender
* a dust payment, sent only to 'dust' your account (see: [Dust attacks](dust-attacks.md))
* an unexpected token or XRP received containing a memo asking you to "claim" or "verify"

The spam transaction itself is not the danger. **The real danger is the bait behind it.**

#### Is my account compromised?

No. A spam transaction:

* does not spend your XRP
* does not cost you network fees
* does not change any settings on your account
* does not give the sender any access to your account

The only thing spam changes is your transaction history. Nobody can read your account secret from it. As long as you keep your account secret safe, your funds are safe.

#### What it looks like

Spam on the XRP Ledger typically appears as one of the following in your account log:

* **XRP dust.** A payment of 1 drop (0.000001 XRP) from an address you do not recognise. The XRP amount is negligible; the goal is the memo or the address itself.
* **XRP with a memo.** A small XRP payment carrying a text memo that contains a URL, a token name, or a "claim your airdrop" message. The XRP is just the delivery mechanism.
* **NFT spam.** An unsolicited `NFTokenOffer` of a low-value or worthless NFT. NFTs do not require a trust line, so anyone can push one to any account.
* **Pre-trusted token drop.** A single unit of a token from an issuer you already have a trust line to. The token amount is negligible; the goal is the memo or the address itself.

In all cases, the transaction has no value to you. Do not interact with it and do not visit any URL in the memo.

#### How did they get my address?

The XRP Ledger is a public blockchain, and every account address is public. A scammer can get your address if you:

* sent or received XRP through a crypto exchange
* opened a trust line to a token
* took part in an airdrop
* or simply activated an account

That is why people who have "done nothing" can still receive spam. A fresh account can be targeted within minutes of its first transaction.

There is currently no way to make an address unfindable, and no setting that stops incoming spam at the account level.

#### How Xaman handles spam

Xaman checks every incoming transaction against its blacklist of thousands of known scam and spam accounts. When a match is found:

* The memo field is **suppressed by default**, so a phishing link does not sit in your transaction history looking like a legitimate message.
* The transaction is **flagged** so you can see that it may be dangerous before you tap it.
* If you try to **send to** a blacklisted address, the app shows a **warning before you sign**.

The transaction itself stays in your history, because it is public and permanent. What changes is how it is displayed.

If you are unsure whether a transaction is spam or something more, contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md) and we will take a look.

#### What to do about spam transactions

1. **Ignore it.** Spam cannot be used against you directly, and replying only tells the sender you are reading it.
2. **Do not click the links.** A link in a memo leads somewhere the sender chose. It is not a safe place.
3. **Do not return the token "to be polite".** Sending it back costs you a network fee, and it flags you as an active account for more targeted spam. If you do choose to return it, understand that you are paying to send it and will most likely be targeted for further scams.
4. **Do not pay anyone to "clean it up".** On-chain transactions cannot be deleted, by anyone.
5. **Treat any follow-up contact as a scam.** If someone contacts you after the spam about a "refund," "recovery," or "help," and asks you to send XRP first or to share your account secret, it is a scam. Spam is often the first step in a longer sequence, and the reply is where the real attempt starts.
6. **If the spam is persistent or you are unsure**, contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md). We can check the pattern, flag the accounts, and let you know if there is anything you should do.
7. **If you clicked something or sent funds**, follow the steps in [_I've been scammed_](ive-been-scammed.md).

#### What we are doing about scams

The XRP Ledger is a decentralised, public network. There are no "network police," no central authority that can reverse a transaction, block an address at the protocol level, or remove a scammer from the ledger. Every address is public, and anyone can send XRP, a token, an escrow, or an NFT to any other address. You are responsible for your own funds, and the strongest defence is recognizing a scam before you act on it.

What we do, every day:

* **Blacklist.** Xaman maintains a blacklist of thousands of known scam and spam accounts, updated daily from multiple sources: Ripple's own flags, the xrpl.to scam database, OFAC sanctions, and our internal monitoring. When you try to send to a blacklisted address, the app shows a warning before you sign.
* **Pre-sign warnings.** Before you confirm any transaction, Xaman checks the destination against the blacklist and other threat feeds. Known-bad addresses are flagged so you see the warning before you tap sign.
* **Memo suppression.** Memos from blacklisted or known-spam accounts are hidden by default, so a phishing link does not sit in your transaction history looking like a legitimate message.
* **Scam website takedowns.** We actively report and pursue takedown of websites that impersonate Xaman or the XRP Ledger.
* **Social media enforcement.** We report scam accounts on X and other platforms for removal.
* **Support-led forensics.** When you report a suspicious transaction, our team pulls the full ledger history, checks every involved address against the blacklist, and identifies the attack pattern. This is how new scam accounts get flagged and added.
* **NFT offer blocking.** You can turn off incoming NFT offers in your account settings so unsolicited buy offers stop appearing in your app.

What we cannot do:

* Reverse or delete a completed transaction.
* Stop an unsolicited incoming payment, escrow, or NFT at the protocol level.
* Control what a third-party website asks you to sign.
* Guarantee that a brand-new scam account has already been flagged.

The single best way to keep your assets safe in the future is [**to contact us**](https://xaman.app/detect/xapp:xumm.support-md) if you are ever unsure about something. We live and breathe the XRP Ledger. We are constantly searching for new scams and are always here to help you verify whether an offer, airdrop, or transaction is safe before you "Slide to send."

It is very important that you **never sign a transaction you did not start yourself**. If something looks unexpected, contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md) before you act. We will check it for you.

**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md) · [_Dust attacks_](dust-attacks.md)

