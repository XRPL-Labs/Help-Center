---
description: >-
  Answers to common questions about depositing, earning, and withdrawing with
  the Flare xApp
---

# Frequently asked questions about the Flare xApp

The **Flare XRPFi Yield** xApp lets you earn yield on XRP from your XRP Ledger (XRPL) account. This article answers common questions about how it works. For the full picture, see [_The Flare XRPFi Yield xApp_](the-flare-xrpfi-yield-xapp.md).

### About the xApp

**Which companies are involved?**

Three parties work together in the xApp:

* Xaman provides the app you sign with. Xaman never holds your funds.
* Flare runs FAssets, the bridge that turns XRP into FXRP, and Flare Smart Accounts.
* Upshift runs the earnXRP vault and the strategies it uses to earn yield.

Flare and Upshift are not part of Xaman. Each sets its own fees and terms.

**How do they work together?**

You sign each step in Xaman with your XRPL account. Your signatures send instructions to your Flare Smart Account, which carries them out on the Flare network. Flare turns your XRP into FXRP, and Upshift's vault holds the FXRP while it earns yield.

**Do I need a second wallet or FLR?**

No. Your Flare Smart Account is controlled only by instructions signed with your XRPL account. You pay every fee in XRP, so you do not need FLR, the Flare network's coin.

**Where does the yield come from?**

Upshift manages the vault and decides how it earns yield. The yield depends on the strategies Upshift uses and on market conditions. It changes over time and is not guaranteed.

### Deposits

**Why do I have to sign twice to deposit?**

The first signature asks Flare to prepare your deposit and pays Flare's instruction fee. The second signature sends your XRP to Flare. See _Depositing XRP with the Flare xApp_.

**Why did more XRP leave my account than the signing screen showed?**

The **Amount** on the second signing screen does not include Xaman's service fee or the network fees. Add the **Amount** and the **Network & Service Fee** to see the total.

**Can I deposit any amount?**

No. Deposits must be in multiples of 10 XRP. You also need enough XRP left for the fees and your account reserve.

**Where did my XRP go?**

Your XRP went to an FXRP agent on the XRP Ledger. The agent holds it while the matching FXRP exists on the Flare network. Your FXRP is in the vault, and the xApp shows your share as earnXRP.

### While your funds are in the vault

**Why is my earnXRP balance lower than the XRP I deposited?**

earnXRP is your share of the vault, not an amount of XRP. Each earnXRP is worth more than 1 FXRP. The xApp shows both your earnXRP balance and its value in FXRP.

**Why did the value of my balance go down?**

Upshift takes its management and performance fees inside the vault. If the vault earns less than these fees in a period, the value of your earnXRP can go down. The number of earnXRP you hold stays the same.

### Withdrawals

**What do I need before I withdraw?**

You need two things before you start a withdrawal:

* Enough XRP in your account to pay the withdrawal fees. Flare charges 0.50 XRP to request the withdrawal and 0.95 XRP to withdraw to the XRP Ledger. You pay both from the XRP in your account, on top of your account reserve.
* An amount of earnXRP worth at least 10 FXRP. Flare only sends FXRP back to the XRP Ledger in multiples of 10 FXRP.

If you deposit almost all of your XRP, you may not have enough left to pay the withdrawal fees. Keep about 1.5 XRP in your account for when you withdraw.

**How do I make sure I can withdraw everything?**

When you request a withdrawal, the xApp shows how much FXRP you will receive. Request the withdrawal only when this amount is at least 10 FXRP, or a multiple of 10 FXRP.

Right after a deposit, your vault balance can be worth slightly less than what you deposited. For example, a 10 XRP deposit can show as 9.999 FXRP. Wait a day or two for the vault to earn the difference before you request the withdrawal.

If you withdraw too early, the amount under 10 FXRP stays on Flare as FXRP, outside the vault, where it does not earn yield.

**How long does a withdrawal take?**

A withdrawal takes two signatures, with a waiting period between them. The xApp lists your request under **Pending Actions**, with the time it will be ready. After your second signature, the XRP usually arrives within a few minutes.



### Risks

**What are the risks?**

The xApp connects your account to products run by Flare and Upshift. Using them carries risks that self-custody does not remove:

* A fault in the smart contracts that run FAssets, Flare Smart Accounts, or the vault.
* A failure in the bridge between the XRP Ledger and the Flare network.
* A failure of an FXRP agent, or of the collateral system that backs FXRP.
* Losses in the vault's strategies, or periods where fees exceed the yield.

Only you can authorize a deposit or a withdrawal from your account. Xaman cannot reverse a transaction or recover funds held by Flare or Upshift.

**I have a problem that is not answered here. Who can help?**

Contact support through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md). Include a screenshot of what you see.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [The Flare XRPFi Yield xApp](the-flare-xrpfi-yield-xapp.md)
* [Depositing XRP with the Flare xApp](depositing-xrp-with-the-flare-xapp.md)
* [Fees in the Flare xApp](fees-in-the-flare-xapp.md)
* [Break-even time in the Flare xApp](break-even-time-in-the-flare-xapp.md)
