---
description: What is a token on the XRP Ledger?
---

# How issued tokens work on the XRP Ledger

This article explains what a token is on the XRP Ledger, the three token standards, and why the issuer matters more than the name.

## Coins and tokens

The XRP Ledger has one native asset: XRP. People often call XRP a "coin." That is the common name for the native unit of a network, like bitcoin or ether. The XRPL docs use the term "native asset."

Every other asset on the ledger is a token. A token is an asset that someone issued.

## Three types of tokens

The XRP Ledger has three token standards:

| Standard                  | What it is                 | Status             |
| ------------------------- | -------------------------- | ------------------ |
| Trust line token          | Fungible tokens, version 1 | Live in production |
| Multi-Purpose Token (MPT) | Fungible tokens, version 2 | Live in production |
| Non-fungible token (NFT)  | Unique, indivisible tokens | Live in production |

Trust line tokens are the subject of this article. (Both NFTs and MPTs have their own articles. See [NFTs](https://help.xaman.app/app/learning-more-about-xaman/nfts) and MPTs.)

## How trust line tokens are identified

Every trust line token is defined by two things:&#x20;

* a currency code&#x20;
* an issuer

When expressing a balance or payment, an amount is included as well (for example, `50 USD issued by Bitstamp`).

Standard currency codes are 3 case-sensitive characters using letters, digits, or select symbols—meaning `usd` and `USD` represent two distinct tokens. Longer tickers (such as `USDC` or `RLUSD`) are supported using 40-character hexadecimal codes. The code `XRP` is reserved exclusively for the ledger's native asset.

## Why the issuer matters

Currency codes are not unique. Multiple accounts can issue tokens with the same familiar ticker, such as `BTC`, `ETH`, or `USD`. Even if two tokens display the same ticker in your wallet, the ledger treats them as completely separate assets with different backing and value. The issuer address is what tells them apart.

## What gives a token value

A currency code is just a label. A token's value depends on its issuer and market demand. For asset-backed tokens like stablecoins, the issuer holds real-world reserves off the ledger, such as one U.S. dollar for every token issued, and backs their redemption. In these cases, a token is only as reliable as the issuer behind it; if the issuer fails or mismanages its reserves, the token can lose its value.

## Permissionless issuance

Anyone can issue a token on the XRP Ledger without permission or an approval process. While this openness lets legitimate projects launch quickly, it also allows scammers to impersonate established assets by copying their tickers. Before accepting or trading a token, always verify that the issuer address belongs to the real project. See:  [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning).

### See Also

* [NFTs](https://help.xaman.app/app/learning-more-about-xaman/nfts)
* [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning)
* [Understanding the XAH token on the XRP Ledger](https://help.xaman.app/app/xahau/understanding-the-xah-token-on-the-xrp-ledger)
* [Multi-Purpose Tokens (XRPL docs)](https://xrpl.org/docs/concepts/tokens/fungible-tokens/multi-purpose-tokens)
