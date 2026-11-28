---
description: How to swap one token for another, and what to check before you sign
---

# Xaman Swap

Xaman Swap lets you trade one token for another in a single step, such as XRP for RLUSD. It looks for the best rate across the XRP Ledger (XRPL), shows you what you can expect to receive, and sends the result straight back to your own account. You see every detail before you sign, and nothing happens until you slide to accept.

This article walks you through a swap screen by screen, and explains the numbers along the way: the rate, slippage, and the minimum you will receive. Those numbers are what protect you when prices move, so they are worth a minute of your attention.

### Before you get started

* An XRP Ledger account with **Full access** in Xaman.
* The token[^1] or XRP you want to sell, in that account.
* A [trust line](#user-content-fn-2)[^2] for the token you want to receive. If you do not have one yet, Xaman Swap offers to create it for you.

### Open Xaman Swap

Tap **xApps** in the bottom navigation bar, then tap **Xaman Swap** under **Our suggestions**. You can also tap the Xaman button in the middle of the bottom navigation bar, where Xaman Swap is under **Our suggestions** too.

### Swap a token

1. Under **Selling**, tap the token, and select the one you want to sell. You can search for it by name.
2. Enter the amount to sell, or tap **MAX** to sell your whole balance.
3. Under **Receiving**, tap the token, and select the one you want to receive.
4. If Xaman Swap says you need a trust line, tap **Create Trustline**, and sign it.
5. Check the amount under **Receiving**, and the **Rate**.
6. Tap **Swap**. The **Review transaction** screen opens.
7. Check **Amount to receive**, **Send Maximum amount**, and **Deliver Minimum amount**.
8. Slide to accept, and confirm with your passcode or biometrics.
9. When **Swap Successful!** appears, check the amount under **You received**.

From there, **Transaction Details** opens the swap in Xaman, **View on Explorer** opens it on a public XRP Ledger explorer, and **New Swap** starts another one. Your swap also shows in **Events** as "Swapped tokens".

### How the rate and the quote work

Prices on the XRP Ledger move all the time, so the rate you see is a quote, not a promise. Under the **Rate**, a countdown shows when the quote updates next. When it reaches zero, Xaman Swap checks the current rate again, and updates the amounts if the rate has changed.

Tap **Swap Details** to see how your swap is worked out:

* **Exchange Rate:** how much of one token you get for the other at the current quote.
* **Price impact:** how much your own swap moves the price. Small swaps barely move it, while a large one can push the rate against you.
* **Smart Slippage:** how far the rate is allowed to move before you sign and the swap completes.
* **Minimum receive:** the least you will receive. If the rate moves further than your slippage allows, the swap does not go through, so you never get less than this.
* **Estimated Outcome:** what you will most likely receive at the current rate.

### Choose your slippage

Slippage is the room you give the rate to move between your quote and the moment your swap completes. A little room helps your swap go through when prices are busy, and too much room lets it complete at a rate you would not have chosen.

To change it, tap the settings icon at the top of Xaman Swap. Under **Slippage**, **Smart** lets Xaman Swap set it for you, based on how much is available to trade. **Manual** lets you pick **0.5%**, **1%**, **2.5%**, **5%**, **10%**, or **Custom**. For most swaps, **Smart** is the best choice.

{% hint style="warning" %}
A high slippage setting lets a swap complete at a much worse rate than the quote. You could receive far less than the estimate. Keep Smart slippage unless your swaps keep failing, and check Minimum receive before you sign.
{% endhint %}

### What the Review transaction screen shows

The **Review transaction** screen can look surprising at first: it shows a **Payment** from your account to your own account. That is how a swap works on the XRP Ledger. You pay yourself, and the payment converts from one token to the other on the way.

* **Amount to receive:** what the swap aims to deliver.
* **Send Maximum amount:** the most you will spend, which is the amount you entered.
* **Deliver Minimum amount:** the least you will receive, from your slippage setting.
* **Issuer fee:** a fee some token issuers[^3] charge whenever their token moves. It is set by the issuer, not by Xaman.
* **Flags:** **tfPartialPayment** lets the swap deliver anything between the minimum and the full amount, depending on the rate when it completes.
* **Network & Service Fee:** the fees for this transaction. \[Uncertain: where the 0.8% service fee appears for a swap]

### What a swap costs

Xaman charges a 0.8% service fee on token swaps, and only when the swap actually moves value. A swap that does nothing costs no service fee. Every swap also pays the small XRP Ledger network fee, and some tokens carry an issuer fee too. [Understanding Xaman Service Fees](https://help.xaman.app/app/getting-started-with-xaman/what-is-xaman/understanding-the-xaman-service-fee) explains the fees in full.

### Before you swap into a token

Any issuer can create a token and give it any name, so the name alone does not tell you who stands behind it. A token's issuer may also have powers XRP does not have: depending on its settings, an issuer can freeze its token or claw it back. Before you swap into a token you do not know, check who issued it. [Token vetting and the token warning](https://help.xaman.app/app/tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning) \[VERIFY LINK] explains how.

If a swap does not work the way you expect, **Get help** at the bottom of Xaman Swap opens the Xaman Support xApp.

<p align="center"><a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Get help from Xaman Support</a></p>

### Frequently asked questions

**Why does the rate change while I am looking at it?**

The rate comes from live XRP Ledger markets, which move all the time. Xaman Swap rechecks it each time the countdown reaches zero, and updates the amounts if the rate has changed. What you sign is always the latest quote.

**Why does the transaction say Payment to my own account?**

That is how a swap works on the XRP Ledger. Your account pays itself, and the payment converts from one token to the other on the way. Nothing leaves your account except the amount you chose to sell.

**Why did I receive a little less than the estimate?**

The rate moved slightly between your quote and the moment your swap completed. You will never receive less than the **Minimum receive** amount shown in **Swap Details**.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Understanding Xaman Service Fees](https://help.xaman.app/app/getting-started-with-xaman/what-is-xaman/understanding-the-xaman-service-fee)
* [Trust Lines on the XRP Ledger](https://help.xaman.app/app/tokens-trust-lines-and-nfts/trust-lines-on-the-xrp-ledger) \[VERIFY LINK]
* [Token vetting and the token warning](https://help.xaman.app/app/tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning) \[VERIFY LINK]
* [Xaman xApps](https://help.xaman.app/app/xapps/xaman-xapps)
* [Xaman Support](https://help.xaman.app/app/xapps/xaman-xapps/xaman-support)

[^1]: A digital asset created on the XRP Ledger by an issuer. Unlike XRP, a token's value depends on whoever issued it.

[^2]: Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.

[^3]: The account that creates a token. Anyone can be an issuer, and any issuer can give a token any name.
