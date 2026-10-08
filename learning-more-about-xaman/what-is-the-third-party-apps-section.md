---
description: What is the Third Party Apps section?
---

# What is the Third Party Apps section?

## What is the Third Party Apps section?

I opened Settings in Xaman and I see a row called "Third party apps." I want to understand what it does and what those apps can actually see.

**The Third Party Apps section is your authorization list. It shows every xApp that has been granted permission to see your public address and send notifications through Xaman, and when that permission expires. You can revoke any app at any time.**

#### What is an xApp?

An xApp is a web application that runs inside Xaman. Both Xaman and independent developers build xApps. They can provide extra features like token management, NFT tools, or account utilities. The first time an xApp wants to display your public address, Xaman shows an authorization prompt. You can approve or deny. If you approve, the app appears in the Third Party Apps list.

#### What permissions does an xApp get?

When you authorize an xApp, you are granting exactly two permissions:

* **See your public r-address.** Your address is already public on the XRPL. Authorizing an xApp does not expose it to anyone new.
* **Send push notifications through Xaman.** The xApp can send you notifications, but only through Xaman's notification system.

An xApp **cannot**:

* Sign transactions on your behalf
* Access your account secret or recovery phrase
* Send code, files, or anything to your phone
* Access your camera, microphone, location, or any other device sensor
* Spy on you or monitor your activity inside Xaman, on your phone, or anywhere else

Your keys never leave your device. An xApp is a web page running inside Xaman's WebView. It cannot install software, modify your device, or reach outside of Xaman.

**What an xApp can do:** It can create a transaction and send you a push notification asking you to review and sign it. You will see the full transaction details before you sign. You can decline. Nothing is signed or sent without your explicit approval and vault authentication (passcode, biometrics, or Tangem).

#### Why would I want to grant this access?

Because knowing your r-address (a public value) makes the xApp useful to you without you having to paste your address every time. Two examples:

* **An NFT marketplace xApp.** Once you grant access, the marketplace can look up your r-address on the public ledger, find the NFTs it holds, and display your collection in its interface. You can browse, list, or buy NFTs without re-entering your address on every screen. It can also send you a push notification when one of your NFTs is listed or when a marketplace event happens.
* **An XRPL transaction tool (such as XRPL.Services).** Once you grant access, the tool can pre-fill your r-address into transaction forms. You build a trust line, an offer, or an NFT operation without retyping your address. It can send you a push notification when a transaction you created is ready for you to review and sign.

In both cases, the xApp is reading public ledger data that anyone with your r-address can already see. The only difference is convenience: the app already has your address, so you do not have to type it in.

#### Where to find it

1. Open Xaman and tap **Settings** (gear icon, bottom-right).
2. Tap **Third party apps** (between Security and Help Center).

If you have not authorized any xApps yet, you will see:

> **No authorized third party app!**
>
> Once you authorize access to a third party app you'll see them here.

This is normal. The list stays empty until an xApp asks for permission and you approve it.

#### What you see in the list

Each authorized app shows its **icon** and **name**. Tap an app to see its details.

#### App details

When you tap an app in the list, you see four sections:

**Details**

The app's icon, name, and a short description of what it does.

**Grants**

Xaman shows a fixed set of capabilities. The check and cross icons are not configurable. They are set by the Xaman backend:

| Capability                              | Status      |
| --------------------------------------- | ----------- |
| See r-address                           | Allowed     |
| Send push notifications (through Xaman) | Allowed     |
| Access balances                         | Not allowed |
| Sign on your behalf                     | Not allowed |

In short: an authorized xApp can see your public address and send you notifications. It **cannot** see how much XRP or tokens you hold, and it **cannot** sign or send transactions. Your keys never leave your device.

**Permission**

Three dates for each authorization:

| Field               | Meaning                                       |
| ------------------- | --------------------------------------------- |
| **Access granted**  | The date you approved the permission.         |
| **Access expires**  | The date the permission automatically lapses. |
| **Access duration** | How many days the permission is valid.        |

When the expiration date passes, the app's access is automatically removed. It will no longer appear in your list.

**Developer information**

If the app's developer provided links, you will see them here: Website, Support, Privacy policy, and/or Terms & conditions. Tap any link to open it in your browser. Not all apps provide these.

#### Revoking access

You can remove an app's permission at any time.

1. In the Third Party Apps list, tap the app you want to revoke.
2. Scroll down and tap **Revoke access** (red button at the bottom).
3. A **Warning** dialog appears: "Are you sure you want to revoke access to {app name}?"
4. Tap **Yes, I'm sure** to confirm, or **Cancel** to go back.

The app is immediately removed from your list. It can no longer see your address or send notifications. If you use that xApp again in the future, it will ask for permission again from the start.

**What revoking does not do:** It does not delete data the app already collected. The app already received your r-address during your session and can store it in their own database. If the app's website asked you for a name, email address, or other personal information and you provided it, that data remains on their side. If you no longer trust the app, contact the developer directly to request deletion of your data.

#### What you cannot do from this section

This section is **list and revoke only**. You cannot:

* Add or authorize a new xApp from here. Authorization happens when an xApp requests it through the Xaman app itself.
* Enable or disable individual permissions (like "allow notifications" but not "allow address"). The permission set is fixed by Xaman.
* Extend an expiration date. When it lapses, it lapses. Re-authorize if you still want access.

#### When do apps get access?

An xApp requests permission the first time you use a feature that needs it. For example, if you open an xApp that wants to display your address in its UI, Xaman shows an authorization prompt. You can approve or deny. If you approve, the app appears in the Third Party Apps list with the dates and capabilities described above.

You will not see an app in this list unless you explicitly approved its request.

#### What if I see an app I do not recognize?

If you see an app in the list and you do not remember authorizing it:

1. Check the **Access granted** date. If it is recent, you may have approved it and forgotten.
2. Check the **Developer information** section for a website or support link. Verify it is a legitimate developer.
3. If you are unsure, **revoke the access**. It takes ten seconds. The worst case is that you re-authorize later if you actually use that app.

If you believe the app was added without your knowledge, contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md) from within the app and include a screenshot of the app details screen.

#### FAQ

**Does revoking an app delete my data?**

No. Revoking removes the app's ability to see your r-address and send you push notifications through Xaman. It does not delete any transactions, tokens, or ledger data. The xApp website itself (the developer's own site) is not affected.

**Can an xApp see my transaction history?**

Your r-address is public on the XRPL. Anyone, including an xApp, can look up your transaction history on a public ledger explorer. The difference with an xApp is convenience: it already has your address, so it does not need you to type it in.

#### Need help?

Contact [**Xaman Support**](https://xaman.app/detect/xapp:xumm.support-md) from within the app. Include a screenshot of the Third Party Apps screen and the app details if you have a question about a specific app.
