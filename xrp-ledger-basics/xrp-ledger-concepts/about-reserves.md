---
description: Why part of your XRP cannot be spent, and how to get it back
---

# Reserves on the XRP Ledger

### Background

Every account on the XRP Ledger (XRPL) must hold a minimum amount of XRP, called a reserve. The XRP Ledger sets this XRP aside, so you cannot send or spend it. If you have ever wondered why your full balance is never available to send, the reserve is the reason. The XRP stays in your account the whole time, and you can get most of it back when you no longer need it.

Reserves keep the XRP Ledger small and fast. Creating accounts and objects costs XRP, which makes spam expensive and stops the XRP Ledger from filling up with unused data. Reserves are part of the XRP Ledger itself, not Xaman, so every wallet shows the same reserves for the same account. Xaman never holds or touches your reserved XRP.

This article covers the XRP Ledger. Xahau has reserves of its own, explained in [_Understanding Reserves on Xahau_](../../xahau/understanding-reserves-on-xahau.md).

### The two kinds of reserve

The XRP Ledger has two kinds of reserves:

* The base reserve is the minimum every account must hold. Your account cannot exist on the XRP Ledger without it.
* The owner reserve is an extra amount for each object your account owns, such as a [trust line](#user-content-fn-1)[^1] or an escrow[^2].

The validators[^3] that run the XRP Ledger can vote to change both amounts, and over the years they have lowered them several times. That is why this article does not print the amounts. The **Reserved** screen in Xaman always shows the current ones for your account (see _See your reserves in Xaman_).

### Objects that need an owner reserve

Each of these objects adds one owner reserve to your account:

* A trust line to a token.
* An open offer on the decentralized exchange (DEX).
* An escrow.
* A Check.
* A payment channel.
* A signer list, for multi-signing.
* A page of non-fungible tokens (NFTs). Each page holds up to 32 NFTs, so several NFTs can share one reserve.

Some newer objects also need an owner reserve, such as Multi-Purpose Tokens (MPTs). You never need to work this out yourself: the **Reserved** screen in Xaman lists every object in your account that holds a reserve.

### See your reserves in Xaman

1. On the **Home** screen, tap **Reserved** under your XRP balance.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2F4eC66ArYGguZvQVnaq5R%2Fxaman-home-reserved-arrow_1x.png?alt=media&#x26;token=c4fabe75-841a-4a87-919d-effc2b999301" alt="The Xaman Home screen, with an arrow pointing at Reserved under the XRP balance" width="360"><figcaption><p>Reserved sits just under your XRP balance</p></figcaption></figure>

2. Check **Available for spending** for the XRP you can send, and **Reserved on ledger** for the objects that hold reserves.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FPJ0pvOK1hLkUIXqvIcwb%2Fxaman-balance-reserved.png?alt=media&#x26;token=944bc2cf-78c4-4b31-b9fc-2c0445605072" alt="The Xaman reserves screen, listing the base reserve and an owner reserve for each object" width="338"><figcaption><p>Reserved XRP and the objects that hold it</p></figcaption></figure>

### Release an owner reserve

When you remove an object from your account, the XRP Ledger releases its owner reserve, and that XRP becomes spendable again. How you remove an object depends on what it is:

* Trust line: send or remove the token balance first, then remove the trust line. See [How to remove a Trust Line](../../xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line.md).
* Offer: cancel the offer on the DEX.
* Escrow: finish or cancel the escrow. See [How to release an escrow](../../xapps/xrpl-services/escrow-creator/how-to-release-an-escrow.md).
* NFT page: remove every NFT on the page, by selling, sending, or burning them. See [How to Burn an NFT](../../tokens-trust-lines-and-nfts/nfts/nft-burn-process.md).

### Recover the base reserve

The only way to recover the base reserve is to delete your account from the XRP Ledger. Deleting an account costs a special transaction fee, much higher than a normal one, so the XRP you get back is your balance less that fee. Your account also needs to remove every object it owns first. See [How to delete an XRPL account](../../your-accounts/importing-your-account/how-to-delete-an-xrpl-account.md).

### Reserves and fees on video

If you would rather watch than read, this short video explains reserves and network fees together. It comes from an explainer series made when Xaman was still called Xumm, so the app looks different, and the amounts it mentions may be higher than today's. For your account's current reserves, check the **Reserved** screen.

{% embed url="https://youtu.be/7E52W4dKmBE" %}
Reserves and network fees, from the older Xumm explainer series
{% endembed %}

### Frequently asked questions

**Does Xaman set the reserves?**

No. The XRP Ledger sets the reserves, and its validators can vote to change them. Every wallet shows the same reserves for the same account, since they come from the XRP Ledger itself.

**Is the reserve a fee?**

No. A fee is gone once you pay it: every transaction pays a tiny [network fee](#user-content-fn-4)[^4], which the XRP Ledger destroys. Your reserve is never paid to anyone. It stays in your account, and you can release an owner reserve whenever you remove the object behind it.

**Where does my reserved XRP go?**

It stays in your account. The XRP Ledger marks it as unspendable until you remove the object it covers, or delete the account.

**Why is some of my XRP not available to send?**

Your account must always keep its reserves. You can send any XRP above them, minus a small network fee.

**Can the reserves change?**

Yes. The validators can vote to raise or lower the base reserve and the owner reserve. When they change, the reserved amount in your account changes automatically, with nothing for you to do.

### See also

* [How to delete an XRPL account](../../your-accounts/importing-your-account/how-to-delete-an-xrpl-account.md)
* [How to remove a Trust Line](../../xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line.md)
* [Trust lines on the XRP Ledger](../../tokens-trust-lines-and-nfts/trust-lines-on-the-xrp-ledger.md)
* [Understanding Reserves on Xahau](../../xahau/understanding-reserves-on-xahau.md)

[^1]: Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.

[^2]: XRP or tokens locked on the XRP Ledger until a set time or condition, then released to a chosen account.

[^3]: A computer that helps the XRP Ledger agree on which transactions are valid. Validators cannot reverse or change transactions.

[^4]: A tiny amount of XRP paid with every transaction. It is destroyed, not paid to anyone, which protects the network from spam.
