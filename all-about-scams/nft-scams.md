---
description: I received a suspicious NFT offerNFT Scams
---

# NFT Scams

**If someone is offering to sell you an NFT — or says an "offer" is waiting on your account — read this before you sign anything.**

### The short version

An NFT Offer (technically called an _NFTokenOffer_) on the XRP Ledger is a native, on-chain mechanism used to buy or sell a Non-Fungible Token (NFT). It is part of the XRP Ledger itself, not a feature of any one app or marketplace. On the XRP Ledger, an NFT trade is a two-step contract: one account **creates an offer**, another account **accepts it**. The moment it is accepted, the swap happens in a single atomic step — the NFT goes one way, the XRP goes the other. **There is no undo.**

A common scam works like this: an offer for an NFT that sounds valuable simply **appears in your app**. No one contacted you. You "accept the offer." What you actually signed was a **buy offer** for a token the scammer minted moments earlier, worth zero. Your XRP is gone within seconds.

### How the scam works

The steps below were verified on-chain from a real case:

1. **The scammer mints a fake NFT.** Creating an NFT costs a fraction of a cent. The scammer gives it a plausible name — for example "Ripple Credit Certificate" or "Earning XRPL Key" — and points the image at a free image host. The NFT has no value.
2. **The offer appears in your app.** No one messages you. When you open Xaman, the offer is simply there — a NFT being sold to you at a price. No contact, no prior relationship, no context. That is the point: it just shows up, and it looks legitimate.
3. **You sign what looks like accepting an offer.** The screen may say "selling for _x_ XRP" or similar — that wording describes the _seller's_ side of the trade. What you actually signed is a **buy offer**: "I will pay _x_ XRP for this NFT."
4. **The scammer accepts.** Seconds later on the ledger. Your XRP moves to the scammer, the worthless NFT moves to you. Final.

**Note:** While most NFT scams involve XRP, a NFT offer can be made with **any** issued token on the XRP Ledger.

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
* **Contact us!** If you are ever unsure, contact us via the [Xaman Support xApp](https://xumm.app/detect/xapp:xumm.support) before you act. We can verify whether an offer is legitimate before you sign anything.

### How to block incoming NFT offers

This stops other accounts from creating new NFT offers to your account.

1. Launch the Account Settings xApp: https://xaman.app/detect/xapp:xrplwin.settings
2. Tap **Allow Incoming NFT Offers**
3. Turn the **Allow** toggle off
4. Tap **Save**
5. Sign the transaction

### After a scam: expect follow-up activity

After a scam, your account is often targeted again. You may see two kinds of follow-up:

* **A "recovery" or "refund" contact.** Someone reaches out — often posing as support or a "crypto recovery" service  — offering to get your funds back for a fee or by asking you for your account secret. This is a second scam. Xaman never asks for your account secret, and no one can reverse a completed transaction.
* **Tiny payments from unknown addresses.** These are usually 1 drop of XRP, but they can also be a single unit of a token, for example 1 of a token you already hold. These payments are worthless. They may be **address poisoning**: the sender's address is put into your history so that later, when you make an outgoing payment, you might copy that look-alike address instead of the real one. The fix is simple: **never copy an address from your transaction history or autocomplete.** Always take it from the verified, known-good source and check it character by character.

### What to do if you already accepted

1. **The XRP cannot be recovered.** Anyone who promises to recover it for a fee is running a second scam. Xaman will never ask for your account secret, and no one can reverse an accepted NFT offer.
2. **File a police report.** Include:&#x20;

* Amount lost:
* Transaction hash / ID:
* The scammer's address (r-address):
* Your XRP Ledger address (r-address):
* Date/time of incident:

If you are not sure where to find all of this information, contact us via the [**Xaman Support xApp**](https://xumm.app/detect/xapp:xumm.support) and we will help you pull it from the ledger.

3. **Turn off "Allow Incoming NFT Offers"** in your settings (as described above).
4. **Watch for the 1-drop follow-up activity** described earlier, and do not act on any "recovery" contact.

### Summary

* Unsolicited NFT offers from strangers are always scams — do not accept them.
* Turn off **Allow Incoming NFT Offers** in the [**Account Settings xApp**](https://xaman.app/detect/xapp:xrplwin.settings) if you don't use NFTs.
* If you already accepted one, the transaction is final — report it to the police.
