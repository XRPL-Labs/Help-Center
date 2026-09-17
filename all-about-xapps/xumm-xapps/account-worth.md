---
description: All about the Account Worth xApp
---

# Account Worth

### **Background**

The Account Worth xApp is designed to display the **total** current value of all of the tokens held in your XRP Ledger account.

### **How do I find it**

Simply touch this link:

[**Account Worth**](https://xumm.app/detect/xapp:xumm.accountworth)

or you can find it by pressing the **xApps** button at the bottom of the main screen in Xaman (formerly Xumm).<br>

<figure><img src="../../.gitbook/assets/Account Worth -2.png" alt=""><figcaption></figcaption></figure>

### **How does Account Worth calculate the "value" of my tokens?**

For each token in your account, the Account Worth xApp looks at the XRPL DEX and calculates what the possible liquidation value would be based on the open orders and the current liquidity.

<figure><img src="../../.gitbook/assets/Account Worth - xApp - 2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note: The value displayed is **not** the actual value of the tokens. It is the approximate value you would get if you were to try to sell them on the XRP Ledger DEX.
{% endhint %}

### **What about the base reserve and owner reserves? Are they counted in the total value?**

The Account Worth xApp **includes** the base reserve and owner reserves when calculating the value of your XRP. The reason for this is that while the reserves are marked as "un-spendable" on the XRPL, they are still **in your account** so they are counted when Account Worth calculates the total value of your XRP.

### **Why is there a difference between what Account Worth shows and what the DEX Trade xApp shows?**

Account Worth shows the value of each asset based on the current liquidity on the DEX. The DEX Trade xApp shows the last traded price. (It does not calculate the actual worth of token.)

In other words, [slippage](../../all-about-scams/some-terms-and-definitions-related-to-xumm-and-the-xrpl.md) and [liquidity](../../all-about-scams/some-terms-and-definitions-related-to-xumm-and-the-xrpl.md) have been taken into account with Account Worth but not with the DEX Trade xApp.

### **Why is there a difference been what Account Worth shows and what my exchange shows?**

Account Worth shows the approximate value of each asset based on the current liquidity on the DEX.

Many crypto exchanges use a different method of calculating value. Some exchanges have their own liquidity pool which they use to calculate value. Some exchange rely on third parties to calculate value. Account Worth relies on the XRP Ledger DEX to calculate value.
