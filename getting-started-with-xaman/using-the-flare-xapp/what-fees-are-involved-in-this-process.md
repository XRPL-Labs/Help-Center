# What fees are involved in this process?

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

