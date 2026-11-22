---
description: Here is how to set up Xaman on your new device.
---

# 📱 Got a new phone?

### Before you start

Congratulations on your new phone! Before you move everything over, these three tips will make the process smoother:

* **Keep your old phone** until Xaman is set up and working on your new phone.
* **Make sure you have the account secret** (Secret Numbers, Family Seed, or Mnemonic) for every account you want to move. If your accounts are on Xaman cards, you only need your cards. See _What about my Xaman cards?_ at the end of this article.
* **Ask us if you get stuck.** If you are unsure about any step in this article, contact us through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md).

### Setting up Xaman on your new phone

You **cannot restore or copy** Xaman from one phone to another. You need to install Xaman **fresh** on your new phone. If Xaman was restored from a backup, you will see this screen when you open the app:

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-adc32b6ec01d60074cc3c3d7a6b33f67d180ddcc%2FPush%20notifications%20-%204.png?alt=media" alt="The Xaman screen shown when the app was restored from a backup"><figcaption></figcaption></figure>

**Step 1. Install Xaman.**

If you already see the screen above, **uninstall** Xaman first.

Next, download the official Xaman app from the [App Store](https://apps.apple.com/app/id1492302343) or [Google Play](https://play.google.com/store/apps/details?id=com.xrpllabs.xumm), and follow the instructions in this article to install it:

[How to install Xaman](https://help.xaman.app/app/getting-started-with-xaman/installing-xumm)

**Step 2. Add your accounts.**

At the end of the installation, you will see this screen:

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-c7522ec5cdf38ac377d0016ef35b32bc44b94eb4%2FNew%20install.png?alt=media" alt="The Xaman home screen after a new installation"><figcaption></figcaption></figure>

Tap **+ Add account**, then choose **Import an existing account**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-99ff35052316ec325605bce91f112645c9293f29%2FImport%20an%20existin%20account%20button.png?alt=media" alt="The Import an existing account button in Xaman"><figcaption></figcaption></figure>

{% hint style="info" %}
**Have Xaman cards?** Tap **Add Tangem card** instead, and follow the instructions on the screen. See _What about my Xaman cards?_ at the end of this article.
{% endhint %}

**Step 3. Enter your account secret.**

Choose the type of account secret you have and enter it into Xaman. These articles walk you through each type:

* [How to import your Secret Numbers](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-secret-numbers)
* [How to import your Family Seed](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-a-family-seed)
* [How to import your Mnemonic](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-a-mnemonic)

Repeat Steps 2 and 3 for each account you want to import.

**Step 4. Check your accounts before you retire your old phone.**

Make sure each account on your new phone shows the same r-address and balance as on your old phone. Once everything matches and you can sign transactions on your new phone, you can uninstall Xaman from your old phone.

### _Frequently asked questions_

#### **What about my Xaman cards?**

Each card's account secret is stored on the card itself, not on your phone, so there is nothing to back up or write down. On your new phone, go to **Settings**, then **Accounts**, then **+ Add account**, and choose **Add Tangem card**. Import each of your cards, including your Backup card.

[How to import your Xaman card](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...a-xaman-tangem-card)

Your Backup card link is stored on the XRP Ledger, not on your phone, so it still works on your new phone. You do not need to run the Tangem Backup xApp again.

Since your cards already hold your accounts, Xaman will warn you that each card has been used before. **That is expected** when you re-import your own cards. Only treat that warning as a problem on a card that is brand new.

{% hint style="warning" %}
**Lost your old phone and your Primary card?** You can still reach your account with your Backup card, but you will need your Primary account's r-address. See [Lost or damaged cards](https://help.xaman.app/app/xaman-tangem-cards/lost-or-damaged-cards).
{% endhint %}

#### **Why should I keep my old phone?**

Sometimes people forget their account secret, or find out it was written down incorrectly. Your old phone can still access your accounts, so it is your safety net if you run into trouble on your new phone.

Once you can access your accounts and sign transactions on your new phone, you can uninstall Xaman from your old phone. You can also keep it as a backup, in case something happens to your new phone.

#### **Why can't I restore Xaman from a backup?**

If Xaman stored sensitive data, like your account secrets, in a Google or Apple iCloud backup, anyone who got into your Google or Apple account could restore that backup to their own phone and take your funds.

That is why it is so important to keep your account secrets stored offline, in a safe place.

#### **My account was created during the CasinoCoin swap. How do I access it?**

If you have your old CasinoCoin wallet secret (a code that starts with a lowercase **s**), you can import it [with this link (scan the QR code with Xaman)](https://xumm.app/detect/secret?type=alt-family-seed\&name=CasinoCoin\&alphabet=cpshnaf39wBUDNEGHJKLM4PQRST7VWXYZ2brdeCg65jkm8oFqi1tuvAxyz).

If you do not have that secret, the CasinoCoin team has documented a process to access accounts created during the swap: [How to recover a CasinoCoin account](https://eminence.freshdesk.com/support/solutions/articles/80000965171-how-to-recover-a-swapped-casinocoin-xumm-account).

If you run into trouble with that process, contact [CasinoCoin Support](https://eminence.freshdesk.com/support/tickets/new).

#### **I imported my account secret, but it opened a different, unactivated account. Do I need to activate it?**

No. To access an XRP Ledger account, you need the **correct** account secret for it. The correct secret **always** opens the same r-address, with your balance and tokens in place.

If you get a different r-address, the secret you entered belongs to a different account. There are three possible reasons:

* the secret was written down incorrectly when the account was created
* the secret was entered into Xaman incorrectly
* your account uses a different account secret

Activating the other account will not give you access to your original one. For more help, see [I've lost my account secret!](https://help.xaman.app/app/learning-more-about-xaman/ive-lost-my-account-secret)

### Questions?

If you have questions about moving Xaman to a new phone, contact us through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md) in Xaman.
