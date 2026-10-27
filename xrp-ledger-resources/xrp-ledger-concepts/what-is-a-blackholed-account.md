# What is a blackholed account?

## What is a blackholed account?

A **blackholed account** is an XRP Ledger (XRPL) account that can never sign or authorize an outgoing transaction again. Its signing authority has been permanently and irreversibly removed from the ledger.

While a blackholed account can still receive incoming XRP and issued tokens, it can never spend, transfer, or move them. Any assets sent to a genuinely blackholed account are permanently unrecoverable.

Blackholing is a deliberate, irreversible action performed by an account operator. Most standard accounts are never blackholed.

#### Why do people blackhole an account?

There are two primary reasons an account operator blackholes an address:

* **To prove a fixed token supply.** When a token issuer blackholes the issuing account, it mathematically proves to the community that no more of that token can ever be minted. It also locks the token settings forever, meaning the issuer can no longer change transfer fees, set freeze flags, or alter trustline configurations.
* **To permanently decommission an account.** Some accounts cannot be deleted using the standard `AccountDelete` transaction (for example, if they still have active trustlines or ledger dependencies). Blackholing ensures the account can never be used again, effectively neutralizing it while leaving its base reserve locked.

#### How do I check if an account is blackholed?

There is no single "blackhole" flag on the XRPL. Instead, an account is considered blackholed only when **all three** of the following conditions are met:

1. **The Master Key is disabled.** The `lsfDisableMaster` flag is enabled on the account, revoking the authority of the original secret key/passphrase.
2. **The Regular Key is set to a verifiable blackhole address.** The account’s `RegularKey` is set to an address with no known private key, most commonly `rrrrrrrrrrrrrrrrrrrrrhoLvTp` (`ACCOUNT_ZERO`) or `rrrrrrrrrrrrrrrrrrrrBZbvji` (`ACCOUNT_ONE`).
3. **No Signer List exists.** The account has no multi-signing list configured, meaning no group of secondary keys can authorize transactions on its behalf.

You can verify these conditions using a public XRPL block explorer (such as XRP Scan or Bithomp) or directly via the XRPL API:

* `account_info` shows whether the master key is disabled and if a `RegularKey` is set.
* `account_objects` confirms that there is no `SignerList` object tied to the account.

**Why are blackhole addresses unspendable?**\
Addresses like `ACCOUNT_ZERO` and `ACCOUNT_ONE` are generated directly from simple numbers (0 and 1) rather than a private key. Because no private key exists for them, no valid cryptographic signature can ever be produced to move funds out of them.

**Note.** A blackholed account can still show recent transaction history. This occurs when other users trade the account's issued tokens, send funds to it, or interact with an Automated Market Maker (AMM) pool involving its assets. The blackholed account itself is not initiating or signing those transactions.

#### I sent funds to a blackholed account. What can I do?

If the destination address is truly blackholed, **the funds are permanently lost.**

Since the private keys do not exist, no one on Earth can authorize a transaction to send them back:

* **Token issuers cannot refund you.** Even if you contact the project or developer who originally operated the account, they no longer hold any keys or permissions to access it.
* **Validators and wallet providers cannot reverse it.** The XRP Ledger has no central administrator, and non-custodial wallets like Xaman do not control your funds or the ledger rules.
* **Beware of recovery scammers.** Anyone who claims they can "hack," "trace," or "reverse" funds from a blackholed account is a scammer. Recovery services targeting accidental transactions are fraudulent. See I've been scammed.

_(**Important Exception:** Make sure the account is actually blackholed before giving up. If you sent funds to an active custodial exchange address and simply forgot to include a **Destination Tag**, the account is not blackholed—it belongs to the exchange. In that scenario, contact the exchange's customer support directly with your transaction hash to request a credit.)_

#### Things to keep in mind

* **Transactions are final.** Once a transaction is validated by the consensus mechanism, it cannot be edited, paused, or canceled.
* **Double-check destinations.** Always verify destination addresses and tags before signing, especially when
