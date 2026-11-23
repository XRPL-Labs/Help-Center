---
description: How to decide which apps, xApps, and token issuers to trust
---

# Trust in the XRPL Community

### Background

Lots of people build on the XRP Ledger (XRPL), from solo developers to large companies, and most of them do honest work. The network is open to everyone, though, so anyone can launch an app or issue a token. Nobody checks every one of them, not even Xaman. It pays to know how to tell a solid project from a risky one. This article explains how you can check Xaman for yourself, what an xApp can and cannot do, and how to look into a token issuer before you add its token.

This article covers the XRP Ledger. xApps work the same way on Xahau, and tokens on Xahau have their own articles.

### Why you can check Xaman for yourself

You should not have to take any wallet on faith, so Xaman is built so you do not have to. It is a self-custody[^1] wallet: your account secret stays on your phone or your Xaman card, every signature happens on your device, and your funds stay on the XRP Ledger. If Xaman's servers ever went offline, your funds would still be there, and you could reach them with any other wallet.

You can also check the people and the code behind it. Xaman's source code is public on GitHub, and an independent security firm has reviewed it (see [_Has Xaman been audited?_](../security/all-about-security/has-xaman-been-audited.md)). The team is public too, in [_About XRPL Labs_](../about-xaman/what-is-xrpl-labs.md), and the status page at `status.xrpl-labs.com` shows whether Xaman's services are running normally.

None of that makes any account safe on its own. What keeps your funds safe is that only you hold your account secret, and that you read every request before you sign it. _Security in Xaman_ covers the habits that matter most.

### What an xApp can and cannot do

An xApp is a small web app that runs inside Xaman, made by Xaman or by another developer. It never gets into your account directly. The first time an xApp wants your address, Xaman asks you to approve it, and you can decline.

If you approve, an xApp can do two things:

* **See your r-address.** Your address is already public on the XRP Ledger, so this tells the xApp nothing new about you.
* **Send you notifications through Xaman.** It cannot reach you any other way.

An xApp cannot see your account secret, sign anything for you, or use your camera, microphone, or location. What it can do is prepare a transaction and send it to you as a [sign request](#user-content-fn-2)[^2]. Xaman shows you exactly what the transaction does, and nothing happens unless you sign it with your passcode, biometrics, or Xaman card.

You can see every xApp you have approved, and remove any of them, in **Settings** > **Third party apps**. [_Third party apps_](../using-the-xaman-app/understanding-the-settings-options/third-party-apps.md) explains how.

{% hint style="warning" %}
An xApp can ask you to sign any transaction, including one that sends your funds away. A signed transaction cannot be reversed. Read every sign request in full, and decline anything you do not understand.
{% endhint %}

### Choose which xApps to use

XRPL Labs makes some xApps itself, such as Account Merge and DEX Trade, and many others come from community developers and businesses. Every xApp goes through a review by the Xaman team before other Xaman users can open it, and every later change is reviewed again. To pass, a developer must complete identity checks (KYC), publish the xApp's source code, and make clear that the xApp is theirs, not Xaman's.

The review also sets rules for how an xApp treats you. These are the ones worth knowing, since an xApp that breaks one of them is a red flag:

* **It never asks for your account secret.** No reviewed xApp asks for Secret Numbers, a Family Seed, or a Mnemonic, in any form.
* **It never asks to change who can sign for your account.** An xApp cannot ask you to set a regular key or a signer list. Those changes are yours to make, directly.
* **It only asks you to sign when you start something.** A sign request should never appear on its own when the xApp opens.
* **It explains first.** Before each sign request, it tells you in plain words what you are signing, and it shows any fees up front.

If an xApp breaks one of these rules, decline the request and tell us about it in the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md).

Some reviewed xApps appear on the **xApps** screen. Others open only from a link the developer shares, since the Xaman team lists new projects only once it knows them better. Either way, a review lowers the risk, but it cannot tell you whether a project is right for you. A few checks of your own still help:

* **The developer's website.** Is it current, and does it say clearly who is behind the xApp?
* **The xApp's description.** Does it explain plainly what the xApp does?
* **Support.** Does the developer offer support, and do they answer when you ask a question?
* **Their history.** Have they been active in the XRP Ledger community for a while, under the same name?

### Check a token issuer before you add a trust line

To hold a token, you add a [trust line](#user-content-fn-3)[^3] to its issuer. That is a choice to trust the account that issued it, since a token is only worth what its issuer stands behind. Nothing on the XRP Ledger checks issuers for you, and any issuer can give a token any name, so a token called "USD" or even "XRP" may have nothing to do with the real thing.

Issuers can also have powers that XRP does not have. Depending on its settings, an issuer may be able to freeze its token or take it back from your account. [_Token freezes and clawback_](../tokens-trust-lines-and-nfts/token-freezes-and-clawback.md) explains how that works.

Before you add a trust line, a few checks go a long way:

* **Get the issuer's address from the source.** If a token claims to represent a business or a real-world asset, confirm the exact issuer address on that business's official website.
* **Look at the team.** Can you find out who runs the project, and have they been through identity checks (KYC)?
* **Read their plans.** Do they explain what the token is for, how it is funded, and what happens next?
* **Contact them.** Do they reply, and how long does it take?

Xaman also shows a warning on some tokens, explained in _Token vetting and the token warning_. If you cannot find out who is behind a token, or what gives it value, do not add the trust line.

### Frequently asked questions

**Can an xApp see my balance?**

Xaman does not give your balance to an xApp. Your balance is public on the XRP Ledger, though, so any xApp that knows your r-address can look it up, the same way anyone can in an explorer. It still cannot move anything without your signature.

**I signed something in an xApp and lost funds. What now?**

A signed transaction cannot be reversed, by Xaman or by anyone else. _I've been scammed!_ walks you through what to do next, and you can tell us about the xApp in the Xaman Support xApp so we can look into it.

Crypto assets can change in value. This article explains how these features work and is not financial advice.

### See also

* [Security in Xaman](../security/security-in-xaman.md)
* [Has Xaman been audited?](../security/all-about-security/has-xaman-been-audited.md)
* [About XRPL Labs](../about-xaman/what-is-xrpl-labs.md)
* [Third party apps](../using-the-xaman-app/understanding-the-settings-options/third-party-apps.md)
* [Token vetting and the token warning](../tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning.md)
* [Token freezes and clawback](../tokens-trust-lines-and-nfts/token-freezes-and-clawback.md)
* [Trust lines on the XRP Ledger](../tokens-trust-lines-and-nfts/trust-lines-on-the-xrp-ledger.md)
* [Official communication channels](official-communication-channels.md)
* [I've been scammed!](ive-been-scammed.md)

[^1]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^2]: A transaction an app or website prepares and sends to Xaman for you to review. Nothing happens unless you sign it.

[^3]: Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.
