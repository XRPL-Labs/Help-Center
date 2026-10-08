---
description: What is the Third Party Apps section?
---

# What is the Third Party Apps section?

## What is the Third Party Apps section?

I opened Settings in Xaman and I see a row called "Third party apps." I want to understand what it does and what those apps can actually see.

#### What is an xApp?

An xApp (xRPL Application) is a third-party web application that runs inside Xaman. xApps can provide extra features like token management, NFT tools, or account utilities. When an xApp needs access to your account, it asks for permission through Xaman's built-in authorization flow. Once you approve, the app appears in the Third Party Apps list.

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

**App information**

The app's icon, name, and a short description of what it does.

**What this app can do**

Xaman shows a fixed set of capabilities. The check and cross icons are not configurable.&#x20;

| Capability                              | Status      |
| --------------------------------------- | ----------- |
| See your r-address                      | Allowed     |
| Send push notifications (through Xaman) | Allowed     |
| Access your balances                    | Not allowed |
| Sign transactions on your behalf        | Not allowed |

In short: an authorized xApp can see your public address and send you notifications. It **cannot** sign or send transactions. Your keys never leave your device.

**Permission dates**

Three dates for each authorization:

| Field               | Meaning                                       |
| ------------------- | --------------------------------------------- |
| **Access granted**  | The date you approved the permission.         |
| **Access expires**  | The date the permission automatically lapses. |
| **Access duration** | How many days the permission is valid.        |

When the expiration date passes, the app's access is automatically removed. It will no longer appear in your list.

**Developer information**

If the app's developer provided links, you will see them here: Website, Support, Privacy policy, and/or Terms of service. Tap any link to open it in your browser. Not all apps provide these.

#### Revoking access

You can remove an app's permission at any time.

1. In the Third Party Apps list, tap the app you want to revoke.
2. Scroll down and tap **Revoke access** (red button at the bottom).
3. A confirmation prompt appears: \*"Are you sure you want to revoke access to {app name}?"\*
4. Tap **Do it** to confirm.

The app is immediately removed from your list. It can no longer see your address or send you notifications. If you use that xApp again in the future, it will ask for permission again from the start.

#### What you cannot do from this section

This section is **list and revoke only**. You cannot:

* Add or authorize a new xApp from here. Authorization happens when an xApp requests it through the Xaman app itself.
* Enable or disable individual permissions (like "allow notifications" but not "allow address"). The permission set is fixed by Xaman.
* Extend an expiration date. When it lapses, it lapses. Re-authorize if you still want access.

#### When do apps get access?

An xApp requests permission the first time you use a feature that needs it. For example, if you open an xApp that wants to display your address in its UI, Xaman shows an authorization prompt. You can approve or deny. If you approve, the app appears in the Third Party Apps list with the dates and capabilities described above.

You will not see an app in this list unless you (or a previous version of your account) explicitly approved its request.

#### What if I see an app I do not recognize?

If you see an app in the list and you do not remember authorizing it:

1. Check the **Access granted** date. If it is recent, you may have approved it and forgotten.
2. Check the **Developer information** section for a website or support link. Verify it is a legitimate developer.
3. If you are unsure, **revoke the access**. It takes ten seconds. The worst case is that you re-authorize later if you actually use that app.

If you believe the app was added without your knowledge, [contact support](https://xaman.app/detect/xapp:xumm.support-md) and include a screenshot of the app details screen.

#### FAQ

**Does revoking an app delete my data?**

No. Revoking removes the app's permission to interact with your Xaman account. It does not delete any transactions, tokens, or ledger data. The xApp itself (the website it loads) is not affected.

**Can an xApp see my transaction history?**

No. The permission set does not include transaction history access. An xApp can see your r-address, which is public on the XRPL, but it cannot query your transaction history through Xaman.

**How often should I check this list?**

There is no fixed schedule. A good habit is to check it whenever you install a new xApp or after a few months of use. If an app's expiration date is approaching and you no longer use it, let it lapse naturally or revoke it early.

**Why does the app list show "No authorized third party app" even though I use xApps?**

Some xApps do not request account-level permissions. They run entirely in the WebView without needing to know your address or send notifications. Only xApps that explicitly request authorization through the XUMM flow appear in this list.

#### Need help?

[Contact Xaman support](https://xaman.app/detect/xapp:xumm.support-md). Include a screenshot of the Third Party Apps screen and the app details if you have a question about a specific app.

***

<br>
