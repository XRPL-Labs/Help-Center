# Account Worth

### **Background**

With the release of Xumm v2.3, the _**Account Worth**_ xApp takes a more prominent role in Xumm.

In previous versions, you could simply touch your XRP balance and it would immediately display the fiat equivalent.

&#x20;

![mceclip3.png](https://drtc9zr.dlvr.cloud/hc/article\_attachments/5881361968658/mceclip3.png)

This is not the case now.

In order to see the value of your XRP and the value of **all** the tokens in your account, you need to use the  _**Account Worth**_ xApp.

&#x20;

### **How do I find it?**

&#x20;To find it, just launch Xumm and press the "**x√**" button at the bottom of the screen. ![mceclip0.png](https://drtc9zr.dlvr.cloud/hc/article\_attachments/5881817535762/mceclip0.png) You should see _**Account Worth**_ listed in the second row. ![mceclip1.png](https://drtc9zr.dlvr.cloud/hc/article\_attachments/5882016149138/mceclip1.png)

&#x20;

### **How does Account Worth calculate the "value" of my tokens?**

&#x20;For each token in your account, the Account Worth xApp looks at the XRPL DEX and calculates what the liquidation value would be based on the open orders currently on the DEX.  &#x20;

![mceclip0.png](https://drtc9zr.dlvr.cloud/hc/article\_attachments/6006931870866/mceclip0.png)

&#x20; Xumm shows the _real_ representation of each asset based on the _current_ DEX liquidity. It shows the amount you can _actually_ trade your tokens for, which is, in case of illiquid pairs, a lot less than the fake price most platforms show.&#x20;

### **What about the base reserve and owner reserves? Are they counted in the total value?**

&#x20;The base reserve on the XRPL is currently set at 10XRP. This is a requirement of owning an account on the XRP Ledger and needs to be continually met as long as you have an XRPL account.  The Owner reserve on the XRPL is currently set at 2 XRP. For every object in your account, (Trust Lines, offers on the DEX, escrows, etc.,) a 2 XRP owner reserve is required. For people who have set up many Trust Lines, this can add up to a sizable amount. The Account Worth xApp **ignores** the base reserve and owner reserves when calculating the value of your XRP.  The reason for this is that while the reserves are marked as "un-spendable" on the XRPL, they are still **in your account** so they are counted when Account Worth calculates the total value of your XRP. &#x20;

### **Where can I learn more about this?**

&#x20;The following article explains more on how "value" is calculated in Xumm.

* [How does Xumm calculate the value of an asset?](https://support.xumm.app/hc/en-us/articles/4416895527314)

&#x20;

**Additional reading**

If you are interested in learning more about the new features in Xumm v2.3, check out this article:

* [Xumm v2.3.0 - Release Notes](https://support.xumm.app/hc/en-us/articles/5569334061330)

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the **Xumm Support xApp** in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.



<figure><img src="../../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
