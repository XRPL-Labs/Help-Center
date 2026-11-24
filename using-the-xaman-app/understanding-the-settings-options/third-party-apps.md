---
description: >-
  What the Third party apps list in Settings shows, and how to revoke an app's
  access
---

# Third party apps

xApps are small apps that run inside Xaman, built by Xaman and by independent developers. Some of them ask to know your r-address[^1], so they can show your NFTs or fill in forms for you without you typing it every time. Xaman asks for your approval first, and every app you approve appears in **Settings** > **Third party apps**. This article explains what an approved app can and cannot do, how to read its details, and how to take its access away. The list is part of Xaman itself, so it works the same whichever network you use.

### What an approved app can do

When you approve an xApp, you give it exactly two things:

* **Your r-address.** The app can see the public address of the account you use with it. Your r-address is already public on the XRP Ledger (XRPL), so approving the app does not reveal anything new.
* **Push notifications.** The app can send you notifications, but only through Xaman's own notification system.

That is the whole list. An approved app cannot sign anything for you, and it never sees your account secret. It runs as a web page inside Xaman, so it cannot install software, use your camera or location, or reach anything else on your phone.

Xaman also does not hand the app your balances. Balances and transaction history are public on the XRP Ledger, though, so anyone with your r-address, an app included, can look them up in an explorer[^2]. Approving an app saves you from typing your address. It does not unlock anything private.

### Why apps ask for your address

Knowing your address lets an app work with your account without asking you for it on every screen. Two common examples:

* **An NFT marketplace.** With your address, the marketplace can find the NFTs your account holds and show your collection. It can also notify you when something happens to one of them.
* **A transaction tool, such as XRPL Services.** With your address, the tool can fill it into forms for trust lines, offers, or NFT actions. It can also notify you when a transaction is ready for you to review.

An app can also prepare a transaction and send it to you as a [sign request](#user-content-fn-3)[^3]. You see every detail before you decide, and you can always decline. Nothing is signed or sent unless you approve it yourself.

{% hint style="danger" %}
An xApp can send you a sign request for any transaction, and once you sign it, Xaman and the network cannot reverse it. Check the transaction type, amount, and destination before you sign. Decline anything that does not match what you asked the app to do, or that you do not fully understand.
{% endhint %}

### Find your approved apps

1. Tap **Settings** in the bottom navigation bar.
2. Tap **Third party apps**.

The list shows the icon and name of every app you have approved. If you have not approved any yet, the screen shows **No authorized third party app!** That is normal: the list stays empty until an xApp asks for your address and you approve it.

### What the details screen shows

Tap an app in the list to open its details. The screen has four sections:

| Section                   | What it shows                                                                                                                                                                               |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Details**               | The app's icon, name, and a short description.                                                                                                                                              |
| **Grants**                | What the app can do. Seeing your r-address and sending push notifications are allowed. Accessing balances and signing on your behalf are not. Xaman sets these, and you cannot change them. |
| **Permission**            | **Access granted** (the day you approved it), **Access expires** (the day its access ends by itself), and **Access duration** (how many days the access lasts).                             |
| **Developer information** | Links the developer chose to share, such as a website, support page, privacy policy, or terms. Not every app shares them.                                                                   |

When an app's access expires, Xaman removes it from your list. If you open the app again later, it asks for your approval from the start.

### Revoke an app's access

1. In **Third party apps**, tap the app.
2. Scroll down and tap **Revoke access**.
3. Tap **Yes, I'm sure** to confirm.

The app disappears from your list right away, which tells you its access is gone. It can no longer see your address or send you notifications.

Revoking stops what the app can do from now on. It cannot take back what the app already has: your r-address, and anything you typed into the developer's own website, such as a name or an email address. To ask for that data to be deleted, contact the developer through the links under **Developer information**.

This screen is for checking and revoking only. You cannot approve a new app here, since approval happens when an xApp asks for it. You also cannot turn single permissions on or off, or extend an app's access when it expires.

### An app you do not recognize

If an app appears that you do not remember approving, three checks help:

* **Check Access granted.** A recent date often means you approved it and forgot.
* **Check Developer information.** Look for a website or support link from a developer you trust.
* **Revoke it if in doubt.** Nothing breaks: if you use the app again, it asks for approval again.

If you believe an app was added without your approval, contact our support team through the Xaman Support xApp, and include a screenshot of the app's details screen. Our support team will never ask for your account secret. Anyone who asks for it is trying to take your funds, so never share it.

<a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Open the Xaman Support xApp</a>

### Frequently asked questions

**Does revoking an app delete my transactions or tokens?**

No. Revoking only ends the app's access to your address and notifications. Your transactions, tokens, and everything else on the XRP Ledger stay exactly as they are.

**Can an app see my transaction history?**

Yes, the same way anyone can. Your transaction history is public on the XRP Ledger, so anyone with your r-address can look it up in an explorer. Approving an app only means the app already knows your address.

### See also

* [Understanding the Settings Options](./)
* [XRPL Services](../../xapps/xrpl-services/)
* [Trust in the XRPL community](../../scams-and-staying-safe/trust-in-the-xrpl-community.md)
* [Official communication channels](../../scams-and-staying-safe/official-communication-channels.md)

[^1]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.

[^2]: A website that shows public XRP Ledger data, such as an account's balance, settings, and transaction history.

[^3]: A transaction an app or website prepares and sends to Xaman for you to review. Nothing happens unless you sign it.
