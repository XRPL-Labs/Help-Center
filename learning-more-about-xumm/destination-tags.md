---
description: The number that tells an exchange which customer a payment is for
---

# Destination tags

### Background

A destination tag is a number you add to an XRP Ledger (XRPL) payment so the receiver knows who it is for. Think of an apartment building: the r-address[^1] is the street address, and the destination tag is the apartment number. The payment reaches the building either way, but without the apartment number, nobody knows whose door to knock on.

Exchanges and other services that hold funds for many customers often use one shared account for all of them. They give each customer a destination tag, and use it to credit each deposit to the right person. If a deposit arrives without the right tag, the exchange receives your XRP but cannot tell it is yours.

This article explains when you need a destination tag, how to add one in Xaman, and what to do if you forgot it or entered the wrong one.

### When you need a destination tag

**Sending to an exchange or another service that holds funds for you:** yes, almost always. Copy the tag from the exchange's XRP deposit page, exactly as shown. Some exchanges call it a "Tag", a "Memo", or a "Destination Tag", and in Xaman it always goes in the **Destination Tag** field.

**Sending to a self-custody account,** such as another Xaman account or a friend's wallet: usually not. The account belongs to one person, so there is nobody else to tell it apart from. Leave the field empty unless the receiver asked you to use a tag.

**Receiving into your Xaman account:** no. Your Xaman account belongs only to you, so people sending you XRP do not need a tag. If an exchange's withdrawal form will not let you continue without one, contact the exchange's support team before you guess a number.

### How to add a destination tag in Xaman

To send a payment with a destination tag:

1. Tap **Send**. \[VERIFY UI LABEL]
2. Enter or scan the receiver's r-address.
3. Enter the tag in the **Destination Tag** field. \[VERIFY UI LABEL]
4. Enter the amount, then continue to the review screen.
5. Check that the destination tag on the review screen matches the one the exchange gave you, digit for digit.
6. Swipe the **Slide to accept** button to sign the payment.

> **IMAGE PLACEHOLDER**
>
> * **Description:** The Xaman review screen for a payment to an exchange, with the destination tag visible. Use the Stargate account as the sender, and the Default theme.
> * **Caption:** Check the tag here before you slide to accept
> * **Alt text:** The Xaman review screen showing the receiver's address and destination tag

If the exchange shows a QR code on its deposit page, scanning it with Xaman often fills in the address and the tag together. \[Uncertain] Check the review screen either way, since the tag is the part that decides whether your deposit can be credited.

### What the XRP Ledger checks, and what it does not

Some exchanges turn on a setting that makes the XRP Ledger reject payments without a destination tag. If you forget the tag when sending to one of these accounts, the payment fails, nothing is sent, and you can try again with the tag. That is the best possible outcome of a forgotten tag.

The XRP Ledger cannot tell whether a tag is the right one, though. If you enter a wrong tag, or the exchange does not require one and you leave it out, the payment goes through. Your XRP arrives in the exchange's account, but the exchange may not know which customer it belongs to.

{% hint style="warning" %}
A missing or wrong destination tag can leave your deposit uncredited at the exchange. Getting it credited means contacting the exchange's support team, which can take days. Copy the tag exactly from the exchange's deposit page every time you send.
{% endhint %}

### If you forgot the tag or used the wrong one

Do not send the payment again, since a second payment would end up in the same place. Your XRP has almost certainly arrived in the exchange's account, and the exchange is the only one who can credit it to you.

To get your deposit credited:

1. Find the payment in Xaman, and copy its transaction hash (the payment's unique ID). \[VERIFY UI LABEL]
2. Contact the exchange's support team through its official website or app.
3. Give them the transaction hash, the amount, the date and time, and your exchange account details.
4. Ask them to credit the deposit to your account.

Most exchanges can credit a deposit like this once they confirm it is yours, though it can take some time. Xaman cannot reverse the payment or move it for you, since it is already in an account the exchange controls. Be careful of anyone who contacts you offering to recover the deposit for a fee. Only the exchange can credit it. See [Recovery scams](https://help.xaman.app/app/all-about-scams/recovery-scams) \[VERIFY LINK].

### Frequently asked questions

**Does my Xaman account have a destination tag?**

No. Your Xaman account is yours alone, so it does not need one. When you send to your own Xaman account, from an exchange or anywhere else, you can leave the tag empty.

**What is the difference between a destination tag and a memo?**

A destination tag is a number that tells the receiver who a payment is for. A memo is an optional note attached to a payment. Some exchanges label their destination tag "Memo", but in Xaman it still goes in the **Destination Tag** field. A tag entered as a memo will not be read as a destination tag.

**Why can a destination tag only contain numbers?**

On the XRP Ledger, a destination tag is always a whole number, from 0 to 4,294,967,295. Letters are not allowed. If an exchange shows you a tag or memo with letters in it, check that you chose the XRP Ledger network on the exchange's deposit page.

**What is a source tag?**

A source tag works the other way around. It tells the receiver where a payment came from, so they know where to send it back if they return it. Most people never need to enter one.

**What is an X-address?**

An X-address is a longer address that combines an r-address and a destination tag into one. When you send to an X-address, the tag is already included. Some exchanges show X-addresses instead of a separate address and tag.

**Can I reuse a destination tag from an earlier deposit?**

Many exchanges give each customer a tag that never changes, but not all of them do. Copy the address and tag from the exchange's deposit page each time you send, to be sure they are still current.

### Prefer to watch?

This short video explains destination tags in a few minutes.

{% embed url="https://youtu.be/gAWnIw4gzW8?list=PL7cEYW-Kob0p9EcJexpZRc-vY93vnpp_l" %}
Destination tags explained
{% endembed %}

### See also

* [Sending XRP and tokens from Xaman](https://help.xaman.app/app/getting-started-with-xaman/sending-tokens-from-xaman)
* [Deposit to exchange did not arrive](https://help.xaman.app/app/learning-more-about-xaman/deposit-to-exchange-did-not-arrive) \[VERIFY LINK]
* [Can Xaman reverse, freeze or undo a transaction?](https://help.xaman.app/app/all-about-scams/can-xaman-reverse-freeze-or-undo-a-transaction)
* [Recovery scams](https://help.xaman.app/app/all-about-scams/recovery-scams) \[VERIFY LINK]

Also available in this video series:

<table><thead><tr><th width="370">Video</th><th>Description</th></tr></thead><tbody><tr><td><a href="../getting-started-with-xaman/what-is-xaman/">What is Xumm?</a></td><td>Explaining the Xumm app</td></tr><tr><td><a href="../getting-started-with-xaman/what-is-xaman/where-are-your-funds-stored.md">Where are your funds stored?</a></td><td>XRP is on the XRPL, not in Xumm</td></tr><tr><td><a href="../learning-more-about-xaman/how-can-you-access-your-xrpl-account.md">Protecting your account secret</a></td><td>Tips on protecting your secret numbers</td></tr><tr><td><a href="../xrp-ledger-resources/xrp-ledger-concepts/reserves-and-fees-on-the-xrpl.md">Reserves and Fees</a></td><td>Base reserve and XRPL Fees</td></tr></tbody></table>

[^1]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.
