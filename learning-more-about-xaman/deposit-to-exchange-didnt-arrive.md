---
description: >-
  Sent XRP to an exchange and don't see it in your account? Don't panic. In most
  cases, the funds are not lost. They just need to be located.
---

# Deposit to exchange did not arrive

#### What You Need to Send XRP to an Exchange

To deposit XRP into an exchange, you need the exchange’s **deposit address** (starts with an `r`), and, if the exchange gives you one, your **destination tag**: a number that identifies your exchange account.

_(Think of the exchange's r-address as an apartment building, and your destination tag as your specific apartment number.)_

#### Why the Deposit Hasn't Arrived

| **Reason**                    | **What happened**                                                                              | **What you should do**                                                               |
| ----------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Missing Destination Tag**   | The exchange received the XRP, but doesn't know which account to credit.                       | Contact exchange support with your Transaction ID so they can trace the transaction. |
| **Incorrect Destination Tag** | The exchange received the XRP, but it credited the XRP to the wrong account.                   | Contact exchange support with your Transaction ID so they can trace the transaction. |
| **Exchange Processing Delay** | The XRP Ledger finished the transaction, but the exchange has a queue or maintenance backlog.  | Check the exchange's system status page. Usually, these clear within a few hours.    |
| **Account or Security Hold**  | The exchange received the deposit, but has temporarily held it for internal compliance checks. | Check your email or exchange notification center for any verification requests.      |

#### How to Recover Your Funds

1. **Contact your exchange’s customer support team**

Since the transfer has already completed on the XRP Ledger and arrived at the exchange’s main address, only the receiving exchange has access to the funds and the ability to credit your account.

{% hint style="info" %}
A quick note on exchange policies:

Every crypto exchange has its own internal rules for dealing with missing or mistagged deposits:

* Some exchanges will locate and credit your deposit for free.
* Some charge a manual recovery fee to locate and process the funds.
* Some exchanges have strict policies refusing to recover missing deposits altogether.

These policies, fees, and processing times are determined solely by the exchange. Xaman is a self-custodial wallet interface and has no control over how third-party exchanges handle incoming transfers.&#x20;
{% endhint %}

2. **Details you will need to provide**

When opening a ticket with your exchange's support team, have the following details ready:

* **Date & Time** of the transaction
* **Amount** of XRP sent
* **Transaction ID**: The unique blockchain receipt proving the transfer settled on the XRP Ledger
* **Destination Tag** entered: The number you typed in (or state clearly that you left it blank)



3. **How to find this information in Xaman**

&#x20;You can locate the details the exchange needs directly in your transaction history:

1. Open Xaman and tap the **Events** tab on the home screen.
2. Scroll to and tap the specific transfer you sent to the exchange.
3. On the transaction details screen, you will see the Date, Amount, and Destination Tag (if one was included).
4. Locate the Transaction ID and tap and hold it, then tap the "Copy" button to copy it directly to your clipboard.

<figure><img src="../.gitbook/assets/transaction-details-arrows.png" alt="Xaman transaction details screen, with arrows pointing to the date, amount, destination tag and transaction ID." width="375"><figcaption><p>Transaction details screen</p></figcaption></figure>

4. **Need to send a screenshot as proof?**

Many exchanges ask for a visual screenshot of the transaction. For your privacy and security, Xaman blocks screenshots by default. To capture one:

1. Go to Settings > Security.
2. Toggle off "Block taking screenshots".
3. Return to the Events tab, reopen the transaction details, and take your screenshot.
4. _(Recommended)_ Return to Settings > Security and turn the screenshot block back on when you're done.

#### Frequently asked questions

#### Can Xaman reverse the transaction for me?

No. Xaman sends your transaction directly to the XRP Ledger. A confirmed transaction on the XRP Ledger is final. No one, including the Xaman team, can freeze, reverse, or undo it. Only the exchange that received the funds can return or re-route them. See [Can Xaman reverse, freeze or undo a transaction?](https://help.xaman.app/app/all-about-scams/can-xumm-reverse-freeze-or-undo-a-transaction).

#### Are my funds gone if I forgot the destination tag?

Not necessarily. If you sent the transfer to the correct deposit address, the exchange received the XRP on the XRP Ledger. Whether those funds can be credited to your account depends entirely on your exchange.\
\
Contact your exchange’s customer support team directly and explain what happened (that the transfer was sent without the tag). They will explain their specific policies, outline your available options, and let you know if there are any verification requirements or recovery fees.

#### What if I sent the XRP to the wrong address (not just the wrong tag)?

An exchange only controls its own XRP Ledger addresses. If you sent the transfer to an incorrect r-address that does not belong to the exchange, their support team will not be able to help you access your funds.

Since XRP Ledger transactions are permanent and irreversible, funds sent to an unintended wallet can only be recovered if the wallet owner chooses to return them voluntarily.

**What you can try**

You can attempt to contact the wallet owner by sending an on-chain message directly to that address:

1. Send a micro-payment: Initiate a transfer in Xaman to the same address for a fraction of a cent (e.g., `0.000001 XRP`).
2. Add a Memo: Tap Add memo before signing. Write a short, polite message explaining the accidental transfer, include your own Xaman r-address, and kindly ask them to return the funds.

{% hint style="warning" %}
Important: This is simply an on-ledger messaging attempt. There is no guarantee the recipient will check incoming transaction memos, and they are under no technical obligation to return the funds.
{% endhint %}

{% hint style="danger" %}
**Be careful:** memos are public. Anyone who contacts you offering to recover your funds for a fee is a scammer. Xaman Support will never ask for your account secret.
{% endhint %}
