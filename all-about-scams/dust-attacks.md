---
description: I received a dust transaction
---

# Dust attacks

### What is a dusting attack?

A dusting attack is when unknown accounts send you extremely small payments — as little as 1 drop (0.000001 XRP), or a single unit of a token. The payments are called **dust** because they are basically worthless: no one can meaningfully spend them, and they leave your balance effectively unchanged.

A token can only be sent to an account that already has a trust line to that token's issuer. So if the dust is a token, the sender already knew you could receive it.

The dust itself is not the attack. **The dust is the setup.**

### What the attacker is trying to do

The goal is usually **address poisoning**: getting the attacker's address into your transaction history, your wallet's address book, or your app's autocomplete — places you naturally look when you send XRP. That address looks familiar — it is in your own history — so you are more likely to copy it without checking.&#x20;

The dust is the setup, not the theft. The only real risk is a future mistake: copying the wrong, familiar-looking address from your own history instead of the verified one.

### What it looks like

* Payments of 1 drop (0.000001 XRP) from addresses you have never dealt with.
* Sometimes they arrive on a schedule — for example, every few days.
* Sometimes from a _rotation_ of several different addresses, not just one.
* Sometimes the addresses look similar to exchanges or services you actually use, to feel familiar.
* Your balance barely moves. That is deliberate — it should not catch your eye.

### Is my account compromised?

No. A dust payment:

* does not spend your XRP,
* does not cost you network fees
* does not change any settings on your account,
* does not give the sender any access to your account,
* cannot be reversed, deleted, or "removed" by you or by anyone else — it is a completed, public transaction.

The only thing a dust payment changes is your transaction history. That is exactly the point.

### What to do

1. **Ignore the payments.** They are worthless and cannot be used against you directly.
2. **Never copy an address from your own transaction history.** When you send XRP or a token, take the destination address from the known-good source, such as a verified contact in your Address Book. Always check the r-address character by character.
3. **Treat any follow-up contact as a scam.** If someone contacts you about a "refund," "recovery of your funds," or "cleaning up" your account, especially if they ask you to send XRP first or to share your account secret, it is a scam. Xaman will never ask for your account secret.
4. **Do not pay anyone to "remove" the payments.** On-chain transactions cannot be deleted, by anyone.
5. **If you have already sent funds to an unfamiliar address**, follow the steps in [_I've been scammed_](ive-been-scammed.md): file a police report, contact Xaman support via the [Xaman Support xApp](https://xumm.app/detect/xapp:xumm.support), and be alert for second-stage "recovery" scams.

#### Advanced option: stop the payments at your account

The dust is not harmful on its own, and most people do not need to act. If you still want the payments to stop landing, the XRP Ledger has an account setting called **Deposit Authorization (DepositAuth)**.

**What it does**

When you turn it on, your account blocks incoming payments from any account you have not preauthorized. It blocks XRP and tokens. Only two things can still reach your account:

* An account you have preauthorized.
* A transaction you start yourself to receive funds, such as finishing an escrow.

**What to know before you turn it on**

* It blocks **every payment** from a sender you have not preauthorized, not just dust. There is no way to block only small payments.
* If you normally receive payments from an exchange or a service, you must preauthorize it first. If you do not, you will not receive from it.
* Each account you preauthorize adds to your account's owner reserve, so your account must hold more XRP.
* This feature was built for regulated businesses that must know the sender of every payment. It is not a simple anti-spam switch.
* A balance at or below the minimum account reserve can still receive a small amount of XRP, so a nearly empty account is not fully protected.

**How to turn it on**

It is set with a ledger transaction (`AccountSet` with the `asfDepositAuth` flag). If you want to use it, contact us via the [Xaman Support xApp](https://xumm.app/detect/xapp:xumm.support) and we will help you set it up.

**Our advice**

For most people, the best response to dust is to ignore it, and never copy an address from your own transaction history. Deposit Authorization is a strong tool, but it is broad and easy to set up wrong. Use it only if you want a hard block and are willing to manage the preauthorization list.

### A red flag worth knowing

On the XRP Ledger, anyone can send anyone a payment as small as 1 drop, and every payment is public and permanent. (A single unit of a token works the same way, but a token can only be sent to an account that already trusts that token's issuer.) A single tiny payment is not, by itself, evidence of anything.

The red flag is a _series_ of tiny payments from a _rotating_ set of addresses, especially right after a scam. That pattern is consistent with someone setting up an address-poisoning attack against your account. If you see it, do not copy any address from your own transaction history, and treat any follow-up contact with extra caution. If you have already lost funds, remember that "recovery" scams are a common follow-up after a loss, and route anything you are unsure about to [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support).

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

**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md)

