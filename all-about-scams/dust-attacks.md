---
description: Dust attacks
---

# Dust attacks

### What is a dusting attack?

A dusting attack is when unknown accounts send you extremely small payments — as little as 1 drop (0.000001 XRP). The payments are called **dust** because they are basically worthless: no one can meaningfully spend 1 drop, and they leave your balance effectively unchanged.

The dust itself is not the attack. **The dust is the setup.**

### What the attacker is trying to do

The goal is usually **address poisoning**: getting the attacker's addresses into your transaction history, your wallet's address book, or your app's autocomplete — places you naturally look when you send XRP.

Later, a fake "refund," "recovery," or "support" message will ask you to send real funds to an address. That address looks familiar — it is in your own history — so you are more likely to copy it without checking. By then, the dust has done its job.

In short: **the theft is a different transaction, weeks later. The dust just prepares the ground.**

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
2. **Never copy an address from your own transaction history.** When you send XRP, take the destination address from the known-good source like a verifed contact in your Address Book. Always check the r-address character by character.
3. **Treat any follow-up contact as a scam.** If someone contacts you about a "refund," "recovery of your funds," or "cleaning up" your account — especially if they ask you to send XRP first or to share your account secret — it is a scam. Xaman will never ask for your account secret.
4. **Do not pay anyone to "remove" the payments.** On-chain transactions cannot be deleted, by anyone.
5. **If you have already sent funds to an unfamiliar address**, follow the steps in _I've been scammed_: file a police report, contact Xaman support, and be alert for second-stage "recovery" scams.

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

On the XRP Ledger, anyone can send anyone 1 drop, and every payment is public and permanent. A single 1-drop payment is not, by itself, evidence of anything. But a _series_ of 1-drop payments from a rotating set of addresses — especially right after a scam — means someone is actively preparing a follow-up attack against you. If you see that pattern after losing funds, assume the next message that arrives will try to take more, and route it straight to Xaman support.

**See also:** [_I've been scammed_](ive-been-scammed.md) · [_NFT scams_](nft-scams.md)

