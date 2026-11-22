---
description: The fees you pay to deposit, hold, and withdraw XRP with the Flare xApp
---

# Fees in the Flare xApp

### Background

The **Flare XRPFi Yield** xApp lets you earn yield on XRP from your XRP Ledger (XRPL) account. It moves your XRP to the Flare network, converts it to FXRP, and places it in a vault run by Upshift.

Three parties charge fees along the way. Flare runs the bridge between the two networks, Upshift runs the vault, and Xaman provides the app you sign with. Flare and Upshift are not part of Xaman, and each sets its own fees.

You pay every fee in XRP from your XRPL account. You do not need FLR, the Flare network's coin, and you do not need a second wallet.

### How the fees work

The fees fall into three groups, depending on when they apply:

* Fees you pay when you sign a transaction. These come out of your XRPL account as payments.
* Fees taken inside the vault while your funds earn yield. These never appear as payments from your account.
* A fee taken from the XRP that comes back to you when you withdraw.

The table lists each fee as of November 2026, who charges it, and when it applies.

| Fee              | Charged by | When                              | Amount                                                                                                |
| ---------------- | ---------- | --------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Instruction fee  | Flare      | Each deposit                      | 0.95 XRP, plus about 0.02% of the deposit for collateral reservation. Paid with your first signature. |
| Minting fee      | Flare      | Each deposit                      | 0.1% of the deposit, added to the XRP you send                                                        |
| Service fee      | Xaman      | Each deposit                      | 0.5% of the XRP you send to Flare, including the minting fee. Paid as a separate payment.             |
| Management fee   | Upshift    | While your funds are in the vault | 0.75% a year, taken inside the vault                                                                  |
| Performance fee  | Upshift    | While your funds are in the vault | 10% of the yield the vault earns                                                                      |
| Instruction fees | Flare      | Each withdrawal                   | 0.50 XRP to request the withdrawal, and 0.95 XRP to withdraw to the XRP Ledger                        |
| Redemption fee   | Flare      | Each withdrawal                   | 0.2%, taken from the XRP paid back to you                                                             |

Flare and Upshift can change their fees. Before you sign, check the amounts shown in the xApp and on the signing screen.

### Fees when you deposit

A deposit takes two signatures. You start it by tapping **Deposit**, entering an amount, and tapping **Request deposit**.

Your first signature sends an instruction to Flare. It pays Flare's instruction fee, which covers carrying out your deposit on Flare and reserving the collateral for it. None of your deposit is in this transaction, and Xaman charges no fee on it.

When Flare accepts the request, tap **Deposit Now** to sign the second transaction. This sends the XRP you are depositing to Flare, with Flare's minting fee added. Xaman's service fee is charged with the same signature and sent as a separate payment.

Flare then converts your XRP into FXRP, a token on Flare that represents XRP one-to-one. It places the FXRP in the vault and gives you earnXRP, the token that represents your share of the vault. The xApp shows your balance once this is done.

### Reading the signing screen

On the second signing screen, the **Amount** is the XRP sent to Flare, including the minting fee. Xaman's service fee is not part of this amount.

The service fee appears under **Network & Service Fee**, together with the XRP Ledger network fee, labeled **Yield product Service Fee (0.5%)**. Tap the information icon next to it to see the two fees listed separately.

{% hint style="warning" %}
The **Amount** on the signing screen does not include Xaman's service fee. More XRP leaves your account than the **Amount** shows. Add the **Amount** and the **Network & Service Fee** to see the total before you slide to accept.
{% endhint %}

The first signature works the same way. Its **Amount** is Flare's instruction fee, and **Network & Service Fee** shows only the network fee.

### Fees while your funds are in the vault

Upshift charges a management fee and a performance fee while your funds are in the vault. Upshift takes them inside the vault, so they never appear as payments from your account.

Instead, they reduce the value of your earnXRP. The value you see in the xApp already has these fees taken out.

### Fees when you withdraw

A withdrawal also takes two signatures, with a waiting period between them. Xaman does not charge a service fee on withdrawals.

To start, tap **Withdraw**, enter the amount of earnXRP you want to withdraw, and tap **Request withdrawal**. Your signature pays Flare's first instruction fee. The xApp lists your request under **Pending Actions**, with the time it will be ready.

When the request is ready, an **FXRP Withdrawal** card shows **Ready**. Tap **Withdraw to XRPL** to sign the second transaction, which pays Flare's second instruction fee.

Flare then converts your FXRP back to XRP and sends it to your account. The redemption fee is taken from this payment, so you receive slightly less XRP than the FXRP you withdrew.

Withdrawals to the XRP Ledger must be in multiples of 10 FXRP. Any smaller remainder stays on Flare as FXRP, outside the vault, where it does not earn yield.

### Frequently asked questions

**Why do I see several payments for one deposit?**

One deposit creates three payments from your account. The first is Flare's instruction fee. The second is your XRP sent to Flare with the minting fee, and the third is Xaman's service fee.

**Why did more XRP leave my account than the signing screen showed?**

The **Amount** on the signing screen does not include Xaman's service fee or the network fees. To see the total, add the **Amount** and the **Network & Service Fee**.

**Why do fees take a larger share of a small deposit?**

Flare's instruction fees are fixed amounts, charged on every deposit and withdrawal. On a small amount, a fixed fee is a larger share of the total.

**Why did my withdrawal come from an address I do not recognize?**

Flare assigns an FXRP agent to pay out each withdrawal. That agent can be different from the one that received your deposit.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Understanding Xaman Service Fees](../../getting-started-with-xaman/understanding-the-xaman-service-fee.md)
* [How to Deposit XRP using the Flare xApp](depositing-xrp-with-the-flare-xapp.md)
* [Flare Smart Accounts](https://flare.network/products/flare-smart-accounts)





***

### **Important Disclaimer**

**Flare Smart Accounts, FAssets, and any associated vault products are developed, operated, and managed by Flare and their respective third-party partners. They are not developed, operated, or controlled by XRPL Labs or Xaman.** Xaman serves solely as a signing interface for XRPL transactions.

While the Flare Smart Accounts architecture is designed to maintain user custody through XRPL key governance, interacting with DeFi protocols and vault strategies still carries inherent risks including but not limited to: smart contract vulnerabilities, cross-chain execution failures, counterparty exposure at the protocol level, liquidity constraints, and market volatility. Self-custody of keys does not eliminate protocol-level risk. Estimated returns are not guarantees of future results.

**Do your own research.** Before interacting with any third-party product through an xApp, understand how it works, what the risks are, where your assets go, and what you are agreeing to. Xaman does not endorse, guarantee, or take responsibility for the performance, security, or outcomes of any third-party xApp, protocol, or platform.
