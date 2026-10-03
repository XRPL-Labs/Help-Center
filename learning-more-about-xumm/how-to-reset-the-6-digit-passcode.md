---
description: How to reset your 6 digit passcode/pin
---

# How to reset the 6 digit passcode

#### **Background**

When you install Xaman, the first thing it asks you to do is to enter a 6 digit passcode/pin.

This 6 digit code is one of the primary ways to access the Xaman application. (The other way is via Biometrics.) If, during the installation of Xaman, you did not select "Extra Security", the 6 digit passcode is also one of the ways to sign a transaction in the application.

#### **My 6 digit passcode works fine, I just want to change it**

To change your passcode, launch Xaman, press **Settings** then **Security** then **Change passcode**.

<figure><img src="../.gitbook/assets/Security passcode.png" alt=""><figcaption></figcaption></figure>

Enter in your current passcode, then enter in your new passcode. You have 1 million possible combinations to choose from. This is one of the primary security measures for protecting your funds, so do not choose 123456, 000000, 111111 or something similar. Your passcode should be difficult to guess.

#### **My 6 digit passcode is not working**

If the passcode does not work, the only way to reset it is to **uninstall Xaman and reinstall it.**&#x20;

{% hint style="info" %}
We strongly recommend that you test your account secret before continuing.\
\
[**How to test your account secret**](../learning-more-about-xaman/how-to-test-your-account-secret.md)
{% endhint %}

**Before you uninstall, make sure you have your account secret(s) for all of your accounts.** You'll need each account's secret — its Secret Numbers, Family Seed, or Mnemonic — to access them again after the re-installation.&#x20;



1. Uninstall Xaman, then install it again. (See: [**Installing Xaman**](../getting-started-with-xaman/installing-xumm.md))
2. When Xaman asks you to set a passcode, enter your new 6 digit code.
3. Bring each account back: press **+ Add account**, then **Import an existing account**, and enter its **account secret**. (See: [**How to import your account**](../getting-started-with-xaman/importing-your-account/))

Because the app data is wiped when you remove Xaman from your phone, a couple of things do not come back on their own:

* **Your Address Book** is cleared.
* **Xaman Support tickets** you created are no longer reachable from the app.

What _does_ come back: each account's r-address, balance and tokens are on the ledger and never leave it — re-importing with the same secret logs you back into the _same_ account, not a new one.

#### **Which route for which situation?**

| Your situation                                  | Route                                 |
| ----------------------------------------------- | ------------------------------------- |
| You know your passcode and want a different one | Settings → Security → Change passcode |
| Passcode not working or lost                    | Uninstall and reinstall               |

#### **Frequently asked questions**

**Where can find the account secret in Xaman?**

If you created your account using Xaman, you would have received a set of ‘secret numbers’. (8 rows of numbers, A to H, each with 6 digits.)  The app does not have the ability to display or recover your secret numbers. They are only displayed once, when an account is created. After that, there is no way to see them again.

You can read more about this here:

[**Can I view/export my account secret?**](../learning-more-about-xaman/can-i-view-export-my-account-secret.md)

\
**I've lost my account secret, what should I do?**

Xaman does not have an account secret recovery mechanism — no cloud backup, no "email me my seed," no support reset. If you lose your account secret, your funds remain safe on the XRPL ledger but become **permanently inaccessible** without it.

If your account secret is truly lost, you only have a couple of options. See this article for the full picture:

[**I've lost my account secret!**](https://help.xaman.app/app/learning-more-about-xaman/ive-lost-my-account-secret)\
\
**How can my passcode work one minute, then completely stop working the next?**\
\
Xaman can be very sensitive to changes made to a phone, an operating system or to Xaman itself. Anything that might compromise the security of your XRP Ledger account is viewed as suspicious and may require that you prove account ownership. (Although this security feature may be a bit annoying, it helps ensure the safety of your account.)
