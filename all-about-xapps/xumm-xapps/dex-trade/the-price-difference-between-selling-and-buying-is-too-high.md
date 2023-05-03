# The price difference between selling and buying is too high

### Situation

When trying to purchase or swap tokens, you receive the message, "The price difference between selling and buying is too high".\


<figure><img src="../../../.gitbook/assets/Price difference.png" alt=""><figcaption></figcaption></figure>

### Relevant terminology

**The DEX**&#x20;

XRP Ledger has a native decentralized exchange (DEX) that lets anyone buy or sell any asset that exists on the XRPL. Since anyone can issue assets on the XRPL, the DEX is an incredibly useful and powerful tool. It is basically a global market place where buying and selling takes place at any time. &#x20;

**The Spread**&#x20;

The spread is the difference between the bid and the ask prices of a token on the DEX. For example, if you place an order for 100 tokens for 100 XRP, but the current orders are for 100 tokens for 105 XRP, the spread is 5 XRP. You are bidding 100 XRP, people are asking for 105 XRP. The difference is 5 XRP. &#x20;

**Market Order**&#x20;

A market order is a transaction that tries to buy or sell tokens at the best available price on the DEX. If you are going to place a market order, you should review the charts and the order book depth before placing an order. Make sure that there is a market on both sides of the order book. This means lots of sellers and lots of buyers. If there is only a large number of sell orders, it means that you are trading in an illiquid asset.&#x20;

### How Xumm works

Any market order placed on the DEX tries to buy/sell the tokens **immediately** based on the current order books and token liquidity. We built safety features into Xumm that prevents unexpected results when placing an order so, if the **Spread is more than 4%**, you will receive above message.

Xumm does not allow the instant market swap/trade on a token pair that results in a user receiving significantly less than the current spot price. (Which could happen with illiquid tokens.) If Xumm allowed this to happen, you would lose a significant percentage of your funds if you decided to trade back to your original asset.

