---
description: From sealed pouch to two cards protecting one account
---

# Setting up your Xaman cards

Your Xaman cards have arrived, so let's open the package together. In about ten minutes, you go from a sealed pouch to a working cold-wallet setup: two cards, one account, and your XRP protected by a card you can hold in your hand. This article walks you through every step, from your first tap to linking your Backup card, and explains why you have two cards and what each one is for.

Xaman cards work on both the XRP Ledger (XRPL) and Xahau. The steps here are for the XRP Ledger. Once your cards are set up, [Activating a Xaman card account on Xahau](../xahau/activating-a-xahau-account/activating-a-xaman-card-account-on-xahau.md) covers Xahau.

### What is in your package

Your package arrives in a sealed pouch, and the cards inside are loose. That is normal, so there is no need to worry when they slide out. Inside, you find:

* At least two cards, in the designs you picked when you ordered.
* A printed instruction sheet, which covers the same setup as this article in less detail.
* A thank-you card, with links to download Xaman from the App Store or Google Play.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2F0T2tpC2uhce5U15uAodB%2Fxaman-thank-you-card.png?alt=media&#x26;token=56857609-4b13-4a25-a52d-0ff6e2eb4361" alt="The thank-you card included in every package, with links to download Xaman" width="375"><figcaption><p>The thank-you card in every package</p></figcaption></figure>

If your package arrived already opened, read [My card package arrived opened](my-card-package-arrived-opened.md) before you go any further.

### Your pre-funded card

One of your cards comes in a clear plastic sleeve with an orange label telling you to import it first. This is your pre-funded card (the label calls it "pre paid"). It comes with enough XRP to activate[^1] its account, so you do not need to buy any XRP to get started. The sleeve is only there so you can spot the card, and it does not change how the card works.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FCtE2UlSmXpXujre5HzV5%2Fxaman-prepaid-label.png?alt=media&#x26;token=339f0b44-dd28-438c-aac6-98616a339a78" alt="The orange label on the pre-funded card&#x27;s sleeve, which says to import this card first" width="375"><figcaption><p>This label marks the card to import first</p></figcaption></figure>

Whichever designs you picked, every card works exactly the same way, including partner ecosystem cards. The only difference is that one card comes pre-funded. That card becomes your Primary card, the one your XRP lives on.

### Before you get started

* A phone with NFC[^2], with NFC turned on.
* An up-to-date version of iOS or Android.
* The latest version of the official Xaman app, from the [App Store](https://apps.apple.com/app/id1492302343) or [Google Play](https://play.google.com/store/apps/details?id=com.xrpllabs.xumm).

{% hint style="info" %}
Already have an XRP Ledger account in Xaman? Read [How to link an existing account to a Xaman card](how-to-link-an-existing-account-to-a-xaman-card.md) before you start. It helps you decide whether to keep your existing account or move everything to a new card account.
{% endhint %}

### How two cards protect one account

Here is the one thing worth understanding before you start: each new card creates and holds its own account. A brand-new card holds no account at all. When you import it, the card creates the keys for a new XRP Ledger account inside its chip, so two cards start out as two separate accounts.

The setup turns those two accounts into one. Your pre-funded card becomes your Primary card, and your XRP lives on its account. You then link your other card to it as your Backup card, through an XRP Ledger feature called a [regular key](#user-content-fn-3)[^3]. (The printed sheet in your package calls it the Signing card, and it is the same thing.) Once they are linked, both cards can sign for your Primary account.

Think of it as two keys to the same door. The Primary card is the master key, and the Backup card is a second key to that same door. You can use either one to get in, which is exactly what protects you if one of them goes missing.

### What Xaman cards do, and what they do not

A Xaman card is a physical card with a secure chip inside. It does three jobs: it creates an [account secret](#user-content-fn-4)[^4], it keeps that secret inside the chip, and it signs transactions for the account it created. The account secret never leaves the chip. It never touches your phone, and Xaman never sees it.

That is what makes the cards so strong, and it also means you should treat them like cash or house keys. Anyone who holds one of your linked cards can use it to sign for your account. Xaman is a self-custody[^5] wallet, so we cannot recover a lost card, freeze your account, or reverse a transaction for you.

The cards are not bank cards. You cannot use them at an ATM, as a debit or credit card, or to connect to a bank account. They do one thing only, which is to protect and control your accounts on the XRP Ledger and Xahau.

### Set up your cards

The whole setup takes about ten minutes. Follow the three parts in order, since each one builds on the last.

#### Import your pre-funded card

Take the pre-funded card out of its sleeve, and import it first.

1. Tap **Settings** > **Accounts**.
2. Tap **+ Add account**.
3. Tap **Add Xaman Tangem card**.
4. Follow the instructions on the screen.
5. Tap **Activate your account** to claim the XRP on your pre-funded card.

This account is now your Primary account. [How to import your Xaman card](...a-xaman-tangem-card.md) shows each screen of the import.

Your Primary account's **Home** screen now shows the XRP from your pre-funded card, with a **No back-up card configured** reminder at the top. That reminder is your next step.

#### Link your second card as your Backup card

The reminder is not an error, and it stays until your Backup card is linked. Your second card does not need to be imported first, and it does not need any XRP, since it only ever signs for your Primary account.

1. Tap **No back-up card configured** on your Primary account's **Home** screen.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FgoyfPymkMMJDXnbO6vVX%2Fxaman-backup-card-banner-arrow_2x.png?alt=media&#x26;token=2ad4e618-7d1f-47a8-adb8-1529a7f8ea5d" alt="The Home screen with the No back-up card configured box at the top, above the Primary card account" width="375"><figcaption><p>Tap the box to link your Backup card</p></figcaption></figure>

2. Check that the card ID on the screen matches your Primary card.
3. Tap **Start**.
4. Tap **Scan original card**.
5. Hold your Primary card against the back of your phone until the scan finishes.
6. Tap **Scan back-up card**.
7. Hold your second card against your phone until the scan finishes.
8. Check that both cards are shown, and tap **Continue**.
9. Tap **Confirm**.
10. Hold your Primary card against your phone once more to approve the link.
11. When **Back-up card linked** appears, tap **Done**.

The reminder is gone once the link is in place, and that is your sign that both cards are ready to use. [Setting up a Backup card](setting-up-a-backup-card.md) walks through every screen, and also covers which card to carry day to day.

#### Move your funds to your Primary account

With both cards linked, you can send your XRP and any other assets to your Primary account. If you already had an XRP Ledger account before your cards arrived, you can move everything to the card account or keep both, and either choice is fine. [How to link an existing account to a Xaman card](how-to-link-an-existing-account-to-a-xaman-card.md) helps you decide.

One thing is worth doing right now, while both cards are in your hands: write down your Primary account's r-address[^6] and keep it somewhere safe. If you ever lose your phone and your Primary card together, you need it to reach your account with your Backup card. [Lost or damaged cards](lost-or-damaged-cards.md) covers what to do if a card goes missing.

### If you have more than two cards

An account can have only one Backup card, so a third card cannot become a second Backup for the same account. Extra cards are still useful, and you can put them to work in a few ways:

* As a spare, ready to replace your Backup card if one is ever lost or damaged.
* As a separate account for daily spending, NFTs, trading, or testing.
* As a gift for a friend or family member.
* As one of several signers in a multi-signing setup, which is an advanced option. See [Multi Signature](../xrp-ledger-basics/xrp-ledger-concepts/multi-signature.md).

Extra cards are not pre-funded, so you need to activate each one you plan to use as its own account.

### Frequently asked questions

**Can I use the other card as my Primary card instead?**

You can, though it takes a few extra steps after you set up both cards. First, activate the second card's account yourself by sending it enough XRP to cover the reserve. Next, delete the account on the pre-funded card, choosing your new Primary account as the destination, so its remaining XRP moves there. Finally, link the pre-funded card as your Backup card. Deleting an account has its own cost and waiting time, which [How to delete an XRPL account](../your-accounts/importing-your-account/how-to-delete-an-xrpl-account.md) explains.

**Why can I not spend the XRP on my pre-funded card?**

That XRP is the reserve, the minimum balance an XRP Ledger account must keep once it is active. It shows in your balance, but it stays locked for as long as the account exists. This is a rule of the XRP Ledger, not a Xaman fee, and the network can change the amount over time. Your Backup card's account is never activated, so it has no reserve to keep.

**My Backup card's account says Not set up yet. Is my backup working?**

That line is about the Backup card's own account, not your Primary account, so it does not mean anything is wrong. To check your backup, tap **Settings** > **Accounts**, then **Edit** next to your Primary card account. The **Back-up card** line shows your Backup card's name when the link is in place.

**What if my package arrived opened?**

Do not import the cards yet. Read [My card package arrived opened](my-card-package-arrived-opened.md), and contact us through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md) if you are unsure about anything. Our support team will never ask for your account secret. Anyone who asks is trying to take your funds.

### See also

* [Setting up a Backup card](setting-up-a-backup-card.md)
* [Xaman cards](xaman-tangem-cards.md)
* [How to import your Xaman card](...a-xaman-tangem-card.md)
* [What is a "Pre-funded" Xaman card?](what-is-a-pre-funded-xaman-card.md)
* [Best security practices for the Xaman cards](best-security-practices-using-a-xaman-card.md)
* [Lost or damaged cards](lost-or-damaged-cards.md)
* [Activating a Xaman card account on Xahau](../xahau/activating-a-xahau-account/activating-a-xaman-card-account-on-xahau.md)



[^1]: Sending an account its first XRP, enough to cover its reserve. Until then, the account does not exist on the XRP Ledger.

[^2]: The technology your phone uses for tap-to-pay. Xaman uses it to talk to your Xaman cards.

[^3]: A second key that can sign for your account, such as a Backup card.

[^4]: The secret that controls your account, as Secret Numbers, a Family Seed, or a Mnemonic. Never share it with anyone.

[^5]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^6]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.
