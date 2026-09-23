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

The dust itself never costs you anything. The only real risk is a future mistake: copying the wrong, familiar-looking address from your own history instead of the verified one.

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

**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md)

