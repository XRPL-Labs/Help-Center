---
description: What is a MPT on the XRP Ledger?
---

# How Multi-Purpose Tokens (MPTs) work on the XRP Ledger

Multi-Purpose Tokens (MPTs) are the XRP Ledger's second-generation fungible token standard. While XRP is the ledger's single native asset, every other asset on the network is an issued token. These issued tokens fall into three standards: trust line tokens (version 1), MPTs (version 2), and NFTs.

This article covers how MPTs work in your wallet and how they differ from traditional issued tokens. (For version 1 tokens, see _How issued tokens work on the XRP Ledger_. For unique collectibles, see _NFTs_.)

## How MPTs are identified

Instead of using a three-character currency code and a bilateral trust line, every MPT issuance is identified by an MPT issuance ID, which is a 48-character hexadecimal string encoding both the issuer's address and a unique sequence number. When expressing a balance or payment, an amount is included alongside that ID (for example, `100 TBILL` tied to a specific issuance ID).

## What makes MPTs different from trust line tokens

For wallet users, MPTs streamline several behaviors that required workarounds under the older trust line standard:

* Simple opt-in instead of trust lines: Rather than setting a trust limit, you simply opt in to hold an MPT. Depending on the token's configuration, the issuer may also need to authorize your account before you can receive it.
* Rich on-ledger metadata: Trust line tokens only store a currency code on the ledger, leaving wallets to pull names and logos from external directories. MPTs can store their ticker, full name, description, and icon directly on the ledger.
* Built-in token rules: Issuers can enforce native rules when creating an MPT, such as a fixed maximum supply, built-in transfer fees, clawback controls, or non-transferability (useful for event tickets, credentials, or loyalty points).

## Why the issuance ID and issuer matter

The ticker, name, and icon stored in an MPT's metadata are just labels, and they are not unique. Multiple accounts can create MPTs using the same familiar ticker (such as `USD`, `TBILL`, or `GOLD`), and a single issuer can even launch multiple separate issuances with the same ticker. Even if two MPTs display identical names and icons in your wallet, the ledger treats them as completely separate assets. The MPT issuance ID is what tells them apart.

## What gives an MPT value

Metadata labels carry no intrinsic value, so an MPT is only worth what its backing and market demand support. MPTs are widely used for real-world and institutional assets, such as tokenized Treasury bills, stablecoins, or loyalty rewards, where an issuer holds reserves or honors redemptions off the ledger. If that issuer fails or mismanages its reserves, the token can lose its value.

## Verifying an MPT before you opt in

Anyone can create an MPT on the XRP Ledger without permission or an approval process, which means scammers can copy the ticker, name, and icon of a legitimate project. Before opting in to hold or trade an MPT, always verify that the issuance ID and issuer address belong to the real project. See: _Token vetting and the token warning_.

## See Also

* How issued tokens work on the XRP Ledger
* NFTs
* Token vetting and the token warning
* Multi-Purpose Tokens (XRPL docs)
