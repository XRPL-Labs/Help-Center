---
description: What common Xaman and XRP Ledger terms mean, in plain words
---

# Glossary

### Background

Xaman and the XRP Ledger (XRPL) come with their own vocabulary, and it can feel like a lot when you are new. This glossary explains the words you are most likely to meet in the app and in this Help Center, in plain language. Keep it open in another tab while you read, and come back whenever a word stops you.

The XRP Ledger is the network Xaman connects to, and XRP is its native coin. This glossary covers the XRP Ledger. Xahau is a separate network that Xaman also supports, with its own set of Help Center articles, so it appears here only as a term. Many terms in other articles also show a short explanation when you tap or hover over them, and those explanations use the same words as this glossary.

### Xaman, accounts, and keys

These words describe what you own and how you control it. The most important one is your account secret, since whoever holds it controls the account and everything in it. Many of the other terms here, from keys to access levels, are about who can sign for an account.

| Term               | Meaning                                                                                                                                  |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| account secret     | The secret that controls your account, as Secret Numbers, a Family Seed, or a Mnemonic. Never share it with anyone.                      |
| activate           | Sending an account its first XRP, enough to cover its reserve. Until then, the account does not exist on the XRP Ledger.                 |
| Family Seed        | An account secret written as a code that starts with "s". Anyone who has it controls your account.                                       |
| **Full access**    | An account Xaman can sign transactions for, since its account secret or card is in the app.                                              |
| master key         | The key created with your account, from its account secret. It can be turned off once another key is in place.                           |
| Mnemonic           | An account secret written as a list of 12, 16, or 24 words, sometimes called a recovery phrase. Anyone who has it controls your account. |
| multi-signing      | A setup where several keys must sign together before a transaction goes through.                                                         |
| passcode           | The six-digit code that unlocks Xaman and approves transactions on your phone. It is not your account secret.                            |
| r-address          | Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.                                            |
| **Read only**      | An account you can view in Xaman but cannot sign transactions for.                                                                       |
| regular key        | A second key that can sign for your account, such as a Backup card.                                                                      |
| rekey              | Giving your account a new regular key, so a different key can sign for it.                                                               |
| reserve            | XRP that every active XRP Ledger account must keep and cannot spend. The network sets the amount, and it can change.                     |
| Secret Numbers     | Xaman's format for an account secret: eight rows of six digits. Anyone who has them controls your account.                               |
| self-custody       | You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.                   |
| sign               | Approving a transaction with your account's key. In Xaman, you slide to accept and confirm with your passcode or biometrics.             |
| sign request       | A transaction an app or website prepares and sends to Xaman for you to review. Nothing happens unless you sign it.                       |
| wallet             | An app that holds the keys to your accounts and lets you sign transactions. Your funds are on the XRP Ledger, not inside the app.        |
| X-address          | A longer address that combines an r-address and a Destination Tag into one.                                                              |
| Xaman              | The self-custody wallet app made by XRPL Labs, formerly called Xumm.                                                                     |
| XRP Ledger account | Your place on the XRP Ledger, where your XRP and tokens are held. Each account has its own r-address.                                    |
| XRPL Labs          | The company behind Xaman.                                                                                                                |

{% hint style="danger" %}
Anyone who has your account secret controls your account and its funds. Our support team will never ask for your account secret. Anyone who asks for it is trying to take your funds, so never share it.
{% endhint %}

### Sending and receiving

These terms come up whenever XRP or tokens move between accounts. Once the XRP Ledger validates a transaction, the transaction is final: neither Xaman nor the network can reverse or cancel it. That is why a few of these words, such as Destination Tag, matter so much when you send to an exchange.

| Term              | Meaning                                                                                                                                          |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Check             | A promise of payment on the XRP Ledger. The funds move only when the receiver cashes it.                                                         |
| custodial         | Held for you by a company. On a custodial service, the company controls the funds, not you.                                                      |
| Destination Tag   | A number that tells an exchange which customer a payment is for. Copy it exactly from the exchange's deposit page.                               |
| escrow            | XRP or tokens locked on the XRP Ledger until a set time or condition, then released to a chosen account.                                         |
| exchange          | A company that holds crypto for its customers, the way a bank holds money. You do not hold the keys to funds kept there.                         |
| explorer          | A website that shows public XRP Ledger data, such as an account's balance, settings, and transaction history.                                    |
| memo              | An optional note attached to a payment. It is not the same as a Destination Tag.                                                                 |
| network fee       | A tiny amount of XRP paid with every transaction. It is destroyed, not paid to anyone, which protects the network from spam.                     |
| payment channel   | A way to send many small XRP payments quickly, settling them on the XRP Ledger together later.                                                   |
| service fee       | A small fee Xaman charges for some features. It is always shown on the review screen before you sign.                                            |
| source tag        | A number that tells the receiver where a payment came from, so they know where to return it.                                                     |
| transaction       | Any action recorded on the XRP Ledger, such as a payment or adding a trust line. Each one needs a signature.                                     |
| transaction ID    | A transaction's unique ID, also called a transaction hash. It helps you find the transaction in an explorer, or show support which one you mean. |
| validated         | Confirmed by the XRP Ledger. A validated transaction is permanent and cannot be reversed.                                                        |
| validator         | A computer that helps the XRP Ledger agree on which transactions are valid. Validators cannot reverse or change transactions.                    |
| XRP               | The native coin of the XRP Ledger. Every account needs some to exist, and every transaction pays a tiny fee in XRP.                              |
| XRP Ledger (XRPL) | A public network, run by independent computers around the world, that records who owns what. XRP is its native coin.                             |

### Tokens and NFTs

Anything on the XRP Ledger other than XRP is a token, and tokens work differently from XRP. Each token depends on the account that issued it, and some issuers can freeze their token or take it back. XRP has no issuer, so no one has those powers over it.

| Term                      | Meaning                                                                                                                             |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| blackholed account        | An account that has given up every way of signing, on purpose and for good. Many token issuers do this to fix their token's supply. |
| burn                      | Permanently destroying an NFT, so it no longer exists.                                                                              |
| clawback                  | An issuer's power to take its token back from a holder. It only exists if the issuer turned it on before issuing.                   |
| coin                      | A network's native currency, such as XRP on the XRP Ledger. Anything issued on top of a network is a token, not a coin.             |
| freeze                    | A pause a token's issuer can place on its token, stopping it from being sent or traded.                                             |
| issuer                    | The account that creates a token. Anyone can be an issuer, and any issuer can give a token any name.                                |
| Multi-Purpose Token (MPT) | A newer kind of XRP Ledger token, with settings its issuer fixes when it is created.                                                |
| non-fungible token (NFT)  | A unique digital item on the XRP Ledger, such as artwork or a ticket. Each one is one of a kind.                                    |
| stablecoin                | A token designed to keep a steady value, usually matching a currency such as the US dollar.                                         |
| token                     | A digital asset created on the XRP Ledger by an issuer. Unlike XRP, a token's value depends on whoever issued it.                   |
| trust line                | Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.           |

### Trading on the DEX

The XRP Ledger has a marketplace built into it, so you can trade straight from your account without handing your funds to an exchange. Trading has its own language, and a few of these terms describe risks worth understanding before you place an order. Liquidity, slippage, and the spread all affect the price you actually get.

| Term                          | Meaning                                                                                                                                                                                    |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Automated Market Maker (AMM)  | A pool of two assets on the XRP Ledger that anyone can trade with or add to.                                                                                                               |
| decentralized exchange (DEX)  | The XRP Ledger's built-in marketplace, where you can trade XRP and tokens straight from your account.                                                                                      |
| liquidity                     | How easily a token can be bought or sold without moving its price much. With few buyers and sellers, even a small trade can move the price a lot.                                          |
| liquidity provider (LP) token | A token you receive for adding assets to an AMM pool. It represents your share of that pool.                                                                                               |
| market order                  | An order to buy or sell right away, at the best prices currently offered on the DEX. With few offers available, it can fill at a much worse price than expected.                           |
| order book                    | The list of open offers to buy and to sell a token on the DEX, with how much is offered at each price.                                                                                     |
| slippage                      | The difference between the price you expected for a trade and the price you got. It happens when prices move, or when an order is larger than the offers at your price.                    |
| spread                        | The gap between the highest price buyers offer and the lowest price sellers ask. If buyers offer 100 XRP for some tokens and sellers ask 105 XRP for the same tokens, the spread is 5 XRP. |

{% hint style="warning" %}
A market order on a token with few offers can fill at a much worse price than you expect. A completed trade cannot be reversed. Check the offers on both sides of the order book before you trade.
{% endhint %}

### Security and scams

Scams on the XRP Ledger follow a few familiar patterns, and knowing their names makes them easier to spot. When something feels wrong, the Xaman Support xApp is the place to ask. Xaman does not offer support through social media, so anyone who contacts you there claiming to be Xaman support is not.

| Term               | Meaning                                                                                                                     |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| airdrop            | Free tokens sent to many accounts at once. A real one never asks for your account secret or a signature to claim it.        |
| biometrics         | Unlocking Xaman with your face or fingerprint instead of typing your passcode.                                              |
| dust               | A tiny amount of XRP or tokens sent to many accounts, often to advertise a scam. Do not interact with it.                   |
| phishing           | A fake website, message, or app that copies a real one, to trick you into signing something or sharing your account secret. |
| recovery scam      | A scam that targets people who have lost crypto, promising to get it back for a fee.                                        |
| Xaman Support xApp | The only official way to contact Xaman support. It opens inside the app.                                                    |

### Xaman cards, xApps, and other networks

Xaman does more than hold your accounts. These terms cover the extras: physical cards that keep your account secret on a chip, small apps that run inside Xaman, identity checks, and the other networks Xaman works with.

| Term                           | Meaning                                                                                                                                     |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Backup card                    | A second Xaman card linked to your Primary account, so either card can sign for it.                                                         |
| earnXRP                        | Your share of the Flare yield vault. Each earnXRP becomes worth a little more FXRP as yield builds up.                                      |
| Flare                          | A separate network that works with the XRP Ledger. Xaman's Flare xApp uses it to earn yield on XRP.                                         |
| FXRP                           | A token on the Flare network that represents XRP, one for one.                                                                              |
| Know Your Customer (KYC)       | Identity checks that some services must run, by law, before you can buy or withdraw.                                                        |
| near-field communication (NFC) | The technology your phone uses for tap-to-pay. Xaman uses it to talk to your Xaman cards.                                                   |
| Primary card                   | The Xaman card whose account holds your funds.                                                                                              |
| Testnet                        | A practice version of the XRP Ledger, with XRP that has no value, used for testing.                                                         |
| XAH                            | The native coin of Xahau.                                                                                                                   |
| Xahau                          | A separate network, related to the XRP Ledger, with its own accounts and its own coin, XAH. Xahau has its own articles in this Help Center. |
| Xaman card                     | A physical card with a secure chip that creates and keeps an account secret. The secret never leaves the card.                              |
| xApp                           | A small app that runs inside Xaman, made by Xaman or by other developers.                                                                   |

### Frequently asked questions

**Why does Xaman say "account secret" instead of "private key"?**

Your account secret can come in three formats: Secret Numbers, a Family Seed, or a Mnemonic. Other wallets often call these a private key, seed phrase, or recovery phrase. Xaman uses one name for all of them, so it is always clear which thing must stay private. Whatever the format, the rule is the same: anyone who has it controls your account.

**What is the difference between a coin and a token?**

A coin is a network's own currency, such as XRP on the XRP Ledger. A token is anything an issuer creates on that network, including stablecoins, MPTs, and NFTs. The difference matters, since a token's name tells you nothing on its own. Any issuer can give a token any name, even "XRP", and only the issuer's r-address shows which token you actually hold.

Crypto assets can change in value. This article explains what these terms mean and is not financial advice.

### See also

* [Self-Custody 101: Staying Safe with Xaman](../../getting-started-with-xaman/what-is-xaman/self-custody-101-staying-safe-with-xaman.md)
* [What do "Full" and "Read Only" mean in Xaman?](../../getting-started-with-xaman/what-is-xaman/what-do-full-and-read-only-mean-in-xaman.md)
* [Reserves on the XRP Ledger](about-reserves.md)
* [Destination tags](../../sending-receiving-and-cashing-out/destination-tags.md)
* [Trust lines on the XRP Ledger](../../tokens-trust-lines-and-nfts/trust-lines-on-the-xrp-ledger.md)
* [Token freezes and clawback](../../tokens-trust-lines-and-nfts/token-freezes-and-clawback.md)
* [Token vetting and the token warning](../../tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning.md)
* [Xaman & AMM](../../tokens-trust-lines-and-nfts/xaman-and-amm.md)
