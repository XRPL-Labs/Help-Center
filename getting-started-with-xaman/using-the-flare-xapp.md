---
description: Understanding and using the Flare XRPFi Yield xApp
---

# Using the Flare xApp

### Introduction

Historically, XRP has been a "passive" asset for investors. You could hold XRP in your account or spend it, but you couldn’t easily earn a yield on it. Most investors just used a "buy and hold" strategy, waiting for the value of XRP to increase before selling for a profit. While that strategy has worked for many, new options are emerging that let you earn yield on your XRP while you wait for the price to rise.

The **Flare XRPFi Yield xApp** allows you to put your XRP to work on the Flare Network to earn rewards through a straightforward, two-step process right inside Xaman.

### What does the Flare XRPFi Yield xApp actually do?

The xApp acts as a bridge and a portal to the Flare network. Here is the breakdown of what happens when you use it:

**Step 1: Bridging your XRP**&#x20;

The xApp allows you to select an amount of XRP to send to a Flare-secured XRP Ledger account ([`rGWGTbxqmpLJ3TYGjoCFDqY9mPQ4T1GTGb`](https://xrplwin.com/account/rGWGTbxqmpLJ3TYGjoCFDqY9mPQ4T1GTGb)). This "locks" your native XRP so it can be used in the next phase.

**Step 2: Minting on Flare**

Once the XRP is received, a smart contract on the Flare network automatically maps your wallet to a Flare Smart Account and mints FXRP —a 1:1 representation of your XRP— on your behalf.

**Step 3: Moving into the Vault**

The system then moves your newly minted FXRP into the earnXRP Vault (managed by Upshift infrastructure) on the Flare network. This is where your assets are officially "put to work."

**Step 4: Yield Generation**&#x20;

Upshift manages the vault's strategies, deploying the FXRP into various decentralized lending and liquidity protocols. The goal is to generate yield, which is then automatically compounded back into your vault balance.

For more technical details on the underlying infrastructure, you can visit: [flare.network/products/flare-smart-accounts](https://flare.network/products/flare-smart-accounts)

### How does the withdraw process work?

When you want to stop earning yield, you first request a withdrawal from the earnXRP Vault.

* What happens: Your "receipt tokens" (earnXRP) are burned, and your assets are pulled out of the various DeFi protocols.
* Note on Timing: Because the vault has to unwind positions from lending and liquidity markets, there is typically a 72-hour processing period before your FXRP is released back to your Flare Smart Account.

Once your FXRP is sitting in your Flare Smart Account, the final step is to "redeem" it.

* What happens: The xApp triggers the FAsset system to burn the FXRP on the Flare Network. This simultaneously signals the Flare-controlled account on the XRPL (`rGWGTbxqmpLJ3TYGjoCFDqY9mPQ4T1GTGb`) to release the original XRP (plus your earnings) directly back to your Xaman wallet address.



### What fees are involved in this process?

Since we are dealing with a bridge between two different blockchains (XRPL and Flare), the fees are split between network costs, service fees, and management.

**Xaman Service Fee**

Xaman charges a **0.5%** service fee (in XRP) for deposits.

ie. If you deposit 10 XRP into the yield program, our fee would be **0.05 XRP**.

We do not charge service fees on withdraws.

**Flare Minting Fee**

Flare charge a **0.11%** minting fee when FXRP is minted.

ie. If you deposit 10 XRP into the yield program, the minting fee would be **0.010945 XRP**

**Note:**&#x20;

The actual Flare fee is calculated on the amount _after_ the initial Xaman fee is deducted.

(9.95 XRP x 0.0011 = **0.010945 XRP)**

**Flare Smart Contract Fee**\
\
Flare charges a **2 XRP** flat fee for the Smart Contract operator.\
\
This is a one-time fee to deploy your Flare Smart Account.

**Flare Redemption Fee**\
\
Flare charges a **0.2%** redemption fee.

When you withdraw your FXRP to XRP, you will automatically be charged this fee.

**Upshift Management Fee**

Upshift charges a **1%** management fee per year.&#x20;

This fee is calculated and deducted from the vault on a **daily** basis.

**Upshift Performance Fee**

Upshift charges a **10%** "performance" fee.&#x20;

On any yield that is earned by the vault, Upshift automatically takes 10%.

**Summary**

| **Fee Type**       | **Provider** | **Amount**  | **Timing** | **Notes**                                               |
| ------------------ | ------------ | ----------- | ---------- | ------------------------------------------------------- |
| Service Fee        | Xaman        | 0.5%        | Deposit    | Calculated on the total deposit amount.                 |
| Smart Contract Fee | Flare        | 2 XRP       | One-time   | Flat fee to deploy your Flare Smart Account (FSA).      |
| Minting Fee        | Flare        | 0.11%       | Deposit    | Calculated _after_ the Xaman Service Fee is deducted.   |
| Management Fee     | Upshift      | 1% (Annual) | Ongoing    | Deducted from the vault on a daily basis.               |
| Performance Fee    | Upshift      | 10%         | Ongoing    | Only taken from the _yield earned_ by the vault.        |
| Redemption Fee     | Flare        | 0.2%        | Withdrawal | Automatically charged when converting FXRP back to XRP. |

### What is the estimated "break even" time?

| **Deposit Amount** | **Total Entry Fees\*** | **Est. Annual Yield (at 7% APY)** | **Time to Break Even** |
| ------------------ | ---------------------- | --------------------------------- | ---------------------- |
| 100 XRP            | \~2.61 XRP             | \~6.3 XRP / year                  | \~5 months             |
| 1,000 XRP          | \~7.1 XRP              | \~63 XRP / year                   | \~6 weeks              |
| 10,000 XRP         | \~52 XRP               | \~630 XRP / year                  | \~4 weeks              |

