---
description: How to deposit XRP into the Flare yield vault, and what each signature does
---

# Depositing XRP with the Flare xApp

### Background

The **Flare XRPFi Yield** xApp moves XRP from your XRP Ledger (XRPL) account to the Flare network, where it earns yield in a vault run by Upshift. This article covers the XRP Ledger.

A deposit takes two signatures in Xaman. The first sends an instruction to Flare to prepare your deposit. The second sends your XRP. Flare then converts your XRP into FXRP, a token that represents XRP one-to-one, and places it in the vault for you.

### Before you get started

* A **Full access** account in Xaman.
* Enough XRP for your deposit, the fees, and your account reserve. See [_Fees in the Flare xApp_](fees-in-the-flare-xapp.md) for the current fees.

### Request a deposit

1. Tap **xApps** in the bottom navigation bar.
2. Tap **Flare XRPFi Yield**.
3. Tap **Deposit**.
4.  Enter the amount of XRP you want to deposit. The amount must be a multiple of 10 XRP.\
    <br>

    <figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt="" width="266"><figcaption></figcaption></figure>
5. Tap **Request deposit**. The signing screen opens.
6. Check the **Amount**, then slide to accept.

This signature pays Flare's instruction fee. None of the XRP you are depositing leaves your account yet, and Xaman charges no fee on it.

### Send your XRP

1.  When Flare accepts your request, tap **Deposit Now**. The signing screen opens.<br>

    <figure><img src="../../.gitbook/assets/image (98).png" alt=""><figcaption></figcaption></figure>
2. Check the **Amount** and the **Network & Service Fee**.
3. Slide to accept.

{% hint style="warning" %}
The **Amount** on this signing screen does not include Xaman's service fee. More XRP leaves your account than the **Amount** shows. Add the **Amount** and the **Network & Service Fee** to see the total.
{% endhint %}

This signature sends your XRP to Flare, with Flare's minting fee included in the **Amount**. Xaman's service fee is charged with the same signature, as a separate payment.

The xApp shows **Updating balance** while Flare creates your FXRP and places it in the vault. No further signatures are needed. When it finishes, your vault balance appears on the xApp's main screen in earnXRP, the token that represents your share of the vault.

### What happens next

Your funds earn yield in the vault, and the value of your earnXRP grows over time. The xApp shows your earnXRP balance and its current value in FXRP.

To withdraw, open the xApp and tap **Withdraw**. A withdrawal also takes two signatures, with a waiting period between them. The xApp shows when your withdrawal will be ready.

### Frequently asked questions

**Why can't I deposit XRP?**

Check that the amount is a multiple of 10 XRP, and that you have enough XRP left for the fees and your account reserve. Your account must also have **Full access** in Xaman. If none of these apply, contact support through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md) and include a screenshot of the error.

**Why did I have to sign twice?**

The first signature asks Flare to prepare your deposit and pays Flare's instruction fee. The second signature sends your XRP. Flare only accepts your XRP after it has prepared the deposit.

**Why did more XRP leave my account than the signing screen showed?**

The **Amount** on the second signing screen does not include Xaman's service fee or the network fees. Add the **Amount** and the **Network & Service Fee** to see the total.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [The Flare XRPFi Yield xApp](the-flare-xrpfi-yield-xapp.md)
* [Fees in the Flare xApp](fees-in-the-flare-xapp.md)
* [Understanding Xaman Service Fees](../understanding-the-xaman-service-fee.md)<br>

