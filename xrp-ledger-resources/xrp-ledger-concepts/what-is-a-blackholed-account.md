---
description: An XRP Ledger account that no one can ever send from again
---

# What is a blackholed account?

### Background

A blackholed account is an XRP Ledger (XRPL) account that has given up every way of signing transactions, on purpose and for good. It can still receive XRP and tokens, but nothing can ever leave it again. Its owner cannot send from it, and neither can anyone else.

Most people never need to think about blackholed accounts. You might come across one in two situations: when you check a token, since many token issuers blackhole their accounts, or when you have sent funds somewhere by mistake. This article explains what blackholing means in both cases, how to check whether an account is blackholed, and what to do if you sent funds to one.

### What makes an account blackholed

Every XRP Ledger account needs a key to sign transactions. Most accounts have one, the account secret, and some add a second key or a multi-signing list. Blackholing removes every one of them, so the account can never sign anything again.

An account counts as blackholed only when all of these are true:

* **Its master key is disabled.** The original account secret no longer works.
* **Its regular key is set to a known blackhole address.** These are special addresses that no one has a key for: `rrrrrrrrrrrrrrrrrrrrrhoLvTp` and `rrrrrrrrrrrrrrrrrrrrBZbvji`.
* **It has no multi-signing list.** No group of other accounts can sign for it.
* **It has no delegates.** No other account has permission to act on its behalf.

The two blackhole addresses are made from the numbers 0 and 1, not from a key pair. That means no account secret exists for them, so no one can ever sign for them. If an account's regular key is set to any other address, it does not count as blackholed, since there is no way to prove that no one holds that key.

There is no single "blackholed" label on the XRP Ledger. An account either meets all four conditions or it does not.

### Why accounts are blackholed

The most common reason is trust in a token. When a token issuer blackholes its account, it can never issue more of that token, so the supply is fixed for good. Its settings are locked too: it can never change the token's transfer fee, freeze the token, or claw it back. For holders, that removes the issuer's powers described in [Token freezes and clawback](../../learning-more-about-xaman/token-freezes-and-clawback.md).

The other reason is retiring an account that cannot be deleted. Some accounts have things attached to them that block deletion. Blackholing stops the account from ever being used again, though it stays on the XRP Ledger and its reserve stays locked.

### How to check whether an account is blackholed

Account settings on the XRP Ledger are public, so you can check any account yourself. Look up its r-address in any XRP Ledger explorer, and check the four conditions above. Explorers usually show whether the master key is disabled, which regular key is set, and whether a multi-signing list exists.

A blackholed account can still show new transactions in its history. This happens when other people trade its tokens, send it funds, or use an AMM pool that holds its tokens. The blackholed account itself is not signing any of them.

A blackholed issuer is a good sign for a token's supply and settings, but it says nothing about whether the token is valuable or genuine. Any issuer can blackhole its account. See [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning) for what else to check.

### If you sent funds to a blackholed account

First, make sure the account really is blackholed, using the four conditions above. Many accounts that seem unreachable are not blackholed at all. The most common case is an exchange deposit without a destination tag, which the exchange can usually fix. See the first question in the FAQ below.

If the account is truly blackholed, XRP sent to it is permanently lost. No one holds a key that can move it, including the account's original owner. Validators and wallets cannot reverse it either. Xaman is a self-custody wallet, so we cannot reverse, freeze, or undo a transaction.

Tokens can be different. If the token's issuer turned on clawback, the issuer can take tokens back from any account, including a blackholed one, since the issuer signs the clawback, not the account holding the tokens. Contact the token's issuer through its official website and ask whether it can help. Whether it does is entirely up to the issuer.

{% hint style="warning" %}
Anyone who offers to "hack", "trace", or "reverse" funds from a blackholed account is a scammer. Paying them loses more money, since no one can move funds from a blackholed account. Do not reply, and do not pay any fee.
{% endhint %}

See [Recovery scams](../../scams-and-staying-safe/recovery-scams.md) for how these scammers work.

### Frequently asked questions

**I sent XRP to an exchange and forgot the destination tag. Is the account blackholed?**

Almost certainly not. Exchanges use shared accounts, and the destination tag tells them which customer a deposit belongs to. Your XRP has arrived at the exchange's account, which the exchange fully controls. Contact the exchange's support team with the transaction hash, and ask them to credit it to your account. See [Deposit to exchange did not arrive](https://help.xaman.app/app/learning-more-about-xaman/deposit-to-exchange-did-not-arrive).

**Can a blackholed account still receive funds?**

Yes. Anyone can still send XRP or tokens to a blackholed account. Nothing can ever leave it, so anything sent there stays there permanently.

**Can a blackholed account be restored?**

No. Blackholing cannot be undone. Restoring an account needs a working key, and a blackholed account has none.

**Can I blackhole my own account?**

You could, but there is almost never a reason to, and it would lock away your XRP reserve and anything left in the account. If you want to stop using an account, deleting it gets back most of the reserve. See [How to delete an XRPL account](https://help.xaman.app/app/learning-more-about-xaman/how-to-delete-an-xrpl-account).

**Why does a blackholed account still show recent activity?**

Other people can still trade its tokens, send it funds, or use an AMM pool that holds its tokens. Those transactions show up in its history, but the blackholed account is not signing any of them.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Token freezes and clawback](../../learning-more-about-xaman/token-freezes-and-clawback.md)
* [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning)
* [How issued tokens work on the XRP Ledger](https://help.xaman.app/app/learning-more-about-xaman/how-issued-tokens-work-on-the-xrp-ledger)
* [Can Xaman reverse, freeze or undo a transaction?](https://help.xaman.app/app/all-about-scams/can-xaman-reverse-freeze-or-undo-a-transaction)
* [I've been scammed!](https://help.xaman.app/app/all-about-scams/ive-been-scammed)
