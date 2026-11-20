---
description: What to do if you lose or damage a Xaman card
hidden: true
noIndex: true
---

# Lost or damaged cards

### Background

Each Xaman card creates its account secret on the card itself, and the secret never leaves it. No one else can know it, including us. That is what makes your cards so secure, but it also means there is no recovery option: if a card is lost, damaged, or stolen, the account secret on it is gone. Xaman is a self-custody wallet, so we cannot recover a lost card, freeze an account, or reverse a transaction for you.

That is why every order includes at least two cards. When you link a second card to your Primary account as a Backup card, you can still reach your funds if something happens to one of them. This article explains what to do in each case, step by step. These steps are for accounts on the XRP Ledger (XRPL).

### How your Backup card protects you

When you set up your cards, Xaman links your Backup card to your Primary account. It uses the XRP Ledger's regular key feature, which lets a second key sign transactions for an account. After the link, either card can sign for your Primary account, so losing one card does not lock you out.

If you have not linked a Backup card yet, do it now, before anything happens to your Primary card. Open your Primary account in Xaman and tap **No back-up card configured**. For the full walkthrough, see Setting up a Backup card.

{% hint style="info" %}
**Write down your Primary account's r-address** and keep it somewhere safe. If you ever lose your phone and your Primary card at the same time, you need it to reach your account with your Backup card.
{% endhint %}

### If you lose your Primary card

If your Primary card is lost, damaged, or destroyed, or it may have been stolen, use your Backup card to move your funds to another account. Your Backup card can sign for your Primary account, so your funds are still within reach.

{% hint style="warning" %}
**If your Primary card may have been stolen, move your funds as soon as possible.** Anyone holding your Primary card can sign for your Primary account and send your funds away. Follow the steps below right now, before anything else.
{% endhint %}

To move your funds with your Backup card:

1. Open Xaman, and select your Primary card account.
2. Send your XRP and any other assets to another account you control.
3. Sign each transaction with your Backup card.

If you do not have another account yet, see How to create an XRP Ledger account. A new pair of Xaman cards works well here too.

Once your funds are safe, you can delete the old Primary account to get back most of its reserve, signing with your Backup card. See How to delete an XRPL account.

### If you lose your Backup card

If your Backup card is lost, damaged, or destroyed, or it may have been stolen, use your Primary card to remove its link. After that, the Backup card can no longer sign for your Primary account, even if someone else has it. Your Primary card still controls everything.

{% hint style="warning" %}
**If your Backup card may have been stolen, remove its link as soon as possible.** Until you do, anyone holding your Backup card can sign for your Primary account. Follow the steps below right now, before anything else.
{% endhint %}

To remove the link to your Backup card: \[Uncertain]

1. On a phone or computer, go to [XRP Ledger Services](https://xrpl.services/).
2. Tap or click **Sign in**.
3. Sign in with Xaman, using your Primary card account.
4. Choose **Set Regular Key**.
5. Select **Delete regular key**.
6. Tap or click **Confirm**, then scan the QR code with Xaman.
7. Sign the transaction with your Primary card.

Once the link is removed, your Primary account shows the **No back-up card configured** reminder again. \[Inferred] If you have a spare card, tap the reminder to link it as your new Backup card. See Setting up a Backup card.

### Frequently asked questions

**What if I lose my phone and my Primary card at the same time?**

You can still reach your account with your Backup card. This is where the r-address you wrote down comes in.

1. Install Xaman on your new phone.
2. Import your Backup card. See How to import your Xaman card.
3. Add your Primary account in **Read only** mode by entering its r-address. See How to import an account in Read Only mode.
4. Send your funds from the Primary account to another account you control.
5. Sign each transaction with your Backup card.

**What if I lose my phone but still have both cards?**

Your cards are safe, and so are your accounts. Install Xaman on your new phone and import both cards again. Your Backup card link is stored on the XRP Ledger, not on your phone, so it still works. See Moving Xaman to a new phone.

**My card is damaged, but it still works sometimes. What should I do?**

Treat it as a lost card while you can still use it. If it is your Primary card, move your funds to another account now. If it is your Backup card, remove its link. Do not wait for the card to stop working completely.

**What if I lose both cards?**

We are truly sorry, but there is no way to recover an account if both cards are lost. Neither we nor anyone else can reach the account secret on a card. This is why it matters so much to keep your two cards in different places, so a single fire, theft, or lost bag cannot take both. See Best security practices for the Xaman cards.

If you have other questions about a lost or damaged card, contact us through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md).

### See also

* Setting up a Backup card
* _Setting up your Xaman cards_ \[VERIFY LINK]
* Best security practices for the Xaman cards
* Moving Xaman to a new phone
* How to delete an XRPL account
