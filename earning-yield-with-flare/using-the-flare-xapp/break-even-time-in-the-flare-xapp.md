---
description: >-
  How long the yield on a deposit takes to cover the fees of depositing and
  withdrawing
---

# Break-even time in the Flare xApp

### Background

Depositing XRP with the **Flare XRPFi Yield** xApp and withdrawing it later both cost fees. Your deposit earns yield in the vault, and over time that yield can cover those fees. The break-even time is how long that takes.

This article shows how to estimate your break-even time on the XRP Ledger (XRPL). The rates in it are examples, not predictions. The yield the vault earns changes over time and is not guaranteed.

### The fees to cover

A full round trip, one deposit and one withdrawal, has two kinds of fees. Some are fixed amounts, and some are a percentage of your deposit.

As of November 2026, these are:

* On the deposit: Flare's 0.95 XRP instruction fee, plus about 0.62% of the deposit (Flare's collateral reservation and minting fees, and Xaman's service fee).
* On the withdrawal: Flare's two instruction fees of 0.50 XRP and 0.95 XRP, plus Flare's 0.2% redemption fee.

The table shows the total for a round trip at different deposit sizes. Network fees are left out, since they are too small to change the results.

| Deposit    | Fees on the deposit | Fees on the withdrawal | Total fees      |
| ---------- | ------------------- | ---------------------- | --------------- |
| 10 XRP     | about 1.01 XRP      | about 1.47 XRP         | about 2.48 XRP  |
| 100 XRP    | about 1.57 XRP      | about 1.65 XRP         | about 3.22 XRP  |
| 500 XRP    | about 4.05 XRP      | about 2.45 XRP         | about 6.50 XRP  |
| 1,000 XRP  | about 7.16 XRP      | about 3.45 XRP         | about 10.61 XRP |
| 5,000 XRP  | about 31.98 XRP     | about 11.45 XRP        | about 43.43 XRP |
| 10,000 XRP | about 63.00 XRP     | about 21.45 XRP        | about 84.45 XRP |

The fixed fees are the same at every deposit size. That is why they take up a larger share of a small deposit. On a 10 XRP deposit, a round trip costs about a quarter of the deposit.

The fixed fees are the same at every deposit size. That is why they take up a larger share of a small deposit.

### Estimate your break-even time

Upshift takes its management and performance fees inside the vault. The rate at which your earnXRP value grows already has them taken out, so use that rate in the calculation.

To estimate your break-even time:

1. Find the total fees for your deposit size in the table.
2. Multiply your deposit by the yearly growth rate, then divide by 12. This is your yield per month.
3. Divide the total fees by your yield per month. The result is your break-even time in months.

For example, take a 1,000 XRP deposit at a yearly growth rate of 4%. The yield is 40 XRP a year, or about 3.33 XRP a month. The total fees of about 10.61 XRP take about 3.2 months to cover.

### Example break-even times

The table applies the same calculation to each deposit size at three example growth rates. The times are approximate.

| Deposit    | At 2% a year                  | At 4% a year                | At 6% a year                |
| ---------- | ----------------------------- | --------------------------- | --------------------------- |
| 10 XRP     | about 149 months (12.4 years) | about 74 months (6.2 years) | about 50 months (4.1 years) |
| 100 XRP    | about 19.3 months             | about 9.7 months            | about 6.4 months            |
| 500 XRP    | about 7.8 months              | about 3.9 months            | about 2.6 months            |
| 1,000 XRP  | about 6.4 months              | about 3.2 months            | about 2.1 months            |
| 5,000 XRP  | about 5.2 months              | about 2.6 months            | about 1.7 months            |
| 10,000 XRP | about 5.1 months              | about 2.5 months            | about 1.7 months            |

If you withdraw before your break-even time, the fees cost more than the yield you earned. You receive less XRP than you deposited.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Fees in the Flare xApp](fees-in-the-flare-xapp.md)
* [Depositing XRP with the Flare xApp](depositing-xrp-with-the-flare-xapp.md)
* [The Flare XRPFi Yield xApp](the-flare-xrpfi-yield-xapp.md)

***

### **Important Disclaimer**

**Flare Smart Accounts, FAssets, and any associated vault products are developed, operated, and managed by Flare and their respective third-party partners. They are not developed, operated, or controlled by XRPL Labs or Xaman.** Xaman serves solely as a signing interface for XRPL transactions.

While the Flare Smart Accounts architecture is designed to maintain user custody through XRPL key governance, interacting with DeFi protocols and vault strategies still carries inherent risks including but not limited to: smart contract vulnerabilities, cross-chain execution failures, counterparty exposure at the protocol level, liquidity constraints, and market volatility. Self-custody of keys does not eliminate protocol-level risk. Estimated returns are not guarantees of future results.

**Do your own research.** Before interacting with any third-party product through an xApp, understand how it works, what the risks are, where your assets go, and what you are agreeing to. Xaman does not endorse, guarantee, or take responsibility for the performance, security, or outcomes of any third-party xApp, protocol, or platform.
