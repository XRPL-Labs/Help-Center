---
description: You sent XRP to your exchange account and it did not arrive
---

# Deposit to Exchange Didn’t Arrive

{% hint style="info" %}
TL;DR\
\
Contact your crypto exchange. They will be able to resolve this for you.
{% endhint %}

### **General information**

In order to send XRP into an exchange account, you need to know **two** pieces of information:

1. the correct exchange r-address to send the funds to
2. the destination tag for your exchange account

Both of these are provided by **your crypto exchange**.

For more information about destination tags, check out this video:

{% content-ref url="../learning-more-about-xaman/destination-tags.md" %}
[destination-tags.md](../learning-more-about-xaman/destination-tags.md)
{% endcontent-ref %}

### **Why a deposit might not arrive**

The main reasons why funds do not arrive are:

* There was **no destination tag** entered in the transaction
* There was an **incorrect destination tag** entered in the transaction

You can check this in Xumm under the **Events** section.

<figure><img src="../.gitbook/assets/Events button -1.png" alt=""><figcaption></figcaption></figure>

When you review the transaction, make sure the destination tag was entered **correctly**.

<figure><img src="../.gitbook/assets/Transaction - 1.png" alt=""><figcaption></figcaption></figure>

If both the destination r-address and destination tag are both correct and the funds still have not arrived in your exchange account, it is most likely related to one of the following situations:

* your exchange has not processed that transaction on their side
* possible technical issues or a processing backlog at the exchange
* the exchange are withholding your funds.

### **What you can do to retrieve your funds**

They only way to recover your funds is to contact your crypto exchange.

They will have process for you to follow and should provide you with the step by step instructions.

### Frequently asked questions

#### I contacted my exchange and they want me to send them a screenshot of the transaction

Some exchanges require proof of a transaction which includes a screenshot showing:

* &#x20;the destination address
* &#x20;the destination amount
* &#x20;the date&#x20;
* the transaction ID/Hash

If you are required to provide this information, here is how to get it in Xumm.

1\) Launch Xumm, press **Settings** -> **Security** -> **Block taking screenshots**

<figure><img src="../.gitbook/assets/Block taking screenshots.png" alt=""><figcaption></figcaption></figure>

2\) Exit the Settings screen and press the **Events** button on the main screen of Xumm.

<figure><img src="../.gitbook/assets/Events 2.png" alt=""><figcaption><p>Events button</p></figcaption></figure>

3\) The Event list is a live view of the transactions on the XRP Ledger. Search through the list and choose the transaction where you sent the funds to your crypto exchange. It might look something like this:

<figure><img src="../.gitbook/assets/Transaction - 2.png" alt=""><figcaption></figcaption></figure>

You can clearly see the date, destination address, Transaction ID, and destination tag in the above image. &#x20;

4\) At this point you can take a screenshot of the transaction as it will contain all of the information your exchange requires.

#### Can't Xumm just reverse the transaction for me?

Once Xumm submits a transaction to the XRP Ledger for processing, there is nothing that can be done to change or reverse it. For more information about this, check out this article:

* [**Can Xumm reverse, freeze or undo a transaction?**](can-xumm-reverse-freeze-or-undo-a-transaction.md)

