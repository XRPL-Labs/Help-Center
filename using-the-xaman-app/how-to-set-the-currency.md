---
description: How to see what your XRP is worth, in the currency you choose
---

# Setting the currency in Xaman

### Background

Xaman can show you what your XRP[^1] is worth in a currency you know, such as US dollars, euros, or yen. You choose that currency once, and Xaman uses it for every value it shows you. This article explains where those values appear, how to change the currency, and where the numbers come from.

The currency is a setting in the Xaman app itself, not in your account. It applies on both the [XRP Ledger (XRPL)](#user-content-fn-2)[^2] and Xahau[^3], with one difference. On Xahau, the **Account Worth** row shows a total for your account, but no value appears under your XAH balance. Changing the currency only changes how values are displayed on your phone. Nothing about your account or your balance changes on either network.

### See what your XRP is worth

The value of your XRP appears on the **Home** screen, right under your XRP balance. Above it, the **Account Worth** row shows a total for everything in the account. Each one has its own setting, so you can show both, one, or neither. If a value is missing from your Home screen, its setting is probably off.

1. Tap **Settings** > **General**.
2. Under **Home Screen**, turn on **Show asset prices on home screen** to see the value of your XRP.
3. Turn on **"Account Worth" on home screen** to see the total for your account.
4. Return to the **Home** screen.

Your Home screen now shows the values you turned on. You can turn either setting off again at any time, for example before you share a screenshot with someone. Your balance stays the same either way. Only the values are hidden.

### Change the currency

Xaman supports many currencies, from the US dollar and the euro to currencies used in far fewer countries. Pick the one you think in, so the numbers mean something to you at a glance. The **Currency** option shows the one you use now, such as USD, and you can change it as often as you like.

1. Tap **Settings** > **General**.
2. Under **Language & Currency**, tap **Currency**.
3. Select the currency you want to use.
4. Return to the **Home** screen.

The value under your XRP balance now shows in the currency you selected.

In the same section, **Use system currency format** writes values the way your phone's region does, such as 1.234,56 in much of Europe instead of 1,234.56. If your phone is set to the United States or Canada (English), the two formats look the same. Turn it off if you prefer Xaman's own format.

### How Xaman works out the value

The value Xaman shows is an estimate of what your XRP is worth right now, not a price anyone has promised you. For XRP, XRPL Labs, the company behind Xaman, checks the XRP price at several exchanges every minute. XRPL Labs sets aside any price that is far from the rest and publishes the middle one. Prices change all day, and every exchange quotes a slightly different price, so the value in Xaman can differ a little from what your exchange shows.

The value covers all of your XRP, including your reserve[^4]. That reserved XRP is still yours and still in your account, but you cannot send or sell it while your account is active. The balance on the Home screen shows only the XRP you can spend, with the reserve listed under it as **Reserved**. The value counts the reserved XRP too, which is why it can look a little high next to the balance.

A token[^5] works differently, since it has no single market price the way XRP does. Its value depends on what other people are offering for it right now on the DEX[^6]. The Account Worth xApp estimates what you would receive if you sold each token there, based on the offers open at that moment. A token with few buyers can show a low value, or none at all. Depending on its settings, a token's issuer may also be able to freeze the token or claw it back, which no one can do with XRP.

### Frequently asked questions

**Does changing the currency change my balance?**

No. The currency only changes how Xaman displays values on your phone. Your XRP stays XRP, nothing is sent, and no transaction or fee is involved.

**Why is the value in Xaman different from the value on my exchange?**

Every exchange sets its own prices, based on its own buyers and sellers. Xaman shows the middle price across several exchanges, so the two numbers are rarely exactly the same. A small difference is normal, and it does not mean anything is wrong with your account.

**Can I see what all my tokens are worth?**

Yes. Turn on **"Account Worth" on home screen**, and the **Account Worth** row on your Home screen shows a total for your XRP and every token in your account. For a breakdown, one token at a time, open the Account Worth xApp from the **xApps** tab. See [Account Worth](https://help.xaman.app/app/xapps/xaman-xapps/account-worth) for how it calculates each value.

**Why is there no live price chart in Xaman?**

Xaman is built for holding, sending, and using XRP and tokens on the XRP Ledger, not for trading. The value on the Home screen gives you a quick sense of what your account is worth. If you want live charts and price alerts, exchanges and trading apps are made for that.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Account Worth](../xapps/xaman-xapps/account-worth.md)
* [Understanding the Settings Options](understanding-the-settings-options/)
* [Reserves on the XRP Ledger](../xrp-ledger-basics/xrp-ledger-concepts/about-reserves.md)

[^1]: The native coin of the XRP Ledger. Every account needs some to exist, and every transaction pays a tiny fee in XRP.

[^2]: A public network, run by independent computers around the world, that records who owns what. XRP is its native coin.

[^3]: A separate network, related to the XRP Ledger, with its own accounts and its own coin, XAH.

[^4]: XRP that every active XRP Ledger account must keep and cannot spend. The network sets the amount, and it can change.

[^5]: A digital asset created on the XRP Ledger by an issuer. Unlike XRP, a token's value depends on whoever issued it.

[^6]: The XRP Ledger's built-in marketplace, where you can trade XRP and tokens straight from your account.
