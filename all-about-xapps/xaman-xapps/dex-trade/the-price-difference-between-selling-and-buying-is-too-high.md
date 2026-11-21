---
description: The price difference between selling and buying is too high
---

# The price difference between selling and buying is too high

### Situation

When trying to purchase or swap tokens, you receive the message, "The price difference between selling and buying is too high".<br>

<figure><img src="../../../.gitbook/assets/Price difference.png" alt=""><figcaption></figcaption></figure>

### Relevant terminology

**The DEX**&#x20;

XRP Ledger has a native decentralized exchange (DEX) that lets anyone buy or sell any asset that exists on the XRPL. Since anyone can issue assets on the XRPL, the DEX is an incredibly useful and powerful tool. It is basically a global market place where buying and selling takes place at any time. &#x20;

**The Spread**&#x20;

The spread is the difference between the bid and the ask prices of a token on the DEX. For example, if you place an order for 100 tokens for 100 XRP, but the current orders are for 100 tokens for 105 XRP, the spread is 5 XRP. You are bidding 100 XRP, people are asking for 105 XRP. The difference is 5 XRP. &#x20;

**Market Order**&#x20;

A market order is a transaction that tries to buy or sell tokens at the best available price on the DEX. If you are going to place a market order, you should review the charts and the order book depth before placing an order. Make sure that there is a market on both sides of the order book. This means lots of sellers and lots of buyers. If there is only a large number of sell orders, it means that you are trading in an illiquid asset.&#x20;

### How Xumm works

Any market order placed on the DEX tries to buy/sell the tokens **immediately** based on the current order books and token liquidity. We built safety features into Xumm that prevents unexpected results when placing an order so, if the **Spread is more than 4%**, you will receive above message. In other words, Xumm does not allow the instant market swap/trade of a token pair that results in a user receiving significantly less than the current spot price. (Which could happen with illiquid tokens.) If Xumm allowed this to happen, you could lose a significant percentage of your funds if you decided to trade back to your original asset.

### How to exchange tokens

{% hint style="danger" %}
Only proceed if you understand and accept that by trading the selected asset you are at risk of getting bad exchange rates.&#x20;
{% endhint %}

Trading in assets that have low liquidity can be risky. One of the better options to limit this risk is to create a **limit order** and specify the exact price you would like your order to be executed at. This allows the DEX to match your order at your desired price when it becomes available.&#x20;

Xumm comes with an xApp that will allow you to create a limit order called the [**DEX Trade xApp**](https://xumm.app/detect/xapp:xumm.dex).&#x20;



### **What are these "3rd party Xumm enabled applications"?**

There are several other ways to place orders on the DEX, but remember, dealing with illiquid tokens can result unexpected results.&#x20;

*   Browser:

    * [https://www.xrptoolkit.com](https://www.xrptoolkit.com/)
    * [https://dex.onxrp.com](https://dex.onxrp.com/)
    * [https://unhosted.exchange/?base=XRP\&quote=EUR\_rhub8VRN55s94qWKDv6jmDy1pUykJzF3wq](https://unhosted.exchange/?base=XRP\&quote=EUR_rhub8VRN55s94qWKDv6jmDy1pUykJzF3wq)


* xApp:
  * Gatehub Trade - [https://gatehub.net/trade-xapp](https://gatehub.net/trade-xapp)
  * DEX Trade - [https://xumm.app/detect/xapp:xumm.dex](https://xumm.app/detect/xapp:xumm.dex)
  * Pathfinding - [https://xumm.app/detect/xapp:xumm.pathfinding](https://xumm.app/detect/xapp:xumm.pathfinding)
