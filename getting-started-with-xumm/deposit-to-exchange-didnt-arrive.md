---
description: You sent XRP to your exchange account and it did not arrive
---

# Deposit to Exchange Didn’t Arrive

### **General information**

In order to send XRP into an exchange account, you need to know **two** pieces of information:

1. the correct exchange r-address to send the funds to
2. the destination tag for your exchange account

Both of these are provided by **your crypto exchange**.

If you are unsure what a destination tag is, this video should help:

{% content-ref url="../learning-more-about-xumm/destination-tags.md" %}
[destination-tags.md](../learning-more-about-xumm/destination-tags.md)
{% endcontent-ref %}

### **Why a deposit might not arrive**

The main reasons why funds do not arrive are:

* There was **no destination tag** entered in the transaction
* There was **incorrect destination tag** entered in the transaction

You can check this in Xumm under the **Events** section.

<figure><img src="../.gitbook/assets/Events button -1.png" alt=""><figcaption></figcaption></figure>

When you review the transaction, make sure the destination tag was entered **correctly**.

<figure><img src="../.gitbook/assets/Transaction - 1.png" alt=""><figcaption></figcaption></figure>

Again, this is the **number 1 reason** funds are not delivered. People either don’t enter a destination tag or enter a destination tag incorrectly.

If the destination r-address and tag are both correct and the funds still have not arrived in your exchange account, it is most likely:

* your exchange has not processed that transaction on their side
* possible technical issues or a processing backlog at the exchange
* the exchange are holding your funds for KYC/AML reasons.

### **What you can do to retrieve your funds**

Once Xumm submits a transaction to the XRP Ledger (XRPL) for processing, there is nothing that can be done to change or reverse it. This article explains how this works:

* [**Can Xumm reverse, freeze or undo a transaction?**](can-xumm-reverse-freeze-or-undo-a-transaction.md)

All crypto exchanges have a process that needs to be followed in order to investigate a transaction.

Start by **contacting your exchange** and explain what happened. They should provide you with the step by step instructions on how begin the process and what information they require. They will also inform you of any fees that they might charge in order to recover your funds.

(Note: Any fees an exchange charges has nothing to do with Xumm or the the XRP Ledger. Each exchange determines their own service fees.)

To confirm, you should **contact your exchange** and they will work with you to determine what happened to your funds.

### I contacted my exchange and they want me to send them a screenshot of the transaction

Some exchanges demand that you provide proof that the transaction happened.

This demand often includes a screenshot showing:

* &#x20;Destination address
* &#x20;Destination amount
* &#x20;Date&#x20;
* Blockchain transaction ID/Hash

If you are required to provide such information here is how to get it in Xumm.

1\) Launch Xumm, press **Settings** -> **Security** -> **Block taking screenshots**

<figure><img src="../.gitbook/assets/Block taking screenshots.png" alt=""><figcaption></figcaption></figure>

2\) Exit the Settings screen and press the **Events** button on the main screen of Xumm.

<figure><img src="../.gitbook/assets/Events 2.png" alt=""><figcaption><p>Events button</p></figcaption></figure>

3\) The Event list is a live view of the transactions on the XRP Ledger. Search through the list and choose the transaction where you sent the funds to your crypto exchange. It might look something like this:

<figure><img src="../.gitbook/assets/Transaction - 2.png" alt=""><figcaption></figcaption></figure>

&#x20;You can clearly see the date, destination address, Transaction ID, and destination tag in the above image. &#x20;

4\) At this point you can take a screenshot of the transaction as it will contain all of the information your exchange requires.

