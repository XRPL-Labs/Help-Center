---
description: Re-keying a card account to another XRPL account
---

# How to link a Xumm card to an existing XRPL account

### Linking the cards to an existing account

This process will allow you sign transactions on an existing XRP Ledger account with your new Xumm card.

#### Step 1: Make sure you have a Primary account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

The Primary account must be imported into Xumm with **Full access**. (You must be able to sign transactions on this account.)

This is your existing account that will have your XRP, your Trust Lines, Escrows, DEX transactions, etc.

#### Step 2: Import your new Xumm card into Xumm <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Import you card into Xumm by following the these instructions:

{% content-ref url="../getting-started-with-xumm/importing-your-account/...a-xumm-tangem-card.md" %}
[...a-xumm-tangem-card.md](../getting-started-with-xumm/importing-your-account/...a-xumm-tangem-card.md)
{% endcontent-ref %}

#### Step 3: Copy the r-address for your card <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

After you have imported your Xumm card, press  the **Request** button then press the **Copy** button.

<figure><img src="../.gitbook/assets/regular keys -3.png" alt=""><figcaption></figcaption></figure>

then switch accounts to your **Primary** account (your existing account) in Xumm and press [<mark style="color:blue;">**here**</mark>](https://xrpl.services/) to go to [**XRP Ledger Services**](https://xrpl.services/)**.**

#### Step 4: Sign into XRPL.Services with your existing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Press the ![](<../.gitbook/assets/image (1) (6).png>) button then press **Open in Xumm App** and sign in.

<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>

5\) On the XRP Ledger Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/XRPL Services - Reg Key - 1.png" alt=""><figcaption></figcaption></figure>

6\) In the field below paste the r-address for the Signing account, then press the **Send Set Regular Key to Xumm** button.

<figure><img src="../.gitbook/assets/XRPL - Regular keys.png" alt=""><figcaption></figcaption></figure>

7\) Sign the transaction in Xumm and you're all done!&#x20;

Now when you look at your Signing account, notice how Xumm now reports "Regular key for Primary Acct".

<figure><img src="../.gitbook/assets/regular keys -4.png" alt=""><figcaption></figcaption></figure>

### Next steps..



Most people will already have an existing XRP Ledger account and may be interested in only using th be sure how to integrate their existing accounts with their new Xumm cards. While this is possible to integrate the cards with existing accounts, it is not advised. Integrating hardware wallet accounts and software wallet accounts is not ideal.

For more information about this, please refer to this article:



The recommended and ideal way to configure a card is to have **two cards**, then "link" them together using the Tangem Backup xApp.

This configuration &#x20;

* You can setup a Xumm card a backup to an existing account, making an existing card a backup to an Xumm card account, managing multiple Xumm card accounts alongside multiple regular accounts or configuring multiple accounts using the multi-sign feature of the XRPL. Each of these options have their pros and cons, but for most people, the above two options will be the better solutions.



intention is to&#x20;

Most people who get the Xumm (Tangem) cards will already have an existing XRP Ledger account.

When you subscribed to Xumm Pro, you receive two cards. The reason for this&#x20;



### Introduction

In an ideal situation, the cards will be configured in the following way:

1\) Import two Xumm cards into Xumm.

2\) Activate one of the cards (the Primary card) and leave the other one un-activated. (The Backup card)

3\) Run the Tangem Backup xApp and link the two cards together.

See this article for complete instructions:

{% content-ref url="getting-started.md" %}
[getting-started.md](getting-started.md)
{% endcontent-ref %}

By configuring the cards this way, you ensure that any funds stored on the Primary card account will not be lost in case the one of the cards is damaged or destroyed.

