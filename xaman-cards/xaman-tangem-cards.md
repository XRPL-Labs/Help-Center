---
description: How Xaman cards keep your account secret on a chip, and how to use them
---

# Xaman cards

Xaman cards are NFC cards made by Tangem for use with Xaman. Each card has a secure chip that creates and stores the [account secret](#user-content-fn-1)[^1] for an XRP Ledger (XRPL) account, and that secret never leaves the chip. You use the card together with Xaman on your phone: Xaman shows you each transaction, and the card signs it when you hold it against your phone. It is a way to keep the key to your savings in your own hand.

This article explains how the cards work, what protects them, and why every card account needs a Backup card. If your cards have just arrived, [Setting up your Xaman cards](getting-started.md) walks you through the setup step by step.

### How a Xaman card works

A new card ships without an account secret. The first time you use it, its chip creates the secret itself, powered by your phone over NFC[^2]. From then on, the card is the only place that secret exists.

To sign a transaction, you hold the card against your phone. Xaman sends the transaction to the card, the card signs it on the chip, and Xaman sends the signed transaction to the XRP Ledger. The card can only sign. It cannot show, export, or copy its account secret, so the secret never reaches your phone at all.

### How the card protects your account secret

Every Xaman card has a secure chip certified to a security level called EAL6+. The chip creates your account secret with its own random number generator, and from then on, nothing can extract it: not Xaman, not XRPL Labs, and not the phone you hold the card against. When you sign, the card sends back only the signature, never the secret. Your part is the same as with any account: read each transaction carefully before you sign it.

### Someone nearby with an NFC reader

NFC only works over a few centimeters, so anyone trying to talk to your card would need to hold a device right against it. Xaman cards are set up at the factory with extra protections against this kind of close-range attempt:

* **A long tap.** Your card is set to need a long tap, so you hold it against your phone for a moment before it signs. Someone would have to stay within a few centimeters of your card for that whole time, which you would notice.
* **Encrypted communication.** The card and Xaman encrypt everything they send each other over NFC.
* **Short sessions.** Each NFC session is kept short, which leaves little time for anyone to listen in.
* **Unused features turned off.** The chip can do far more than Xaman needs, and every feature Xaman does not use is turned off at the factory.
* **Genuine-card checks.** Xaman checks every new card the first time you tap it, to confirm the card is genuine and has never been used.

The real risk to a card is the same as for cash: someone getting hold of the card itself, or talking you into signing something. Keep your cards somewhere only you can reach, and read every transaction before you tap. Our support team will never ask for your account secret, or ask you to tap your card to fix your account. Anyone who asks is trying to take your funds. If a card is lost or stolen, [Lost or damaged cards](lost-or-damaged-cards.md) walks you through what to do.

### When to use a Xaman card

An account secret stored in Xaman on your phone is convenient for everyday use. For larger amounts, you may prefer to keep the secret off your phone altogether, and that is where a card fits. A common setup uses two accounts:

* A spending account in Xaman, for receiving funds and day-to-day transactions.
* A savings account on a Xaman card, for larger amounts.

To top up your spending account, sign a payment from your savings account with your card. When your spending account holds more than you are comfortable with, send some of it to your card account. Xaman cards work with everything Xaman supports on the XRP Ledger and Xahau, such as tokens, the DEX, escrows, NFTs, and account settings.

### Why every card account needs a Backup card

A card's account secret exists in only one place: on that card. If you lose or damage your only card, you lose access to its account, and no one can recover the secret from the chip, including us. Xaman is a self-custody[^3] wallet, so we cannot recover a lost card, freeze an account, or reverse a transaction for you.

That is why every order includes at least two cards. Your second card becomes a [Backup card](#user-content-fn-4)[^4], linked to your Primary card's account through an XRP Ledger feature called a [regular key](#user-content-fn-5)[^5]. The Backup card keeps its own account secret, and nothing is ever copied from one chip to the other. Once the two are linked, either card can sign for your Primary account, so losing one card does not lock you out.

To set up your Backup card, tap **Settings** > **Accounts**, tap **Edit** next to your Primary card account, and tap **Set up** next to **Back-up card**. Xaman guides you from there: you scan your Primary card, scan your second card, and approve the link with your Primary card. Your second card's account is added to Xaman for you, and it needs no XRP of its own.

Once the link is in place, the **Back-up card** line shows your Backup card and an **Update** button. Tapping **Update** lets you identify, replace, or remove your Backup card, so you can always check that the card in your hand is the one linked to your account. [Setting up a Backup card](setting-up-a-backup-card.md) walks you through the setup step by step.

The guided setup needs an up-to-date version of Xaman. If you do not see it, update Xaman from the App Store or Google Play, and check again.

{% hint style="warning" %}
A card account without a Backup card depends on that one card. If the card is lost or damaged, the funds in its account can no longer be reached. Link your Backup card before you send funds to a card account.
{% endhint %}

### Get Xaman cards

You can order Xaman cards in the [**Get cards**](https://xumm.app/detect/xapp:xumm.tangem-order) xApp in Xaman, or on [our website](https://xaman.app/cards).

When your cards arrive, [Setting up your Xaman cards](getting-started.md) takes you from the sealed pouch to a working setup.

### Xaman cards and Tangem cards

Xaman cards are branded Tangem cards, but they run custom firmware that XRPL Labs had tuned and re-audited for the XRP Ledger and Xahau. When you set up a card in Xaman, it is prepared to work with Xaman. You can still import it into the Tangem app afterward and use it there too. A card set up in the Tangem app first can no longer be added to Xaman.

{% hint style="warning" %}
Set up a new Tangem card in Xaman before you use it in the Tangem app. If you set it up in the Tangem app first, you cannot add it to Xaman later.
{% endhint %}

|                              | Set up in Xaman first                                              | Set up in the Tangem app first                          |
| ---------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------- |
| Works in Xaman               | Yes                                                                | No                                                      |
| Works in the Tangem app      | Yes, after you import it                                           | Yes                                                     |
| XRP Ledger features in Xaman | Everything Xaman supports, including tokens, escrows, and NFTs     | None                                                    |
| Backup                       | A second card, linked as a Backup card with its own account secret | The same account secret, copied to each card in the set |

### Frequently asked questions

**Does a Xaman card have its own r-address?**

Yes. A new card creates its own XRP Ledger account, with its own r-address[^6]. You can also link a card to an account you already have. See [How to link an existing account to a Xaman card](how-to-link-an-existing-account-to-a-xaman-card.md).

**Does a card account need its own reserve?**

Your Primary card's account needs to be activated, like any XRP Ledger account, so it keeps a reserve[^7]. Your Backup card's account does not need activation, since it only signs for your Primary account. See [Activating an account (XRPL)](https://help.xaman.app/app/getting-xrp-into-xaman/how-to-activate-a-new-xrpl-account) and [Reserves on the XRP Ledger](../xrp-ledger-basics/xrp-ledger-concepts/about-reserves.md).

**Can I use a Xaman card like a bank card?**

No. ATMs and payment terminals do not recognize Xaman cards, since the chip only works with apps that support it, such as Xaman. You can pay a business with your card only where it accepts XRP or XRP Ledger tokens, by signing the payment in Xaman.

**Can I use my Tangem card with Xaman?**

Yes, if you have not set it up in the Tangem app yet. Set up the card in Xaman first, as described in [How to import your Xaman card](...a-xaman-tangem-card.md). After that, you can also import it into the Tangem app. If you already set up the card in the Tangem app, you cannot add it to Xaman, and you can keep using it with the Tangem app as usual.

**My card package arrived opened. Is my card still safe to use?**

A new card holds no account secret until you set it up, and Xaman checks every new card the first time you tap it, to confirm it is genuine and has never been used. If Xaman warns that a card was used before, stop. Do not import that card, and contact us through the Xaman Support xApp, the only official way to reach us. [My card package arrived opened](my-card-package-arrived-opened.md) explains what to check.

<a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Open the Xaman Support xApp</a>

### See also

* [Setting up your Xaman cards](getting-started.md)
* [Setting up a Backup card](setting-up-a-backup-card.md)
* [How to link an existing account to a Xaman card](how-to-link-an-existing-account-to-a-xaman-card.md)
* [Best security practices for the Xaman cards](best-security-practices-using-a-xaman-card.md)
* [Lost or damaged cards](lost-or-damaged-cards.md)
* [My card package arrived opened](my-card-package-arrived-opened.md)
* [Get Cards](https://help.xaman.app/app/xaman-cards/get-cards-tangem)

[^1]: The secret that controls your account, as Secret Numbers, a Family Seed, or a Mnemonic. Never share it with anyone.

[^2]: The technology your phone uses for tap-to-pay. Xaman uses it to talk to your Xaman cards.

[^3]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^4]: A second Xaman card linked to your Primary account, so either card can sign for it.

[^5]: A second key that can sign for your account, such as a Backup card.

[^6]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.

[^7]: XRP that every active XRP Ledger account must keep and cannot spend. The network sets the amount, and it can change.
