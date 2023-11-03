---
description: What to do if you lose or damage a card?
---

# Lost or damaged cards

### Introduction

One of the great features of a Xumm (Tangem) card is that they generate a new XRP Ledger account secret directly on each card. Since this is done "off line", there is no way for anyone to know the account secret which means that the only way to access the card account is if you have the physical card. You must have the card otherwise there is no way to access the account.

So what happens if you lose the card, or if the card is damaged, destroyed or stolen?

If any of these options happened, you would lose access to your account. The only way to access a card account is with the card. There is no recovery option.

This is why we always ship two cards with every Xumm Pro order and don't offer the option to purchase single cards. We want people to configure a second card as a backup to the first card so it something happens to one of the cards, you still have a way to access the funds in your account.

### Ideal configuration

The ideal way to configure the cards is to import both cards in Xumm, then run the Tangem Backup xApp to "link" the cards together. Doing this will take advantage of the "regular key" feature on the XRP Ledger which allows you to assign as second key pair to sign an account. This effectively allows one card to sign transactions on another card's account, basically allowing one card to act as a backup to another one. If one card is damaged or lost or destroyed, you can just use the other card to sign transactions on the account.&#x20;

### Losing the Primary card

If you have already followed the instructions in this article:

{% content-ref url="how-to-configure-a-backup-signing-account.md" %}
[how-to-configure-a-backup-signing-account.md](how-to-configure-a-backup-signing-account.md)
{% endcontent-ref %}

you have already created a Primary card account and a Backup card account and link them together.

If the Primary card is lost, damaged or destroyed or there is a possibility that it has been stolen,  here is what to do.

1\) Sign into Xumm and move the funds from the Primary card account to another XRP Ledger account. (You will need the Backup card to sign transactions on the Primary card's account.)

If you don't have another XRPL account, you can follow the instructions in this article to create one:

{% content-ref url="../getting-started-with-xumm/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md" %}
[how-to-create-an-xrpl-account.md](../getting-started-with-xumm/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
{% endcontent-ref %}

### Losing the Backup card

If the Backup card is lost, damaged or destroyed or there is a possibility that it has been stolen,  here is what to do.

1\) Disable the Backup card by going to&#x20;
