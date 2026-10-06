---
description: I received a suspicious NFT offer
---

# NFT Scams

**If someone is offering to sell you an NFT — or says an "offer" is waiting on your account — read this before you sign anything.**

### The short version

An NFT Offer (technically called an _NFTokenOffer_) on the XRP Ledger is a native, on-chain mechanism used to buy or sell a Non-Fungible Token (NFT). It is part of the XRP Ledger itself, not a feature of any one app or marketplace. On the XRP Ledger, an NFT trade is a two-step contract: one account **creates an offer**, another account **accepts it**. The moment it is accepted, the swap happens in a single atomic step — the NFT goes one way, the XRP goes the other. **There is no undo.**

A common scam works like this: an offer for an NFT that sounds valuable simply **appears in your app**. No one contacted you. You "accept the offer." What you actually signed was a **buy offer** for a token the scammer minted moments earlier, worth zero. Your XRP is gone within seconds.

### How the scam works

The steps below were verified on-chain from a real case:

1. **The scammer mints a fake NFT.** Creating an NFT costs a fraction of a cent. The scammer gives it a plausible name — for example "Ripple Credit Certificate" or "Earning XRPL Key" — and points the image at a free image host. The NFT has no value.
2. **The offer appears in your app.** No one messages you. When you open Xaman, the offer is simply there — an NFT being sold to you at a price. No contact, no prior relationship, no context. That is the point: it just shows up, and it looks legitimate.
3. **You sign what looks like accepting an offer.** The screen may say "selling for _x_ XRP" or similar — that wording describes the _seller's_ side of the trade. What you actually signed is a **buy offer**: "I will pay _x_ XRP for this NFT."
4. **The scammer accepts.** Seconds later on the ledger. Your XRP moves to the scammer, the worthless NFT moves to you. Final.

**Note:** While most NFT scams involve XRP, an NFT offer can be made with **any** issued token on the XRP Ledger.

### Signs of a fake offer

* The offer just appeared in your app — no one contacted you about it, and you do not recognize the NFT.
* The name sounds official, but the issuer is an unknown account — or the NFT was minted minutes ago.
* The price sounds too good to be true, or "too valuable to miss."
* There is pressure to act right now.
* The image is hosted on a free image site (postimg.cc, imgur, and similar).
* The app's wording is ambiguous. **Before you sign, check the direction: is your XRP going out, or coming in?**

### Protecting yourself

* **Do not accept NFT offers that appear out of nowhere.** If an offer for a token you do not recognize shows up in your app, the answer is no — no matter how legitimate the token appears.
* **Check the direction before you sign.** Every signature in Xaman shows you what you are signing. If XRP is leaving your account, you are buying — and you should be certain you want to buy.
* **Check the NFT's history.** When was it minted, and by whom? A token minted ten minutes ago by an account with no history is worthless.
* **Turn off "Allow Incoming NFT Offers" in Xaman.** Be clear about what it does: it blocks offers _targeting your account_ (offers that can only be accepted by you). It does **not** stop you from signing a buy offer — that choice is always yours, which is why the first three points matter most.
* **Contact us!** If you are ever unsure, contact us via the [**Xaman Support xApp**](https://xaman.app/detect/xapp:xumm.support-md) before you act. We can verify whether an offer is legitimate before you sign anything.

### How to block incoming NFT offers

This stops other accounts from creating new NFT offers to your account.

1. Launch the Account Settings xApp: https://xaman.app/detect/xapp:xrplwin.settings
2. Tap **Allow Incoming NFT Offers**
3. Turn the **Allow** toggle off
4. Tap **Save**
5. Sign the transaction

### After a scam: expect follow-up activity

After a scam, your account is often targeted again. You may see two kinds of follow-up:

* **A "recovery" or "refund" contact.** Someone reaches out — often posing as support or a "crypto recovery" service — offering to get your funds back for a fee or by asking you for your account secret. This is a second scam. Xaman never asks for your account secret, and no one can reverse a completed transaction.
* **Tiny payments from unknown addresses.** These are usually 1 drop of XRP, but they can also be a single unit of a token, for example 1 of a token you already hold. These payments are worthless. They may be **address poisoning**: the sender's address is put into your history so that later, when you make an outgoing payment, you might copy that look-alike address instead of the real one. The fix is simple: **never copy an address from your transaction history or autocomplete.** Always take it from the verified, known-good source and check it character by character.

### What to do if you already accepted

1. **The XRP cannot be recovered.** Anyone who promises to recover it for a fee is running a second scam. Xaman will never ask for your account secret, and no one can reverse an accepted NFT offer.
2. **File a police report**. Include:&#x20;

* Amount lost:
* Transaction hash / ID:
* The scammer's address (r-address):
* Your XRP Ledger address (r-address):
* Date/time of incident:

If you are not sure where to find all of this information, contact us via the [**Xaman Support xApp**](https://xaman.app/detect/xapp:xumm.support-md) and we will help you pull it from the ledger.

3. **Turn off "Allow Incoming NFT Offers"** in your settings (as described above).
4. **Watch for the 1-drop follow-up activity** described earlier, and do not act on any "recovery" contact.

### What we are doing about scams

The XRP Ledger is a decentralized, public network. There are no "network police," no central authority that can reverse a transaction, block an address at the protocol level, or remove a scammer from the ledger. Every address is public, and anyone can send XRP, a token, an escrow, or an NFT to any other address. You are responsible for your own funds, and the strongest defense is recognizing a scam before you act on it.

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

The single best way to keep your assets safe in the future is[ **to contact us**](https://xaman.app/detect/xapp:xumm.support-md) if you are ever unsure about something. We live and breathe the XRP Ledger. We are constantly searching for new scams and are always here to help you verify whether an offer, airdrop, or transaction is safe before you "Slide to send."

It is very important that you **never sign a transaction you did not start yourself**. If something looks unexpected, contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md) before you act. We will check it for you.

### Summary

* Unsolicited NFT offers from strangers are always scams — do not accept them.
* Turn off **Allow Incoming NFT Offers** in the [**Account Settings xApp**](https://xaman.app/detect/xapp:xrplwin.settings) if you don't use NFTs.
* If you already accepted one, the transaction is final — report it to the police.
