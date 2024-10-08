---
description: Re-keying an existing account to a Xaman card
---

# How to link an existing account to a Xaman card

### Why would I want to do this? <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

Most people who purchase the cards already have an existing XRP Ledger account, sod when they get their new cards, they want to 'link' them to their existing account. The idea is that the cards will either be a 'backup' to their existing account(s) or that the cards should work together with their existing accounts.

While it is easy to configure the cards this way, you should consider how you plan to manage your XRP Ledger accounts and why you purchased the cards.

### Xaman card (Hardware wallet) vs Xaman (Software wallet)

Xaman cards are hardware wallets and hardware wallets are largely about **long term storage** of your assets.&#x20;

A hardware wallet stores the private keys for an XRP Ledger account on a device that is not connected to the internet and transactions can only be signed on the XRPL account if the signer is in possession of the hardware device. Storing private keys 'offline' limits some potential attack vectors on an XRPL account.

Xaman is a software wallet and is largely about enabling **interaction** with the XRP Ledger ecosystem.

Xaman stores the private keys for an XRP Ledger account on a mobile device. (Which is presumably connected to the internet at various times.) It allows a user to sign transactions on their XRPL account via their phone. By storing private keys on a device that is 'on line', it exposes an account to other types of potential attack vectors.&#x20;

### How are you planning to interact with the XRPL ecosystem? <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

If you are going to use the cards as a 'savings' account, where you plan to store your XRP and wait for the price to go up, we recommend that you create a 'primary' card account and configure a 'backup' card account. By doing this, you take advantage of the cards features. (Creating and storing the account secret off line.) Configuring the cards this way, does not involve an existing account.

If you plan to be **active in the XRPL community**, and want to use the cards with an existing XRPL account, you should consider that if you configure an existing account as a backup to a card account, you are **adding an additional attack vector** to the card account. If your existing account was ever comprised, some could access you card account.  (Configuring a card as a backup to an existing account is ok though.)

As long as you are aware of the potential risk, here are the instructions.

### How to configure a card to sign on an existing account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

#### Step 1: Make sure you have a existing XRP Ledger account (Primary account)

The existing account must be imported into Xaman with **Full access** and you must be able to sign transactions on this account. (This is your XRPL account that contains your XRP, your Trust Lines, Escrows, DEX transactions, etc.)

#### Step 2: Import your new Xaman card into Xaman <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Import your card into Xaman by following these instructions:

{% content-ref url="../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md" %}
[...a-xumm-tangem-card.md](../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md)
{% endcontent-ref %}

#### Step 3: Copy the r-address for your card <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

After you have imported your Xumm card, press the **Request** button then press the **Copy** button:

<figure><img src="../.gitbook/assets/regular keys -3.png" alt=""><figcaption></figcaption></figure>

then switch accounts to your **Primary** account (your existing account) in Xaman and press [<mark style="color:blue;">**here**</mark>](https://xrpl.services/) to go to [**XRP Ledger Services**](https://xrpl.services/)**.**

#### Step 4: Sign into XRPL.Services with your existing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Press the ![](<../.gitbook/assets/image (1) (6).png>) button then press **Open in Xumm App** and sign in.

<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>

#### Step 5: Set the Regular Key for your existing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

On the XRP Ledger Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/XRPL Services - Reg Key - 1.png" alt=""><figcaption></figcaption></figure>

Paste the r-address for your new Xumm card in the field titled, "XRPL address which will be able to sign transactions", then press the **Send Set Regular Key to Xumm** button.

<figure><img src="../.gitbook/assets/XRPL - Regular keys.png" alt=""><figcaption></figcaption></figure>

#### Step 6: Sign the transaction with your existing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Sign the transaction in Xumm and you're all done!&#x20;

### How to configure an existing account to sign on a card account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

#### Step 1: Import your new Xumm card into Xaman <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

Follow these instructions to do this:

{% content-ref url="../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md" %}
[...a-xumm-tangem-card.md](../getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md)
{% endcontent-ref %}

#### Step 2: Activate your new card account with at least 10 XRP <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

In order to hold assets in a XRP Ledger account, it must first be activated with at least 10 XRP.

This article explains how to activate an XRPL account:

{% content-ref url="../getting-started-with-xaman/how-to-activate-a-new-xrpl-account/" %}
[how-to-activate-a-new-xrpl-account](../getting-started-with-xaman/how-to-activate-a-new-xrpl-account/)
{% endcontent-ref %}

#### Step 3: Copy the r-address for your existing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Switch accounts to your existing XRPL account and press the **Request** button then press the **Copy** button:

<figure><img src="../.gitbook/assets/regular keys -3.png" alt=""><figcaption></figcaption></figure>

then switch accounts to your **Xumm card account** and press [<mark style="color:blue;">**here**</mark>](https://xrpl.services/) to go to [**XRP Ledger Services**](https://xrpl.services/)**.**

#### Step 4: Sign into XRPL.Services with your Xumm card <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Press the ![](<../.gitbook/assets/image (1) (6).png>) button then press **Open in Xumm App** and sign in.

<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>

#### Step 5: Set the Regular Key for your Xumm card account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

On the XRP Ledger Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/XRPL Services - Reg Key - 1.png" alt=""><figcaption></figcaption></figure>

Paste the r-address for your existing account into the field titled, "XRPL address which will be able to sign transactions", then press the **Send Set Regular Key to Xumm** button.

<figure><img src="../.gitbook/assets/XRPL - Regular keys.png" alt=""><figcaption></figcaption></figure>

#### Step 6: Sign the transaction with your Xumm card <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Sign the transaction with your Xumm card and you're all done!

## _Frequently asked Questions_

### What is the recommended way to configure my Xumm cards?

The recommended and ideal way to configure a card is to have **two cards**, then "link" them together using the Tangem Backup xApp. This is explained in this article:

{% content-ref url="getting-started.md" %}
[getting-started.md](getting-started.md)
{% endcontent-ref %}

### I only have one card though...

Each card will generate and store an XRP Ledger account secret on the card.

The account secret **can not** be viewed or extracted from the card and anytime you want to sign transaction on the card's account, you must have the card with you.

This is a great security feature but since the account secret only exists in one place, (on the card) what would happen if you lost or damaged the card? (You would lose access to your funds!)

This is why we only sell a minimum of two cards. With two Xumm cards, you can create a backup card which allows you to access your funds in case one of them is ever lost or damaged.

If you only have one card, "linking" an existing account to it allows your existing account to act as a backup in case something happens to the card.



