---
description: All about the Account Worth xApp
---

# Account Worth

### **Background**

The Account Worth xApp is designed to display the **total** current value of all of the tokens held in your XRP Ledger account.&#x20;

### **How do I find it**

Simply touch this link:

[**Account Worth**](https://xumm.app/detect/xapp:xumm.accountworth)

or you can find it by pressing the **xApps** button at the bottom of the main screen in Xumm.\




<figure><img src="../../.gitbook/assets/Account Worth -2.png" alt=""><figcaption></figcaption></figure>

### **How does Account Worth calculate the "value" of my tokens?**

For each token in your account, the Account Worth xApp looks at the XRPL DEX and calculates what the liquidation value would be based on the open orders currently on the DEX.  &#x20;

<figure><img src="../../.gitbook/assets/Account Worth - xApp - 2.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Xumm shows the _real_ representation of each asset based on the _current_ DEX liquidity. It shows the amount you can _actually_ trade your tokens for, which is, in case of illiquid pairs, a lot less than the fake price most platforms show.&#x20;
{% endhint %}

### **What about the base reserve and owner reserves? Are they counted in the total value?**

The Account Worth xApp **includes** the base reserve and owner reserves when calculating the value of your XRP.  The reason for this is that while the reserves are marked as "un-spendable" on the XRPL, they are still **in your account** so they are counted when Account Worth calculates the total value of your XRP. &#x20;

### **Why is there a difference been what Account Worth shows and what the DEX Trade xApp shows?**

Account Worth shows the real value of each asset based on the current liquidity on the DEX. The DEX Trade xApp shows the last traded price. (It does not calculate the actual worth of token.)

In other words, [slippage](../../getting-started/some-terms-and-definitions-related-to-xumm-and-the-xrpl.md) and [liquidity](../../getting-started/some-terms-and-definitions-related-to-xumm-and-the-xrpl.md) have been taken into account with Account Worth but not with the DEX Trade xApp.

### **Why is there a difference been what Account Worth shows and what my exchange shows?**

Account Worth shows the real value of each asset based on the current liquidity on the DEX.&#x20;

Many crypto exchanges use a different method of calculating value. Some exchanges have their own liquidity pool which they use to calculate value. Some exchange rely on third parties to calculate value.  Account Worth relies on the XRP Ledger DEX to calculate value.





**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
