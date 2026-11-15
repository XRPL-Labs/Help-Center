---
description: The fees you pay to deposit, hold, and withdraw XRP with the Flare xApp
---

# Fees in the Flare xApp

## Background

The **Flare XRPFi Yield** xApp moves XRP from your XRP Ledger (XRPL) account to the Flare network, where it earns yield in a vault.&#x20;

Three parties charge fees along the way: Xaman, Flare, and Upshift. Flare runs the bridge between the two networks, and Upshift runs the vault. Neither company is part of Xaman, and each sets its own fees.

You pay every fee in XRP from your account. You do not need FLR, the Flare network's coin.&#x20;

## Fees by stage

Each fee, who charges it, and when it applies:

| Fee              | Charged by | When                              | How it is charged                                                                                 |
| ---------------- | ---------- | --------------------------------- | ------------------------------------------------------------------------------------------------- |
| Service fee      | Xaman      | Each deposit                      | A percentage of the XRP you send to Flare, including the minting fee. Paid as a separate payment. |
| Instruction fee  | Flare      | Each deposit                      | A fixed fee, plus a small percentage for collateral reservation.                                  |
| Minting fee      | Flare      | Each deposit                      | A percentage of the XRP converted, added to the XRP you send.                                     |
| Management fee   | Upshift    | While your funds are in the vault | A yearly percentage, taken inside the vault.                                                      |
| Performance fee  | Upshift    | While your funds are in the vault | A share of the yield the vault earns.                                                             |
| Instruction fees | Flare      | Each withdrawal                   | A fixed fee for each of the two withdrawal steps.                                                 |
| Redemption fee   | Flare      | Each withdrawal                   | A percentage, taken from the XRP paid back to you.                                                |

## Fees when you deposit

A deposit takes two signatures, and each signature creates payments from your account.&#x20;

The fees fall into the two signatures like this:

* Your first signature sends an instruction to Flare and pays the instruction fee. The fee covers the operator that carries out your instruction on Flare and Flare's collateral reservation fee.
* Your second signature sends your XRP to Flare with the minting fee added. Xaman's service fee follows as a separate payment.

Flare then converts your XRP into FXRP, a token on Flare that represents XRP one-to-one, and places it in the vault.

## Fees while your funds are in the vault

Upshift's management and performance fees do not appear as payments from your account. Upshift takes them inside the vault, so they reduce the value of your earnXRP. (The token that represents your share of the vault.)

## Fees when you withdraw

A withdrawal has two steps, and Flare charges an instruction fee for each step. Flare's redemption fee is taken from the XRP paid back to you. Xaman does not charge a service fee on withdrawals.



## Frequently asked questions

**Why do I see several payments for one deposit?**

One deposit creates three payments from your account: the instruction fee, the XRP sent to Flare with the minting fee, and Xaman's service fee. \[Verified]

**Why did my withdrawal come from an address I do not recognize?**

Flare assigns an FXRP agent to pay out each withdrawal. That agent can be different from the one that received your deposit.

### See also

* [Understanding Xaman Service Fees](../understanding-the-xaman-service-fee.md)
* [How to Deposit XRP using the Flare xApp](how-to-deposit-xrp-using-the-flare-xapp.md)
* [Flare Smart Accounts](https://flare.network/products/flare-smart-accounts)





***

### **Important Disclaimer**

### **Important Disclaimer**

**Flare Smart Accounts, FAssets, and any associated vault products are developed, operated, and managed by Flare and their respective third-party partners. They are not developed, operated, or controlled by XRPL Labs or Xaman.** Xaman serves solely as a signing interface for XRPL transactions.

While the Flare Smart Accounts architecture is designed to maintain user custody through XRPL key governance, interacting with DeFi protocols and vault strategies still carries inherent risks including but not limited to: smart contract vulnerabilities, cross-chain execution failures, counterparty exposure at the protocol level, liquidity constraints, and market volatility. Self-custody of keys does not eliminate protocol-level risk. Estimated returns are not guarantees of future results.

**Do your own research.** Before interacting with any third-party product through an xApp, understand how it works, what the risks are, where your assets go, and what you are agreeing to. Xaman does not endorse, guarantee, or take responsibility for the performance, security, or outcomes of any third-party xApp, protocol, or platform.
