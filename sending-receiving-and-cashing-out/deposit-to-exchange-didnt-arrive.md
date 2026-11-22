---
description: >-
  What to do when XRP you sent to an exchange does not appear in your exchange
  account
---

# Deposit to exchange did not arrive

### Background

To deposit XRP to an exchange, you send it to the exchange's deposit address on the XRP Ledger (XRPL). Most exchanges also give you a destination tag, a number that identifies your account at the exchange.

Think of the deposit address as an apartment building, and the destination tag as your apartment number. The address gets the XRP to the exchange, and the tag tells the exchange which account to credit.

When a deposit does not arrive, the XRP is usually not lost. Either the payment did not go through, or the exchange has the XRP and has not credited it to your account yet.

### Check that the payment succeeded

Start by checking whether the payment completed on the XRP Ledger.

1. Tap **Events**.
2. Tap the payment you sent to the exchange.
3. Check the status of the transaction.

If the payment failed, the XRP never left your account. Only the network fee was charged. Many exchanges reject payments without a destination tag, so a missing tag is a common reason. Check your exchange's deposit details and send the payment again.

If the payment succeeded, the XRP reached the exchange's address. Continue with the next section.

### Why a successful deposit was not credited

| Cause                     | What happened                                                                       | What to do                                                                                                                 |
| ------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| No destination tag        | The exchange received the XRP, but does not know which account to credit.           | Contact exchange support with your transaction ID.                                                                         |
| Wrong destination tag     | The exchange received the XRP, but credited it to another account or to no account. | Contact exchange support with your transaction ID.                                                                         |
| Below the minimum deposit | The exchange does not credit deposits under its minimum amount.                     | Check the exchange's deposit rules, then contact exchange support.                                                         |
| Deposits paused           | The exchange has paused XRP deposits, for example for maintenance.                  | Check the exchange's status page or announcements. If the deposit is still missing after deposits resume, contact support. |
| Processing delay          | The exchange has not processed the deposit yet. Processing times vary by exchange.  | Check the exchange's status page and wait.                                                                                 |
| Account or security hold  | The exchange is holding the deposit for its own checks.                             | Check your email and the exchange's notifications for verification requests.                                               |

### Contact your exchange

The XRP is at the exchange's address, so only the exchange can credit it to your account. When you contact exchange support, have these details ready:

* The date and time of the payment.
* The amount of XRP you sent.
* The transaction ID.
* The destination tag you entered, or a note that you left it blank.

{% hint style="info" %}
Each exchange has its own rules for missing or mis-tagged deposits. Some credit the deposit for free, some charge a recovery fee, and some do not recover deposits at all. Xaman has no control over these rules.
{% endhint %}

### Find the transaction details in Xaman

1. Tap **Events**.
2. Tap the payment you sent to the exchange.
3. Find the date, amount, and destination tag on the transaction details screen.
4. Tap and hold the transaction ID, then tap **Copy**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FjsgHaR5Kd4SbykRSIRgG%2Ftransaction-details-arrows.png?alt=media&#x26;token=bee20c88-150f-4f31-bb8c-b186a53a5022" alt="Xaman transaction details screen, with arrows pointing to the date, amount, destination tag and transaction ID." width="375"><figcaption><p>Transaction details screen</p></figcaption></figure>

### Take a screenshot of the transaction

Many exchanges ask for a screenshot of the payment. Xaman blocks screenshots by default to protect your privacy.

1. Go to **Settings** > **Security**.
2. Turn off **Block taking screenshots**.
3. Tap **Events**, open the payment, and take your screenshot.
4. Go back to **Settings** > **Security** and turn on **Block taking screenshots**.

### Frequently asked questions

**Can Xaman reverse the transaction?**

No. A confirmed transaction on the XRP Ledger is final, and no one can reverse it, including the Xaman team. Only the exchange that received the XRP can credit or return it. See _Can Xaman reverse, freeze or undo a transaction?_

**Are my funds gone if I forgot the destination tag?**

Not necessarily. First check that the payment succeeded. If it failed, the XRP is still in your account. If it succeeded, the exchange has the XRP, and exchange support can tell you whether it can credit it.

**What if my wrong tag belonged to another customer?**

The exchange may have credited the XRP to that customer's account. Exchanges usually cannot take it back. Ask support whether it will contact the customer and ask for a voluntary return.

**What if the exchange charges a fee to recover my deposit?**

Some exchanges charge a recovery fee, or only recover deposits above a minimum amount. Some only return the XRP to the address it came from. Check whether the exchange has a deposit recovery form, and ask support about its process.

If you sent the XRP from another exchange, the return goes back to that exchange. Contact both exchanges so they can match the payment.

**What if support says the transaction cannot be reversed?**

Explain that you are not asking for a reversal. The payment succeeded and the XRP is at the exchange's address. Ask to escalate the ticket, and include the transaction ID, the date and time, the amount, and a screenshot.

**What if the exchange still does not credit my deposit?**

If the exchange is regulated where you live, you can use its formal complaints process. Some countries also have an ombudsman or regulator you can contact after that.

**What if I sent the XRP to the wrong address?**

An exchange can only help with its own addresses. If the address does not belong to the exchange, only the owner of that address can return the XRP.

You can try to contact the owner with a message on the XRP Ledger:

1. Send a very small payment, such as 0.000001 XRP, to the same address.
2. On the **Summary** screen, write a short message in the **Memo** field. Explain the mistake, include your r-address, and ask for the XRP back.

{% hint style="warning" %}
The owner may never read the message, and does not have to return the XRP.
{% endhint %}

{% hint style="danger" %}
Memos are public, so scammers can see your message. Anyone who offers to recover your XRP for a fee is a scammer. Xaman Support will never ask for your account secret.
{% endhint %}

### See also

* [Sending XRP and tokens from Xaman](sending-tokens-from-xaman.md)
* [Can Xaman reverse, freeze or undo a transaction?](can-xaman-reverse-freeze-or-undo-a-transaction.md)
