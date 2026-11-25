---
description: What the xApp does, who runs each part, and where your XRP goes
---

# The Flare XRPFi Yield xApp

The **Flare XRPFi Yield** xApp lets you earn yield on XRP held in your XRP Ledger (XRPL) account. It moves your XRP to the Flare network, where it earns yield in a vault. You sign every step in Xaman, and you can withdraw your funds back to your XRPL account.

The xApp brings together products from three parties:

* Flare runs FAssets, the bridge that turns XRP into FXRP on the Flare network. Flare also runs Flare Smart Accounts.
* Upshift runs the earnXRP vault and decides how the vault earns yield.
* Xaman provides the app you use to sign each transaction.

Flare and Upshift are not part of Xaman. Xaman never holds your funds.

### Key terms

These terms appear throughout the Flare xApp articles:

* FXRP is a token on the Flare network that represents XRP one-to-one. Each FXRP is backed by XRP held on the XRP Ledger.
* A Flare Smart Account is your account on the Flare network. Only instructions signed by your XRPL account control it, so you do not need a second wallet or FLR, the Flare network's coin.
* earnXRP is the token that represents your share of the vault. Its value in FXRP grows as the vault earns yield.

### What happens when you deposit

A deposit takes two signatures in Xaman. Your first signature sends an instruction to Flare to prepare your deposit. It reserves the FXRP that your XRP will become.

Your second signature sends your XRP to an FXRP agent on the XRP Ledger. The agent holds your XRP while the matching FXRP exists. Xaman's service fee is charged with this signature, as a separate payment.

Flare then creates FXRP in your Flare Smart Account and moves it into the vault, without any further signatures. You receive earnXRP for your share of the vault, and the xApp shows your balance.

### While your funds are in the vault

Upshift manages the vault and the strategies it uses to earn yield. As the vault earns, the value of your earnXRP grows. Your number of earnXRP stays the same.

Upshift takes its fees inside the vault, so they never appear as payments from your account.

### What happens when you withdraw

A withdrawal also takes two signatures, with a waiting period between them. Your first signature requests the withdrawal from the vault. The xApp shows when the request will be ready.

When it is ready, your second signature asks Flare to turn your FXRP back into XRP. An FXRP agent then sends the XRP to your XRPL account. This agent can be different from the one that received your deposit.

Withdrawals to the XRP Ledger must be in multiples of 10 FXRP. Xaman does not charge a service fee on withdrawals.

### Frequently asked questions

**Does Xaman hold my XRP?**

No. Xaman is the app you sign with. While your funds are in the vault, your XRP is held by an FXRP agent on the XRP Ledger, and your earnXRP is held in your Flare Smart Account.

**Can I see my Flare Smart Account?**

Yes. The xApp shows your Flare Smart Account address. You can look it up on the Flare network's block explorer.

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [How to Deposit XRP using the Flare xApp](depositing-xrp-with-the-flare-xapp.md)
* [Fees in the Flare xApp](fees-in-the-flare-xapp.md)
* [Flare Smart Accounts](https://flare.network/products/flare-smart-accounts)



***

### **Important Disclaimer**

**Flare Smart Accounts, FAssets, and any associated vault products are developed, operated, and managed by Flare and their respective third-party partners. They are not developed, operated, or controlled by XRPL Labs or Xaman.** Xaman serves solely as a signing interface for XRPL transactions.

While the Flare Smart Accounts architecture is designed to maintain user custody through XRPL key governance, interacting with DeFi protocols and vault strategies still carries inherent risks including but not limited to: smart contract vulnerabilities, cross-chain execution failures, counterparty exposure at the protocol level, liquidity constraints, and market volatility. Self-custody of keys does not eliminate protocol-level risk. Estimated returns are not guarantees of future results.

**Do your own research.** Before interacting with any third-party product through an xApp, understand how it works, what the risks are, where your assets go, and what you are agreeing to. Xaman does not endorse, guarantee, or take responsibility for the performance, security, or outcomes of any third-party xApp, protocol, or platform.
