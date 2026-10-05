---
description: I received an escrow transaction
---

# Escrow Scams

### What is an escrow?

On the XRP Ledger, an escrow is a built-in mechanism that locks assets, either XRP or supported tokens, directly on the blockchain. These funds are securely locked and are only released to the recipient when predefined conditions are met, such as a specific date and time passing.

### What does an escrow scam look like?

A scammer sends you an unsolicited escrow that appears to hold a large amount of a token. They attach a memo with a link telling you to visit a website to "finalize" or "release" it. The escrow itself is not the attack. **The signature on the website is the attack.**

This escrow scam is a form of phishing that works in two distinct steps:

* The "lure" via memos: The XRP Ledger is public and permissionless, so anyone can initiate an escrow naming your account as the destination. Scammers send an unsolicited escrow appearing to hold a large amount of value, then attach custom text in the `Memo` field containing a phishing link. This link tells you to visit an external website to "verify," "claim," "finalize," or "release" the funds. The high token value is purely a lure.
* The true vector of attack: Simply receiving an unsolicited escrow on-chain does not grant a scammer access to your account or endanger your funds, the escrow object itself is not the attack. The actual attack occurs off-chain when you visit the scammer's website and sign a malicious transaction with your wallet (such as a `SetRegularKey` transaction, which hands signing control of your XRPL account over to the attacker).

### What the attacker is trying to do

The goal is to make a large, tempting balance appear in your account, and then get you to act on it. The token amount looks valuable, so you are more likely to want to claim it.

The token is almost always a fake look-alike, issued by an account you do not recognize. Some memos even claim it is XRP, but it is a fake token you have never heard of. You could not spend it, and you could not claim it on the ledger yourself.

A conditional escrow only releases once its condition is met, and the attacker is the one who set that condition. The token on the screen is worthless, so "releasing" it hands you nothing of value. The value was never there. The website is just the excuse to get your signature.

On that website, you are asked to connect your wallet and sign a transaction to "receive" the funds. **Do not sign it.** That transaction is not a harmless release. It is designed to take your real assets, or to give the attacker control of your account. You never actually receive the token amount you were shown.

### What it looks like

* An escrow from an address you have never dealt with.
* A large amount of a token with a familiar-sounding name, such as "USDT0" or "XRPL", sometimes claimed to be "XRP".
* A memo with a link, for example "Finalize Escrow at \[some-website]".
* Often repeated, or sent to many accounts at once.
* Sometimes from a _rotation_ of different sender addresses.
* The token issuer is an account you do not recognize.

### Is my account compromised?

No. An unsolicited escrow:

* does not spend your XRP
* does not cost you network fees
* does not change any settings on your account
* does not give the sender any access to your account
* does not add to your reserve or block your account, because the escrow object belongs to the sender, not to you.

The only thing it changes is your transaction history. The record of the transaction is public and permanent, and cannot be deleted.

### What to do

1. **Ignore it.** You do not need to take any action. The escrow cannot be used against you directly.
2. **Do not click the link in the memo.** It leads to a site the sender chose. It is not a safe place.
3. **Do not try to "finalize" or "release" the funds.** You never receive the token. The amount is only there to get you to act.
4. **Never sign a transaction you did not start yourself.** If a site asks you to connect your wallet and sign something to receive the funds, that signature is what steals your real assets. Do not sign it.
5. **Do not pay anyone to "clean it up" or "recover" it.** On-chain records cannot be deleted, by anyone.
6. **If you clicked a link or signed something**, follow the steps in [_I've been scammed_](ive-been-scammed.md)_._

### **Can you block these transactions?**

No. You cannot stop incoming escrows at the account level. The correct response is still to ignore the transaction and never sign what a link sends you to.

### What we are doing about scams

The XRP Ledger is a decentralized, public network. There are no "network police," no central authority that can reverse a transaction, block an address at the protocol level, or remove a scammer from the ledger. Every address is public, and anyone can send XRP, a token, an escrow, or an NFT to any other address. You are responsible for your own funds, and the strongest defence is recognizing a scam before you act on it.

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

The single best way to keep your assets safe in the future is[ **to contact us**](https://xumm.app/detect/xapp:xumm.support) if you are ever unsure about something. We live and breathe the XRP Ledger. We are constantly searching for new scams and are always here to help you verify whether an offer, airdrop, or transaction is safe before you "Slide to send."

It is very important that you **never sign a transaction you did not start yourself**. If something looks unexpected, contact [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support) before you act. We will check it for you.



**See also:** [_I've been scammed_](ive-been-scammed.md) · [_Spam on the XRP Ledger_](spam-on-the-xrp-ledger.md) · [_Dust attacks_](dust-attacks.md)

