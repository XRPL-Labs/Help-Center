# What fees are involved in this process?

### What fees are involved in this process?

Since we are dealing with a bridge between two different blockchains (XRPL and Flare), the fees are split between network costs, service fees, and management.

**Xaman Service Fee -** Xaman charges a **0.5%** service fee (in XRP) for deposits.

ie. If you deposit 10 XRP into the yield program, our fee would be **0.05 XRP**.

Note: We do not charge service fees on withdraws.<br>

\
**Flare Minting Fee -** Flare charge a **0.11%** minting fee when FXRP is minted.

ie. If you deposit 10 XRP into the yield program, the minting fee would be **0.010945 XRP**

The actual Flare fee is calculated on the amount _after_ the initial Xaman fee is deducted.

(9.95 XRP x 0.0011 = **0.010945 XRP)**



**Flare Smart Contract Fee -** Flare charges a **2 XRP** flat fee for the Smart Contract operator.\
\
This is a one-time fee to deploy your Flare Smart Account.



**Flare Redemption Fee -** Flare charges a **0.2%** redemption fee.

When you withdraw your FXRP to XRP, you will automatically be charged this fee.

\
**Upshift Management Fee -** Upshift charges a **1%** management fee per year.&#x20;

This fee is calculated and deducted from the vault on a **daily** basis.

\
**Upshift Performance Fee -** Upshift charges a **10%** "performance" fee.&#x20;

On any yield that is earned by the vault, Upshift automatically takes 10%\
.

**Summary**

<table data-header-hidden><thead><tr><th width="106.31640625"></th><th width="181.4296875"></th><th width="122.375"></th><th width="119.52734375"></th><th></th></tr></thead><tbody><tr><td><strong>Provider</strong></td><td><strong>Fee Type</strong></td><td><strong>Amount</strong></td><td><strong>Timing</strong></td><td><strong>Notes</strong></td></tr><tr><td>Xaman</td><td>Service Fee</td><td>0.5%</td><td>Deposit</td><td>Calculated on the total deposit amount.</td></tr><tr><td>Flare</td><td>Smart Contract Fee</td><td>2 XRP</td><td>One-time</td><td>Flat fee to deploy your Flare Smart Account (FSA).</td></tr><tr><td>Flare</td><td>Minting Fee</td><td>0.11%</td><td>Deposit</td><td>Calculated <em>after</em> the Xaman Service Fee is deducted.</td></tr><tr><td>Upshift</td><td>Management Fee</td><td>1% (Annual)</td><td>Ongoing</td><td>Deducted from the vault on a daily basis.</td></tr><tr><td>Upshift</td><td>Performance Fee</td><td>10%</td><td>Ongoing</td><td>Only taken from the <em>yield earned</em> by the vault.</td></tr><tr><td>Flare</td><td>Redemption Fee</td><td>0.2%</td><td>Withdrawal</td><td>Automatically charged when converting FXRP back to XRP.</td></tr></tbody></table>

***

### **Important Disclaimer**

### **Important Disclaimer**

**Flare Smart Accounts, FAssets, and any associated vault products are developed, operated, and managed by Flare and their respective third-party partners. They are not developed, operated, or controlled by XRPL Labs or Xaman.** Xaman serves solely as a signing interface for XRPL transactions.

While the Flare Smart Accounts architecture is designed to maintain user custody through XRPL key governance, interacting with DeFi protocols and vault strategies still carries inherent risks including but not limited to: smart contract vulnerabilities, cross-chain execution failures, counterparty exposure at the protocol level, liquidity constraints, and market volatility. Self-custody of keys does not eliminate protocol-level risk. Estimated returns are not guarantees of future results.

**Do your own research.** Before interacting with any third-party product through an xApp, understand how it works, what the risks are, where your assets go, and what you are agreeing to. Xaman does not endorse, guarantee, or take responsibility for the performance, security, or outcomes of any third-party xApp, protocol, or platform.
