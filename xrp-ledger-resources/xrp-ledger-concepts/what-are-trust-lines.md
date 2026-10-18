---
description: >-
  Understand Trust Lines. What a Trust Line is, why it exists, how it works, and
  whether it is dangerous.
---

# What are Trust Lines?

The XRP Ledger lets anyone create new assets. These are called **issued assets**, or simply **tokens**. In this article we explain what a token is, what a Trust Line is and why the ledger needs one, what a Trust Line costs, and how to keep yourself safe.

#### Why Trust Lines exist

A token on the XRP Ledger can represent almost anything. It can represent a cryptocurrency (such as Bitcoin or Ethereum), a fiat currency (such as US dollars or euros), a commodity, or another type of financial instrument. Any account on the ledger can issue a token.

Issuing a token on the XRP Ledger is easy. It takes no coding, it is cheap, and it is quick. This is very different from creating a token on a network like Ethereum, where you must write and deploy a smart contract.

That simplicity has two sides.

* **For legitimate issuers** it makes it easy and affordable to put an asset on the ledger.
* **For scammers** it makes it easy to issue a worthless token and try to trick someone into holding it.

Trust Lines manage this. A token cannot be created or circulated unless at least one account holds a Trust Line to its issuer. And a token can only reach your account if you hold a Trust Line to the issuer. This is what stops the ledger from being spammed with tokens you never asked for.

#### What is XRP on the XRP Ledger?

XRP is the **native asset** of the ledger. It is the one asset that needs no Trust Line at all. You can send XRP to any account freely, with no Trust Line and no conditions.

XRP is also used to pay the small network fee on every transaction, and to cover the reserves that keep your account in good standing. See [About Reserves](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/about-reserves).

Every other asset you hold is an issued asset, and every issued asset sits on a Trust Line.

#### What is a Trust Line?

A token has two identifying parts:

1. A currency code (for example **USDC** or **GLD**)
2. The r-address of the account that issued it

The currency code alone does not identify a token. Two different issuers can both issue a token called **GLD**, and those are two different assets. The code is also case sensitive, so **BTC**, **btc**, and **Btc** are three different assets on the ledger.

A **Trust Line** is a record on the XRP Ledger, owned by your account, that names one issuer for one currency code. It says: _"this account is willing to hold this issuer's version of this token."_ You create it with a **TrustSet** transaction that you sign in Xaman. Until it exists, the issuer cannot send you the token, and you cannot buy, sell or hold it.

Think of it as an "allow list". You add an issuer once, and the entry stays until you remove it. One issuer can issue more than one token, and you can hold a Trust Line to each of them.

**Creating a Trust Line does not expose your account to any attack.** It does not move your funds, it cannot sign for you, and it does not hand anything to the issuer. It only opens your account to receive that issuer's token.

#### Why does the XRP Ledger work this way?

On networks like Ethereum, any address can be forced to hold a token from any other address. You might have seen this in the form of unsolicited "airdrops" appearing in wallets, and some of them are part of outright scams.

The XRP Ledger takes the opposite approach. Your account is willing to hold XRP and nothing else until you say otherwise. Every token you hold arrived there with your explicit consent. This keeps the spam that can reach you limited to issuers you have deliberately opted into.

#### What Trust Lines let you do

A Trust Line is not only a gate. It is what unlocks trading on the ledger.

* **Receiving tokens.** A sender's token only arrives if you hold a Trust Line to its issuer.
* **Trading.** Any asset on the ledger can trade against any other, including XRP. Most swaps in Xaman involve a token that arrives on a new Trust Line, so a trade often creates one for you automatically. Xaman's **Auto-bridging** can route a swap through XRP when that gives better liquidity, so thin direct markets rarely get in your way.
* **Holding.** A Trust Line is where a token "lives" in your account. You can hold as many as you like.
* **Ecosystem access.** Some xApps, DeFi products, and airdrops require a Trust Line to a specific issuer before they work for you.

#### The limit on a Trust Line

When you create a Trust Line you can set a **limit**, the maximum amount of that issuer's token you are willing to hold.

* The limit stops **other people** from pushing you past it.
* Your own actions can still take you above it. If you buy more of a token in a trade, or if you lower the limit after you already hold a balance, your balance can end up higher than the limit.
* In Xaman a working limit is set automatically when a Trust Line is created, so you do not need to manage this value.

#### Native and non-native assets

XRP is the native asset. Everything else is an issued asset, and many of them represent something that lives outside the ledger.

The important thing is that the ledger itself does not know what a token represents. It tracks the token, not the gold, the Bitcoin, or the dollar behind it. You could set a Trust Line limit for a Bitcoin token far above the 21 million Bitcoin that will ever exist, and the ledger would accept it, because it has no knowledge of Bitcoin. The value of a token depends entirely on the issuer standing behind it.

#### How much does a Trust Line cost?

| Action              | Xaman service fee | Network fee            | Owner reserve                |
| ------------------- | ----------------- | ---------------------- | ---------------------------- |
| Create a Trust Line | Free              | 0.00001 XRP (10 drops) | 0.2 XRP locked               |
| Hold a Trust Line   | Free              | None                   | 0.2 XRP stays locked         |
| Remove a Trust Line | Free              | 0.00001 XRP (10 drops) | 0.2 XRP released back to you |

A few notes:

* The **0.2 XRP owner reserve** does not leave your account. The ledger marks it as un-spendable, the same way it marks the 1 XRP base reserve. It comes back in full the moment the Trust Line is removed. This is why cleaning up old Trust Lines can free up small amounts of XRP.
* **New accounts get a discount.** While your account is very new and holds at most 2 objects, the owner reserve is waived. In practice this means your first Trust Line costs nothing at all.
* The network fee is 10 drops at normal load and can rise slightly during periods of heavy network activity.&#x20;
* Removing a Trust Line manually is only possible when it is **empty**. You must send, sell, or otherwise move the tokens off it first. See [How to remove a Trust Line](https://help.xaman.app/app/all-about-xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line).

#### Are Trust Lines dangerous?

The Trust Line mechanism itself is not dangerous. It cannot move your funds, it cannot sign for you, and it costs nothing except the recoverable 0.2 XRP reserve.

The real risk is in _which issuer_ you open a Trust Line to. Here is how to think about it:

1. **Only create a Trust Line to an issuer you recognize.** If a token in Xaman shows an issuer r-address you do not expect, do not add it.
2. **The issuer controls more than you might think.** An issuer can charge a transfer fee on their token, and an issuer can freeze the token, either in a specific holder's account or across the whole token. There is a common belief that XRP can be frozen. That is not true. XRP is the backbone of the ledger and cannot be frozen. Only issued assets can be frozen, and only by their issuer.
3. **Issuers go out of business.** A token's value depends on the entity behind it standing ready to honor it. When that entity disappears, the token usually becomes worthless, even if it once represented a real asset. Check the issuers behind the tokens you hold, and clean up Trust Lines you no longer need.
4. **Receiving a token you did not ask for is a common scam pattern.** A stranger can send you any token whose issuer you already have a Trust Line to. This is how dust and spam tokens show up in accounts.  See [Spam on the XRP Ledger](https://help.xaman.app/app/all-about-scams/spam-on-the-xrp-ledger) and [Dust attacks](https://help.xaman.app/app/all-about-scams/dust-attacks).
5. **A Trust Line is public.** Anyone can look at the ledger and see every issuer your account has a Trust Line to. This is not a secret relationship.
6. **Trust Lines are not reversible by Xaman.** Once you have signed a TrustSet, the relationship exists on the network. Xaman cannot undo it for you. You can remove it yourself at any time, following the steps in [How to remove a Trust Line](https://help.xaman.app/app/all-about-xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line).

The short version: a Trust Line is a normal, low-risk part of using the XRP Ledger. The danger is never the mechanism. The danger is the issuer on the other end of it.

{% hint style="info" %}
**The short version**\
\
Trust Line is a normal, low-risk part of using the XRP Ledger. The danger is never the mechanism. The danger is the issuer on the other end of it.
{% endhint %}

#### How to create a Trust Line in Xaman

1. From the main screen, tap the **+ Add a token** button.
2. Choose a category (**Stable**, **Popular**, or **Ecosystem**) or search for a token by name.
3. Tap the token you want.
4. Tap **Setup TrustLine** and review the details.
5. Sign the transaction. The Trust Line is created.

The full walkthrough with screenshots is in [How to create a Trust Line](https://help.xaman.app/app/learning-more-about-xaman/how-to-create-a-trust-line).

#### Frequently asked questions

**Can I hold the same token code from two different issuers?**

Yes. A Trust Line is per issuer and per currency code. If two issuers both issue a "BTC" token, you can hold both at the same time on two separate Trust Lines, and Xaman shows them as two distinct assets.

**Can someone send me a token I do not have a Trust Line for?**

No. The transfer fails on the network. This is also why a Trust Line has to exist before a trade involving a new token can complete, and why Xaman creates one automatically when you first swap for a token you do not hold.

**Can I receive more of a token than my Trust Line limit allows?**

Yes, but only through your own actions. The limit stops other people from pushing you over it. When you buy more of a token in a trade, the ledger treats your open order as your consent to hold the result. You can also end up above the limit if you lower it after you already hold a balance.

**Does the issuer see my account?**

Yes, in a limited sense. The Trust Line is a public record that names your account and the issuer's account. The issuer does not get your account secret or any signing ability. They can see that your account holds their token, which is true of any public ledger.

**Do I have to set a limit on a Trust Line?**

No. When Xaman creates a Trust Line for you, it sets a working limit automatically. You do not need to manage this value.

**Can I delete my account while I have Trust Lines?**

No, before an account can be deleted, you must make sure all of your Trust Lines have been removed from your account. See [Deleting an XRPL account](../../learning-more-about-xumm/deleting-an-xrpl-account.md).

**Does Xaman charge a service fee for creating a Trust Line?**

No. Creating and removing a Trust Line is on the free list of the [Xaman service fee](https://help.xaman.app/app/getting-started-with-xaman/understanding-the-xaman-service-fee). You only pay the small network base fee, and the 0.2 XRP reserve is always returned to you.

#### See also

* [About Reserves](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/about-reserves)
* [How to create a Trust Line](https://help.xaman.app/app/learning-more-about-xaman/how-to-create-a-trust-line)
* [How to remove a Trust Line](https://help.xaman.app/app/all-about-xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line)
* [Spam on the XRP Ledger](https://help.xaman.app/app/all-about-scams/spam-on-the-xrp-ledger)
