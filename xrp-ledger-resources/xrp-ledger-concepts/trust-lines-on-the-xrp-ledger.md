---
description: What a Trust Line is, what it costs, and how to use one safely
---

# Trust Lines on the XRP Ledger

### Background

The XRP Ledger (XRPL) lets any account create new assets, called tokens. A token can represent almost anything, such as a fiat currency, another cryptocurrency, or a commodity.

XRP is the XRP Ledger's own coin. It is the only asset that needs no Trust Line, so any account can receive XRP. Every other asset is a token, issued by an account on the XRP Ledger.

To hold a token, your account first needs a Trust Line to the token's issuer. Newer Multi-Purpose Tokens (MPTs) use a different ledger object, but follow the same rule: you must opt in before you can hold them.

### What a Trust Line is

Every token has two identifying parts:

* A currency code, such as USDC or GLD.
* The r-address of the account that issued it.

The currency code alone does not identify a token. Two issuers can both issue a token called GLD, and those are two different assets. Currency codes are also case-sensitive, so BTC, btc, and Btc are three different assets.

A Trust Line is a record on the XRP Ledger, owned by your account, for one currency code from one issuer. It says that your account is willing to hold that issuer's token. You create it with a transaction you sign in Xaman.

Think of a Trust Line as an entry on an allow list. Until it exists, no one can send you that token, and you cannot hold it. The entry stays until you remove it.

### Why the XRP Ledger uses Trust Lines

Creating a token on the XRP Ledger takes no coding and costs very little. That makes it easy for legitimate issuers, and also for scammers who want to issue worthless tokens.

Trust Lines limit the damage. A token can only reach your account if you have a Trust Line to its issuer. On networks where any address can receive any token, unwanted tokens can appear in your wallet without your consent. On the XRP Ledger, your account holds only XRP until you choose otherwise.

### What a Trust Line lets you do

A Trust Line is what lets your account use a token:

* Receive the token from other accounts.
* Hold the token in your account.
* Trade the token on the XRP Ledger's decentralized exchange (DEX). When you swap for a token you do not hold yet, the XRP Ledger creates the Trust Line for you as part of the trade.
* Use xApps and services that work with that token.

The XRP Ledger's auto-bridging can route a trade through XRP when that gives a better rate. This helps when there is little direct trading between two tokens.

### The Trust Line limit

Every Trust Line has a limit, the most of that token your account is willing to hold. Xaman sets a working limit for you when it creates a Trust Line, so you do not need to manage it.

The limit only stops other accounts from sending you more than it allows. Your own actions can take you above it, for example when you buy more of the token in a trade.

### What a token represents

The XRP Ledger tracks tokens, not the assets behind them. It does not know whether a token represents gold, dollars, or nothing at all. A token is only worth something if its issuer stands behind it.

### What a Trust Line costs

| Action              | Xaman service fee | Network fee         | Owner reserve                     |
| ------------------- | ----------------- | ------------------- | --------------------------------- |
| Create a Trust Line | None              | A small network fee | One owner reserve is set aside    |
| Hold a Trust Line   | None              | None                | The owner reserve stays set aside |
| Remove a Trust Line | None              | A small network fee | The owner reserve is released     |

The owner reserve never leaves your account. The XRP Ledger marks it as unspendable while the Trust Line exists, and releases it when you remove the Trust Line. See _Reserves on the XRP Ledger_ for the current amounts.

If your account owns fewer than two objects, you can create a Trust Line even without enough XRP to cover its reserve. The reserve still applies afterward, so it reduces the XRP you can spend.

To remove a Trust Line, its balance must be zero and its settings must be back to their defaults. Send or sell your tokens first. See _How to remove a Trust Line_.

### Are Trust Lines dangerous?

A Trust Line cannot move your funds, sign transactions for you, or give the issuer access to your account. The risk is the issuer you trust, not the Trust Line itself.

Before you add a Trust Line, keep these points in mind:

1. Only add a Trust Line to an issuer you recognize. If the issuer's r-address is not the one you expect, do not add it.
2. Issuers have control over their tokens. An issuer can charge a transfer fee, and can freeze its token, for one holder or for all of them. Only tokens can be frozen. XRP cannot be frozen.
3. Some issuers can claw back their tokens, taking them back out of your account. An issuer can only do this if it turned the option on before it issued any tokens. See [_Clawing back tokens_](https://xrpl.org/docs/concepts/tokens/fungible-tokens/clawing-back-tokens) on xrpl.org.
4. Issuers can go out of business. When they do, their tokens usually become worthless, even if they once represented a real asset.
5. Anyone can send you a token whose issuer you already trust. This is how dust and spam tokens appear in accounts. See [_Spam on the XRP Ledger_](../../scams-and-staying-safe/spam-on-the-xrp-ledger.md) and [_Dust attacks_](../../scams-and-staying-safe/dust-attacks.md).
6. Trust Lines are public. Anyone can see which issuers your account trusts.

{% hint style="info" %}
A Trust Line is a normal, low-risk part of using the XRP Ledger. The risk is the issuer at the other end of it.
{% endhint %}

### Create a Trust Line in Xaman

1. On the home screen, tap **+ Add a token**.
2. Choose a category, or search for a token by name under the Exosystem tab.
3. Tap the token you want.
4. Tap **Setup TrustLine** and check the details.
5. Slide to accept.

For the full steps with screenshots, see [_How to create a Trust Line_](../../learning-more-about-xaman/how-to-create-a-trust-line.md).

### Frequently asked questions

**Can I hold the same currency code from two issuers?**

Yes. A Trust Line is for one currency code from one issuer. If two issuers both issue a token called BTC, you can hold both on two separate Trust Lines. Xaman shows them as two different assets.

**Can someone send me a token I do not have a Trust Line for?**

No. The payment fails on the XRP Ledger. When you swap for a new token yourself, the XRP Ledger creates the Trust Line as part of the trade.

**Can my balance go above my Trust Line limit?**

Yes, but only through your own actions. The limit stops other accounts from sending you more. Buying the token in a trade, or lowering the limit after you already hold a balance, can leave you above it.

**Can the issuer see my account?**

Yes. A Trust Line is a public record that names your account and the issuer's account. The issuer cannot see your account secret or sign for you.

**Can I delete my account while I have Trust Lines?**

No. Before you can delete your account, you need to remove all of its Trust Lines and other objects. See _How to delete an XRPL account_.

**Does Xaman charge a service fee for Trust Lines?**

No. Creating and removing a Trust Line has no Xaman service fee. You pay only the network fee. See [_Understanding Xaman Service Fees_](../../getting-started-with-xaman/understanding-the-xaman-service-fee.md).

### See also

* [Reserves on the XRP Ledger](about-reserves.md)
* [How to create a Trust Line](../../learning-more-about-xaman/how-to-create-a-trust-line.md)
* [How to remove a Trust Line](../../all-about-xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line.md)
* [Spam on the XRP Ledger](../../scams-and-staying-safe/spam-on-the-xrp-ledger.md)
* [Multi-Purpose Tokens on xrpl.org](https://xrpl.org/docs/concepts/tokens/fungible-tokens/multi-purpose-tokens)
* [Clawing back tokens on xrpl.org](https://xrpl.org/docs/concepts/tokens/fungible-tokens/clawing-back-tokens)
