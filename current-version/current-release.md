---
description: A security and clarity release, rolling out to both stores this week
---

# What's New in Xaman 5.4

_November 25, 2026_

Xaman 5.4.0 is a security and clarity release. It makes scam warnings harder to miss and easier to act on, gives your Xaman card an easier backup flow, and lets you sign new network features the day they go live, all while making Xaman faster and more secure underneath.

The update is a phased release, rolling out gradually on the App Store and Google Play over the course of this week, so it may not be available in your store yet. No action is needed on your side, and the update arrives on its own.

### Set up your Xaman Tangem card backup

Every Xaman Tangem card ships as a set, and the second card is your backup. If the original is ever lost or damaged, the backup keeps full access to the account. 5.4.0 makes setting it up a guided flow: scan the backup card, approve the link with your original card, and wait while the network confirms it. No funds need to be added to the backup card.

1. Tap **Settings** > **Accounts**.
2. Select your Xaman card account.
3. Follow the guided steps to link your backup card.

From the same screen you can also:

* Identify a backup card, to check that the card in your hand is the one linked to your account
* Replace a backup card
* Remove a backup card, with a clear warning about what that means for your access

A backup card is the difference between a lost card and a lost account. [_How to configure a backup signing account_](../xaman-cards/how-to-configure-a-backup-signing-account.md) covers the flow in detail.

### Stronger scam warnings, and a faster way out

Sign requests that involve an account or object reported as a possible scam now carry stronger, clearer warnings, and a prominent **Reject** button, so the safe choice is the easy one. Warnings about sensitive transaction types are now separated from warnings about reported scams, so each says exactly what it means.

Xaman also checks before you can accept. The **Slide to accept** control stays disabled until the scam lookup has finished for the account that will actually sign, so a result for one account can never be applied to another.

### A hardened core

On Android, Xaman now requires strong biometrics for the biometric prompt, keeps the vault more durable through interrupted writes and process kills, and enforces the complete passcode cooldown interval between attempts.

Across both platforms, xApps are more tightly walled off from the rest of Xaman. Each xApp now only receives the information it needs to work with your account, and only on its own domain. An xApp cannot pop up its own dialogs pretending to be Xaman, and cannot send you to places on your phone it has no business opening.

None of this changes how you use Xaman.

### A refreshed xApp directory

The xApp directory has a new look. Tiles take their color from each xApp's own icon, headers and surfaces match the rest of the app, and automatic refreshes no longer move the list while you are scrolling it.

xApps also now receive Xaman's light or dark mode as a standard signal, so an xApp can follow your theme without any extra work from its developer.

### Universal Signing: new network features, usable from day one

The XRP Ledger and Xahau keep adding new transaction types and new fields. Until now, each one needed its own purpose-built review screen in Xaman before you could sign it, and until that screen existed, the feature was out of reach.

Xaman now reads the live definitions published by the network itself and uses them to review and sign supported transaction types and fields, even ones without a dedicated screen yet. You still see everything before you sign: the full values, including nested data and raw hex where that is what the transaction contains. Where Xaman cannot yet explain what a field means, it tells you so, with a clear warning, rather than hiding it.

When a new feature goes live on the network, you can start using it in Xaman without waiting for a custom screen. Nothing gets signed blind, and nothing gets held back.

### Smaller changes that add up

* **QR scanner flashlight.** A flashlight toggle on the scan screen, for the moments when the QR code is in a dark room or on a dim screen.
* **Swap review.** The review screen is clearer about what you pay and what you receive. Partial payments show the minimum you will receive first, and a service fee is now only charged when a trade actually moved value, never on a swap that did nothing.
* **xApp account and network switching.** When an xApp asks for a specific account or network, such as a switch from the XRP Ledger to Xahau, Xaman now switches more consistently, including when the request arrives through a push notification.
* **Translations.** Every language has been reviewed for shorter, more natural, localized wording.
* **Stability and usability.** Dozens of smaller fixes, including Settings alignment, account reordering, the escrow condition on review screens, and a connection to the network that never gives up.

### Update now

Xaman 5.4.0 is a phased release, rolling out gradually on the [App Store](https://apps.apple.com/us/app/xaman-xrp-wallet/id1492302343) and [Google Play](https://play.google.com/store/apps/details?id=com.xrpllabs.xumm\&hl=en) over the course of this week. If the update is not showing for you yet, it is on its way.

Once you have it: if you hold a Xaman Tangem card, open **Settings** > **Accounts** and confirm your backup card is set up.

As always, feedback helps shape the next releases. If you run into issues or notice anything off, report it through the Xaman Support xApp.

<a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Open the Xaman Support xApp</a>

### Frequently asked questions

**Why can't I find 5.4.0 in my store yet?**

The update rolls out in phases over the course of this week. Check your store again later today, and make sure automatic updates are on if you would like it to arrive on its own.

**What does Universal Signing change for me?**

You can use new network features as soon as they go live, without waiting for a dedicated screen in Xaman. You still review every value before you sign, and Xaman warns you when it cannot explain a field yet.

### See also

* [How to configure a backup signing account](../xaman-cards/how-to-configure-a-backup-signing-account.md)
* [Spam on the XRP Ledger](../scams-and-staying-safe/spam-on-the-xrp-ledger.md)
* [Token vetting and the token warning](../tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning.md)
* [What's New in Xaman 5.0](previous-releases/whats-new-in-xaman-5.0.md)
