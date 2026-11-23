---
description: Xaman 5.0.0 Brings Virtual Assets and True Offline Resilience
---

# 🎉 What's New in Xaman 5.0

_January 20, 2026_

Xaman 5.0.0 is a resilience-focused release built around two goals: giving you a clearer overview of what you own, and keeping the wallet operational even when primary infrastructure is unavailable.

This article explains the new features, how to use them, and what you should know when getting started.

***

### 🪙 Virtual Assets (See Everything You Own in One Place)

Xaman 5.0.0 introduces support for Virtual Assets—a new way to represent value you own that isn't currently held as a directly spendable balance in your Xaman account.

#### What Are Virtual Assets?

A growing number of users commit assets to strategies and products such as yield earning or other managed positions. Those assets are often not instantly spendable and not always visible in one place.

Virtual Assets solve this by letting Xaman present a more complete picture of what you own—across providers on the XRP Ledger and on external networks where you have a claim—while making it clear that these positions may not be immediately liquid.

#### What This Means for You

* Your home screen can reflect value you own across multiple providers and networks
* Positions that aren't instantly spendable are clearly distinguished
* Over time, Virtual Assets will enable contextual shortcuts to relevant xApps, so you can review, manage, or redeem where appropriate

#### What's Available Now

Xaman 5.0.0 lays the technical groundwork that enables upcoming capabilities, including foundations needed for smart account functionality. The products that use these capabilities are close, and 5.0.0 ensures the wallet is ready to support them cleanly and safely when they arrive.

ℹ️ **Note:** Virtual Assets will become available through third-party providers. Stay tuned for announcements as integrations go live.

***

### 🔒 Full Fallback Mode When Backend Is Offline

The most important functional change in 5.0.0 is simple: Xaman can now keep working for manual actions even if the Xaman Backend is unreachable.

> _"Wallet resilience is not only about protecting keys. It is about resilience and clarity. Xaman 5.0.0 is designed to keep users transacting, in control and informed, even when conditions are not ideal."_ — **Robert Kiuru**, COO of XRPL Labs

#### How It Works

When primary infrastructure is unavailable, Xaman fully falls back to XRPL node-only operation for:

* Manual sending of transactions
* Manual Exchange actions, such as setting a Trust Line

In practical terms, the wallet no longer depends on a single path to stay usable during infrastructure outages or severe connectivity issues. If you can reach the XRPL network through nodes, you can keep moving.

#### Key Benefits

* No single point of failure for core wallet actions
* Transactions and Trust Lines can still be set manually
* You stay in control even during backend outages or poor connectivity

***

### 💰 Faster Fiat Value Loading on the Home Screen

Xaman 5.0.0 improves the speed and responsiveness of loading and displaying fiat values for all assets on your home screen.

#### How to Enable It

1. Open Xaman
2. Go to **Settings → General → Show Asset Prices on Home Screen**
3. Toggle it on

Once enabled, Xaman will load and display pricing data faster, improving the at-a-glance portfolio experience.

***

### 🌐 Alternative Nodes for Manual Sending

To support resilience during bad connectivity, Xaman can now route manual sending through alternative nodes when needed.

#### How to Configure It

1. Open Xaman
2. Go to **Settings → Advanced → Networks → Network Settings**
3. Select or add your preferred alternative nodes

This is particularly useful when your default path is degraded, or when you want to explicitly choose which infrastructure Xaman should attempt to use.

***

### 🛠️ Why This Release Matters

Xaman 5.0.0 is about strengthening the fundamentals:

* **Clarity:** Virtual Assets prepare Xaman to show a fuller picture of what users own across platforms and networks.
* **Resilience:** Node-only fallback keeps core manual actions available even during backend outages.
* **Performance:** Faster home screen valuation improves everyday use without changing how you operate the wallet.

***

### FAQ

**What are Virtual Assets?** Virtual Assets represent value you own that isn't held as a directly spendable balance—such as assets committed to yield strategies, managed positions, or claims on external networks.

**Are Virtual Assets available right now?** Xaman 5.0.0 lays the technical foundation. Virtual Assets will become available through third-party providers in upcoming releases.

**What happens if the Xaman backend goes offline?** Xaman will automatically fall back to XRPL node-only operation. You can still manually send transactions and set Trust Lines as long as you can reach the XRPL network.

**Do I need to do anything to enable fallback mode?** No. Fallback mode activates automatically when the backend is unreachable.

**How do I configure alternative nodes?** Go to **Settings → Advanced → Networks → Network Settings** to select or add preferred nodes.

**How do I enable fiat values on my home screen?** Go to **Settings → General → Show Asset Prices on Home Screen** and toggle it on.

***

### Previous Updates

* **A More Accessible XRPL: Xaman 4.6.1 Speaks to the World** — Xaman now supports one of the broadest language sets ever introduced to the wallet, expanding advanced language access to almost six billion speakers. _(December 2, 2025)_
* **Xaman 4.5.0: New Account Worth, Home Screen Overhaul, and Batch Support** — One of our cleanest and most powerful updates to date, with a redesigned home screen, new Account Worth and per-asset fiat values, and full support for the Batch amendment. _(November 3, 2025)_
* **Xaman 4.4.0: AMM Liquidity, Extended MPT Support & Permissioned Domains** — Important steps toward the bigger picture of XRPL DeFi, with AMM liquidity tools, extended MPT support, and permissioned domain capabilities. _(October 10, 2025)_
* **One Big Step Forward for Tokens on XRPL** — Celebrating the XRPL's pioneering approach to issued assets, allowing stablecoins, community tokens, and real-world value to live natively alongside XRP. _(September 2, 2025)_

***

### Need More Help?

If you have any questions or run into issues:

* Use the in-app support xApp to message our team directly
