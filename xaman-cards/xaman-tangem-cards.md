---
description: How Xaman cards keep your account secret on a chip, and how to use them
---

# Xaman cards

Xaman cards are NFC cards made by Tangem for use with Xaman. Each card has a secure chip that stores the account secret for an XRP Ledger (XRPL) account. The secret never leaves the chip.

You use a Xaman card together with Xaman on your phone. Xaman shows you each transaction, and the card signs it when you hold it against your phone.

### How a Xaman card works

The cards ship without an account secret. The first time you use a card, its chip creates the secret itself, powered by your phone over NFC. No one handles the secret between the factory and you.

To sign a transaction, you hold the card against your phone. Xaman sends the transaction to the card, the card signs it on the chip, and Xaman sends the signed transaction to the XRP Ledger.

The card can only sign. It cannot show, export, or copy its account secret, so the secret cannot be stolen from your phone.

### When to use a Xaman card

An account secret stored on your phone is convenient for everyday use. For larger amounts, many people prefer to keep the secret away from their phone.

A common setup uses two accounts:

* A spending account in Xaman, for receiving funds and day-to-day transactions.
* A savings account on a Xaman card, for larger amounts.

To top up your spending account, sign a payment from your savings account with your card. When your spending account holds more than you are comfortable with, send some of it to your card account.

Xaman cards work with everything Xaman supports on the XRP Ledger and Xahau, such as tokens, the DEX, escrows, NFTs, and account settings.

### Backup cards

If you lose or damage your only card, you lose access to its account. The account secret cannot be recovered from the chip.

To protect yourself, set up a second card as a backup with the **Tangem Backup** xApp. The backup card can sign for your card account, so you can still reach your funds if the first card is lost, stolen, or damaged. See [_How to configure a backup signing account_](how-to-configure-a-backup-signing-account.md).

{% hint style="warning" %}
Set up a backup card before you send funds to a card account. Without a backup, a lost or damaged card means the funds in its account can no longer be reached.
{% endhint %}

### Get Xaman cards

You can order Xaman cards in the **Get cards** xApp in Xaman, or on [our website](https://xaman.app/cards).

When your cards arrive, see [_Getting started with your new cards_](getting-started.md).

### Xaman cards and Tangem cards

Xaman cards are Tangem cards that XRPL Labs configures for the XRP Ledger and Xahau. You can also use a card bought from Tangem with Xaman, as long as you set it up in Xaman first.

When you set up a card in Xaman, it is prepared to work with Xaman. You can still import it into the Tangem app afterward and use it there too. A card set up in the Tangem app first can no longer be added to Xaman.

{% hint style="warning" %}
Set up a new Tangem card in Xaman before you use it in the Tangem app. If you set it up in the Tangem app first, you cannot add it to Xaman later.
{% endhint %}

|                              | Set up in Xaman first                                                | Set up in the Tangem app first                          |
| ---------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------- |
| Works in Xaman               | Yes                                                                  | No                                                      |
| Works in the Tangem app      | Yes, after you import it                                             | Yes                                                     |
| XRP Ledger features in Xaman | Everything Xaman supports, including tokens, escrows, and NFTs       | None                                                    |
| Backup                       | A second card, set up as a backup signer with its own account secret | The same account secret, copied to each card in the set |

For questions about using a card in the Tangem app, contact Tangem support.

### Frequently asked questions

**Does a Xaman card have its own r-address?**

Yes. A new card creates its own XRP Ledger account, with its own r-address. You can also link a card to an account you already have. See [_How to link an existing account to a Xaman card_](how-to-link-an-existing-account-to-a-xaman-card.md).

**Does a card account need its own reserve?**

A card's own account needs to be activated, like any XRP Ledger account, so it needs a base reserve. A backup card does not need activation, because it only signs for your card account. See [_Activating an account_](../getting-xrp-into-xaman/how-to-activate-a-new-xrpl-account/).

**Can I copy or back up the account secret on a card?**

No. The chip never reveals the account secret. To protect against losing a card, set up a backup card instead.

**Can I use a Xaman card at an ATM or a payment terminal?**

No. ATMs and payment terminals do not recognize Xaman cards. The chip only works with apps that support the cards, such as Xaman.

**Can I use a Xaman card to pay in a store or online?**

Only where the business accepts XRP or XRP Ledger tokens. If it does, you can sign the payment with your card in Xaman.

**Can I use my Tangem card with Xaman?**

Yes, if you have not set it up in the Tangem app yet. Set up the card in Xaman first. See [_How to import your Xaman card_.](../your-account/importing-your-account/...a-xaman-tangem-card.md) After that, you can also import the card into the Tangem app and use it there.

If you already set up the card in the Tangem app, you cannot add it to Xaman. You can keep using it with the Tangem app as usual.

### See also

* [Getting started with your new cards](getting-started.md)
* [How to configure a backup signing account](how-to-configure-a-backup-signing-account.md)
* [How to link an existing account to a Xaman card](how-to-link-an-existing-account-to-a-xaman-card.md)
* [Best security practices for the Xaman cards](best-security-practices-using-a-xaman-card.md)
* [Lost or damaged cards](lost-or-damaged-cards.md)
