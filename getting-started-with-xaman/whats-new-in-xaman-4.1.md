---
description: >-
  Xaman 4.1.0 introduces major improvements that make it easier to onboard,
  explore tokens, and send or receive payments in any XRPL asset.
---

# 🎉 What's New in Xaman 4.1

This article explains the new features, how to use them, and what you should know when getting started.

***

### 🔁 Smart Payment Requests (Now with Pathfinding & Issued Token Support)

Payment requests can now be paid in **any XRPL token**, not just XRP, and thanks to pathfinding, the person sending the payment doesn’t need to hold the same token you request. The receiver always gets the asset they've requested.

#### How It Works

Let’s say you request **100 RLUSD**, but your friend doesn’t have any RLUSD.\
With Xaman 4.1.0:

* Your friend can still pay using another token they hold (e.g. Token X)
* Xaman finds the best route on the XRPL DEX/AMM (e.g. **Token X → XRP → RLUSD**)
* You receive **exactly 100 RLUSD**—automatically

This is possible thanks to **pathfinding**, which scans the XRPL for available liquidity and builds a payment path, usually using **XRP as the bridge currency**.

#### Key Benefits

* You don’t need to know what token the sender holds
* The sender doesn’t need to swap manually
* The receiver always gets the correct amount
* Works with all issued assets—RLUSD, EUR, USD-backed tokens, and more

#### How to Use It

1. Open **Xaman**
2. Tap **Receive** on the home screen
3. Choose the token and amount to request
4. Share the generated **Payment Request link**

Xaman will handle the rest, automatically performing pathfinding and suggesting the best available route to the sender.

> ℹ️ **Note:** This feature supports both the **XRPL** and **Xahau** networks. If someone opens a request on the wrong network, Xaman will prompt them to switch.

***

### 🚀 20x Faster Onboarding (With Backup Later Option)

First-time users can now set up Xaman in **under 20 seconds**—no immediate backup required.

#### What’s New

* First-time users can create an account in seconds
* **Skip key backup temporarily** to access the wallet immediately
* A **persistent warning** reminds you to complete the key backup later

This makes Xaman ideal for quick demos, public events, and helping friends get started with self-custody.

> ⚠️ **Warning:** If you skip backing up your keys and lose your phone or device, your account will not be recoverable.
>
> \
> The secret numbers are **not stored anywhere**—you must write them down and verify them manually.

#### Best Practice

Always complete your key backup as soon as possible. Until then, you’ll see a warning banner in the app.

***

### 🧭 New Token Browser (Discover & Add Tokens Easily)

The updated token browser makes it easy to explore and add XRPL tokens.

#### How to Access It

1. Tap **Add** on your Xaman home screen
2. Browse:
   * **Popular tokens** (ranked by holder count)
   * **Ecosystem tokens** (ranked by volume)
3. View details for any listed token
4. Add a TrustLine with one tap

#### Important Reminder

Always double-check the token name, issuer, and details before adding a TrustLine.\
Never interact with suspicious or unknown assets.

***

### 📱 Swipe Navigation in xApps

You can now **swipe left or right** from the edges of your screen while using xApps.

This allows you to:

* Move between views smoothly
* Avoid reloading pages
* Navigate naturally, just like switching between apps

#### Where It Works

This gesture navigation works in most xApps, including:

* DeFi dashboards
* NFT marketplaces
* Swap and liquidity apps

***

### 🔧 New Transaction Types

Xaman 4.1.0 supports the latest XRPL and Xahau transaction types and flags, including:

* Full support for all known **transaction flags**
* Support for **SetRemarks**, a Xahau-specific feature that lets users add human-readable metadata to transactions

These updates ensure compatibility with future tools and smart contract use cases.

***

### 🛠️ Other Improvements

We’ve also made a wide range of behind-the-scenes updates:

* UI polish and small visual tweaks
* Improved responsiveness and transitions
* Minor bug fixes for a smoother experience

***

### FAQ

**Can I request stablecoins like RLUSD or EUR?**\
Yes! You can request any issued currency on XRPL or Xahau—including RLUSD, USD, EUR, etc.

**Can the sender pay using a different token?**\
Yes. Xaman uses pathfinding to convert the sender’s token into your requested asset using XRPL’s DEX and AMM.

**What is XRP’s role in this?**\
XRP usually acts as the **bridge currency** in the payment path. For example:\
**Token X → XRP → RLUSD**

**Do I need to perform a manual swap before sending?**\
No. The entire transaction is automatic. Xaman handles the swap and routing for the sender.

**What if I skip the key backup during onboarding?**\
You can still use Xaman right away, but if your device is lost, your account cannot be recovered.\
Until the backup is completed, you’ll see a persistent warning in the app.

**Can I use the new onboarding flow if I’m already a Xaman user?**\
No. This faster onboarding is available only for first-time users.

**How do I know a token is safe to add?**\
Check the issuer details carefully and make sure the token is from a trusted source. If in doubt, ask in the XRPL community or Xaman support.

***

### Need More Help?

If you have any questions or run into issues:

* Use the in-app support xApp to message our team directly
