---
description: What to do if you lose or damage a card?
---

# Lost or damaged cards

### Introduction

One of the great features of a Xaman card is that it generates a new XRP Ledger account secret directly on each card. Since this is done "off line", there is no way for anyone to know the account secret which means that the only way to access the card account is if you have the physical card. You must have the card otherwise there is no way to access the account.

So what happens if you lose the card, or if the card is damaged, destroyed or stolen?

If any of these options happened, you would lose access to your account since the only way to access a card account is with the card and there is no recovery option.

This is why we don't offer the option to purchase single cards. We want people to configure a second card as a backup to the first card so if something happens to one of the cards, you still have a way to access the funds in your account.

### Ideal configuration

The ideal way to configure the cards is to import both cards in Xaman, then run the Tangem Backup xApp to "link" the cards together. Doing this will take advantage of the "regular key" feature on the XRP Ledger which allows you to assign as second key pair to sign transactions on an account. This effectively allows one card to sign transactions on another card's account, basically allowing one card to act as a backup to another one. If one card is damaged or lost or destroyed, you can just use the other card to sign transactions on the account.&#x20;

### Losing the Primary card

If you have already followed the instructions in this article:

{% content-ref url="how-to-configure-a-backup-signing-account.md" %}
[how-to-configure-a-backup-signing-account.md](how-to-configure-a-backup-signing-account.md)
{% endcontent-ref %}

you have already created a Primary card account and a Backup card account and linked them together.

If the Primary card is lost, damaged or destroyed or there is a possibility that it has been stolen,  here is what to do.

1\) Sign into Xaman and move the funds from the Primary card account to another XRP Ledger account. (You will need the Backup card to sign transactions on the Primary card's account.)

If you don't have another XRPL account, you can follow the instructions in this article to create one:

{% content-ref url="../getting-started-with-xaman/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md" %}
[how-to-create-an-xrpl-account.md](../getting-started-with-xaman/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
{% endcontent-ref %}

### Losing the Backup card

If the Backup card is lost, damaged or destroyed or there is a possibility that it has been stolen,  here is what to do.

1\) Disable the Backup card by going to [https://xrpl.services/](https://xrpl.services/)

2\) Sign in using the Primary card account.

3\) Choose **Set regular key**

4\) Select **Delete regular key**

5\) Press **Confirm**.

6\) Scan the QR code with Xaman.

7\) Sign the transaction using the Primary card.

This will disable the link between your Primary card and your Backup card.

If your Backup card was stolen, the thief will not be able to access your Primary card account after following this procedure.

### Frequently Asked Questions

#### What if I lose my phone and my Primary card at the same time?

1\) On your new phone, install Xaman.

2\) Import your Backup card into Xaman.

{% content-ref url="../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md" %}
[...a-xumm-tangem-card.md](../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md)
{% endcontent-ref %}

3\) Import your Primary card account into Xaman in Read only mode.

{% content-ref url="../getting-started-with-xaman/importing-your-account/...in-read-only-mode.md" %}
[...in-read-only-mode.md](../getting-started-with-xaman/importing-your-account/...in-read-only-mode.md)
{% endcontent-ref %}

Note: You will need to manually enter the r-address of your Primary card account when importing in read only mode.

4\) Move your funds from the Primary card account to another XRP Ledger account. (You will need the Backup card to sign transactions on the Primary card's account.)

If you don't have another XRPL account, you can follow the instructions in this article to create one:

{% content-ref url="../getting-started-with-xaman/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md" %}
[how-to-create-an-xrpl-account.md](../getting-started-with-xaman/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
{% endcontent-ref %}

