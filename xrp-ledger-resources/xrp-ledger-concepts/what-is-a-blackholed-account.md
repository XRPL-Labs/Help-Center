---
description: What is a blackholed account?
---

# What is a blackholed account?

## What is a blackholed account?

A **blackholed account** is an XRP Ledger (XRPL) account that can never sign or authorize an outgoing transaction again. Its signing authority has been permanently and irreversibly removed from the ledger.

A blackholed account can still receive incoming XRP and issued tokens. It can never spend or send them. Any assets sent to a genuinely blackholed account are permanently unrecoverable.

Blackholing is an irreversible action performed by an account operator. Most standard accounts are never blackholed.

#### Why do people blackhole an account?

There are two primary reasons an account operator blackholes an address:

* **To prove a fixed token supply.** When a token issuer blackholes the issuing account, it proves to the community that no more of that token can ever be minted. It also locks the token settings forever. The issuer can no longer change transfer fees, set freeze flags, or alter rippling.
* **To permanently decommission an account.** Some accounts cannot be deleted using the standard `AccountDelete` transaction (for example, if they still have active trustlines or ledger dependencies). Blackholing ensures the account can never be used again. The account stays on the ledger and its reserves stay locked.

#### How do I check if an account is blackholed?

There is no single "blackhole" flag on the XRPL. An account is considered blackholed only when **all four** of the following conditions are met:

1. **The master key is disabled.** The `lsfDisableMaster` flag is enabled on the account. This removes the authority of the account secret (the master key).
2. **The regular key is set to a known blackhole address.** The account's `RegularKey` is set to one of two specific addresses derived from the numbers 0 and 1: `rrrrrrrrrrrrrrrrrrrrrhoLvTp` (ACCOUNT\_ZERO) or `rrrrrrrrrrrrrrrrrrrrBZbvji` (ACCOUNT\_ONE). A `RegularKey` set to any other address does not count. The ledger cannot verify who holds that other address's key.
3. **No signer list exists.** The account has no multi-signing list configured.
4. **No delegates exist.** The account has no delegate entries, so no other account can act on its behalf.

You can verify these conditions using a public XRPL block explorer (such as XRPLWin or XRP Scan) or directly via the XRPL API:

* `account_info` shows whether the master key is disabled and if a `RegularKey` is set.
* `account_objects` confirms that there is no `SignerList` object and no Delegate entries for the account.

**Why are blackhole addresses unspendable?** The blackhole addresses are generated directly from the numbers 0 and 1, not from a key pair. No one can produce a matching private key. So no valid signature can ever move funds out of these addresses.

**Note.** A blackholed account can still show recent transaction history. This occurs when other users trade the account's issued tokens, send funds to it, or interact with an Automated Market Maker (AMM) pool involving its assets. The blackholed account itself is not initiating or signing those transactions.

#### I sent funds to a blackholed account. What can I do?

If the destination address is truly blackholed, **the funds are permanently lost.**

No key can authorize a transaction to send them back:

* **The operator of the account cannot get the funds back either.** Once an account is blackholed, no one holds a working key for it. If you sent an issued token, the issuer cannot refund you. If you sent XRP, there is no issuer to contact. In either case, no one can authorize a transaction to move the funds out.
* **Validators and wallet providers cannot reverse it.** The XRP Ledger has no central administrator, and non-custodial wallets like Xaman do not control your funds or the ledger rules.
* **Beware of recovery scammers.** Anyone who claims they can "hack," "trace," or "reverse" funds from a blackholed account is a scammer. Recovery services targeting accidental transactions are fraudulent. See [I've been scammed](../../all-about-scams/ive-been-scammed.md).

_(**Important exception:** Check that the account is actually blackholed before you give up. If you sent funds to an active custodial exchange address and simply forgot to include a **Destination Tag**, the account is not blackholed. It belongs to the exchange. In that scenario, contact the exchange's customer support directly with your transaction hash to request a credit.)_

#### Things to keep in mind

* **Transactions are final.** Once a transaction is validated by the consensus mechanism, it cannot be edited, paused, or canceled.
* **Double-check destinations.** Always verify destination addresses and tags before signing, especially when sending to an exchange or requesting a credit with a destination tag.
* **Xaman cannot reverse a transaction.** Xaman cannot reverse, freeze or undo a transaction. See [Can Xaman reverse, freeze or undo a transaction?](../../all-about-scams/can-xumm-reverse-freeze-or-undo-a-transaction.md).
