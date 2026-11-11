---
description: What is a token is on the XRP Ledger?
---

# How issued tokens work on the XRP Ledger

On the XRP Ledger, every asset except XRP is a token. The name on a token is a label anyone can pick. The issuer is what makes the token real.

### Coins and tokens

Many people call XRP the native coin of the network. That is a fair way to think about it. A coin is the asset a network builds in. A token is an asset an account issues on top of that network. On the XRP Ledger, XRP is the only coin. Every other asset on the ledger is a token.

Most other networks work the same way. ETH is a coin on Ethereum. SOL is a coin on Solana. Both networks also host tokens issued by accounts.

The official XRPL documents use the term "native asset" for XRP. The meaning is the same: XRP is built into the ledger, and it has no issuer.

### The three types of tokens

All assets other than XRP fall under one of three token standards:

| Standard                    | Type                                | Status                |
| --------------------------- | ----------------------------------- | --------------------- |
| Trust line tokens           | Fungible, all units interchangeable | In production         |
| Multi-Purpose Tokens (MPTs) | Fungible, plus unique issuance IDs  | In active development |
| Non-fungible tokens (NFTs)  | Unique, indivisible                 | In production         |

Most of what you see in Xaman is trust line tokens. NFTs are covered in [NFTs](https://help.xaman.app/app/learning-more-about-xaman/nfts). This article focuses on the fungible kinds.

### What a token is made of

A fungible token has three parts: a currency code, a value, and an issuer.

* The currency code is a short string the issuer picks. Standard codes are three characters, such as `USDC`.
* Codes are case-sensitive. `abc` and `ABC` are two different tokens.
* The code cannot be `XRP`.
* The issuer is an XRP Ledger account. Two tokens with the same code from two different issuers are two different tokens.

The code is a label. It tells you nothing about what the token is worth.

### A token named XLM is not XRP

Anyone can name a token anything, including `XLM`. XLM is the coin of the Stellar network, which is a different network from the XRP Ledger. A token named `XLM` on the XRP Ledger is a token issued by some account on the XRP Ledger. It has no connection to Stellar and no connection to XRP. If you see `XLM` in your account, you are holding a token. Check its issuer before you trust it.

### What gives a token value

The issuer gives a token its value.

In the stablecoin model, the issuer holds value outside the ledger, such as dollars in a bank account, and issues tokens that represent it.

In the IOU model, a token represents a debt the issuer owes you. The token is only worth what the issuer promises to honor it.

Either way, holding a token means holding a claim on an issuer. That is why the issuer, not the name, is what you should vet.

### Anyone can issue tokens

Anyone can issue any type of token on the XRP Ledger. No permission is needed. No approval is needed. There is no official list of "real" tokens, and there is no way to make the ledger refuse a name. This is a feature. It means anyone in the world can build a payment system on the ledger. It also means a scammer can pick a well-known name. For this reason, Xaman shows a warning on every token. See [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning) for what that warning means and what issuers can do instead.

### See Also

* [What are Trust Lines?](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/what-are-trust-lines)
* [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning)
* [GateHub's issued tokens](https://help.xaman.app/app/learning-more-about-xaman/gatehubs-issued-tokens)
* [NFTs](https://help.xaman.app/app/learning-more-about-xaman/nfts)





On the XRP Ledger, every asset except XRP is a token. The name on a token is a label anyone can pick. The issuer is what makes the token real.

**What a token actually is**

A token on the XRP Ledger is defined by two things:

1. A currency code, such as XLM, BTC, or USD
2. The r-address of the account that issued it

The currency code is just a name. Anyone can create a token and give it any name they want. The XRP Ledger does not stop them. It does not check that the name matches anything in the real world. The code is also case sensitive, so BTC, btc, and Btc are three different tokens.

XRP is the one asset that is not a token. It is the native asset of the ledger, it has no issuer, and it cannot be frozen. Every other asset you hold is a token, and every token has an issuer.

**A name is not the real thing**

We will use XLM as the example, since it is the question we hear most.

When you see a token called XLM in Xaman, what you hold is a token named XLM, issued by one specific account on the XRP Ledger. It is not the XLM that lives on the Stellar network. You cannot send it to Stellar. It is not the same asset as Stellar XLM. The two just share a name.

This is true for every name. Someone can issue a token called BTC, DOGE, or GOLD. Two different issuers can both issue a token called GLD, and those are two different assets. The XRP Ledger treats them as different, and so must you.

**What gives a token its value**

The only thing that gives a token its value is the issuer. The XRP Ledger tracks the token. It does not track the gold, the dollar, or the XLM behind it. The ledger has no way to know what a token is supposed to represent.

Some issuers stand behind their tokens. A stablecoin issuer, for example, holds real dollars or euros outside the ledger and issues tokens that represent that value. As long as the issuer keeps those assets and acts in a transparent way, the token holds its value. In the past these tokens were called "IOUs", and that term still helps you see the idea. The token is a promise from the issuer, not the thing itself.

If the issuer is a stranger, or a scammer, the token is worth nothing. No matter what they named it.

**Why anyone can do this, and why it matters**

Issuing a token on the XRP Ledger is easy. It takes no coding, it is cheap, and it is quick. This has two sides:

* For a legitimate issuer, it makes it easy and affordable to put a real asset on the ledger.
* For a scammer, it makes it easy to issue a worthless token and trick someone into holding it.

So the name on a token proves nothing. The issuer's address is what counts. Before you trust a token, find out who issued it and check that you recognize them.

\{% hint style="danger" %\} Anyone can issue a token with the same name as a well-known one. A token called XLM, BTC, or XAH is only as good as the account that issued it. Check the issuer before you add a token, and never give your account secret to anyone who asks you to. \{% endhint %\}

**See also**

* [What are Trust Lines?](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/what-are-trust-lines) how a token is stored, and what a Trust Line costs
* [How to create a Trust Line](https://help.xaman.app/app/learning-more-about-xaman/how-to-create-a-trust-line) the steps, with screenshots
* [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning) how to check an issuer
* [Understanding the XAH token on the XRP Ledger](https://help.xaman.app/app/xahau/understanding-the-xah-token-on-the-xrp-ledger) this same idea applied to XAH
* [GateHub's issued tokens](https://help.xaman.app/app/learning-more-about-xaman/gatehubs-issued-tokens) a real-world example of one issuer's
