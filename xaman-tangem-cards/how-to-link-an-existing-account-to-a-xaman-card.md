---
description: Use your Xaman cards with an XRP Ledger account you already have
---

# How to link an existing account to a Xaman card

Many people who buy Xaman cards already have an XRP Ledger account in Xaman. This article helps you decide what to do with that account, and shows you how to link it to a card if that is the right choice for you.

#### First, decide what you want

You have three options. Most people should choose the first one.

**Option 1 (recommended): Move your funds to your card account.**\
Set up your cards as described in [Getting started with your new cards](https://help.xaman.app/app/xaman-tangem-cards/getting-started), then send your funds from your existing account to your new Primary card account. Your funds are then protected by an account secret that never leaves your cards, and your cards work just as well for everyday use as for long-term savings. You do not need to link anything.

**Option 2: Let a card sign for your existing account.**\
This adds the card as a second way to sign for your existing account. Choose this if you want to keep your existing r-address, for example because your trust lines, NFTs, escrows, or exchange withdrawal addresses are tied to it. Jump to the steps.

**Option 3 (not recommended): Let your existing account sign for your card account.**\
This weakens the security of your card account, and it uses up the slot you would otherwise use for a Backup card. It only makes sense if you have a single card and no way to get a second one. Jump to the steps.

#### Why it matters: where the account secret lives

**A Xaman card keeps its account secret on the card.** The secret never leaves the card, so you need the card in your hand to sign. You can use your cards for everyday activity just as well as for long-term savings.

**An account created in Xaman without a card keeps its secret on your phone,** protected by Xaman. You sign with your phone instead of a card.

Both are secure ways to hold your funds. Linking changes how many ways there are to sign for an account: after a link, the account can be signed for by its own secret **and** by the linked one. So it helps to think about which secret ends up controlling which account. That is the main difference between Options 2 and 3.

#### Option 2: Let a card sign for your existing account

{% hint style="info" %}
**What this does and does not do.** This adds the card as a signer for your existing account. It does not remove your existing account secret. After you finish, both your original account secret and the card can sign for the account.

If you want the card to be the **only** signer, you must also disable the account's master key. That is a separate, advanced step.  [Contact support](https://xaman.app/detect/xapp:xumm.support-md) before you do it.
{% endhint %}

**Step 1. Check your existing account**

Your existing account must be in Xaman with **Full access**, so you can sign transactions with it. This is your Primary account for these steps.

An account can only have one regular key. If your existing account already has one, this procedure replaces it.

**Step 2. Import your card**

Import the card you want to use. See [How to import your Xaman card](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card).

The card's own account does not need any XRP for this. Its only job is to sign for your existing account.

**Step 3. Copy your card's r-address**

With the card account selected, tap **Receive**, then tap **Copy**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2F6InuNmkrjYjDwh0cA2pX%2FRecieve%20button%20-2.png?alt=media&#x26;token=3cb2e875-bbbb-400a-8520-5829d6db03c8" alt="The Receive button in Xaman" width="375"><figcaption></figcaption></figure>

**Step 4. Sign in to XRP Ledger Services with your existing account**

In Xaman, switch to your existing account. Then go to [XRP Ledger Services](https://xrpl.services/), tap the sign-in button, choose **Open in Xumm App**, and sign in.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-9ade49286ad7bd499d9ffa6252bcdb204d314b67%2FSign%20into%20Xumm.png?alt=media" alt="Signing in to XRP Ledger Services with Xaman"><figcaption></figcaption></figure>

**Step 5. Set the regular key**

On XRP Ledger Services, select **Set Regular Key**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-306b13376dfc1e1cdd510614d68478d3b46f5cac%2FXRPL%20Services%20-%20Reg%20Key%20-%201.png?alt=media" alt="The Set Regular Key option on XRP Ledger Services"><figcaption></figcaption></figure>

Paste your **card's** r-address into the field labeled "XRPL address which will be able to sign transactions," then tap **Send Set Regular Key to Xumm**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-8a1a285f6f9c11ce628cd0a81bc5f7eb2824e68f%2FXRPL%20-%20Regular%20keys.png?alt=media" alt="Pasting the card&#x27;s r-address into the Set Regular Key form"><figcaption></figcaption></figure>

**Step 6. Sign with your existing account**

Sign the transaction in Xaman with your existing account. You're done! Your card can now sign for your existing account.

#### Option 3: Let your existing account sign for your card account

{% hint style="danger" %}
**We do not recommend this option.** Read this before you continue:

* **It weakens your card account.** Your existing account's secret is stored on your phone. If that account is ever compromised, the attacker can also sign for your card account.
* **You cannot also link a Backup card.** An account can only have one regular key. If your existing account takes that slot, there is no room for a Backup card.

The only good reason to choose this option is if you have a single card and your existing account is your only backup.
{% endhint %}

**Step 1. Import your card**

Import your card. See [How to import your Xaman card](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card).

**Step 2. Activate your card account**

Your card account must be activated before it can hold funds. If this is your pre-funded card, tap **Activate** in the app to claim your 1 XRP. Otherwise, send it at least the reserve amount of XRP. See [How to activate a new XRPL account](https://help.xaman.app/app/getting-started-with-xaman/how-to-activate-a-new-xrpl-account).

**Step 3. Copy your existing account's r-address**

In Xaman, switch to your existing account, tap **Receive**, then tap **Copy**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2FJ0GEjGVTa9JYewZndqRP%2FRecieve%20button%20-2.png?alt=media&#x26;token=785c3731-854e-4e69-b8f5-31e8c9444cf0" alt="The Receive button in Xaman" width="375"><figcaption></figcaption></figure>

**Step 4. Sign in to XRP Ledger Services with your card**

In Xaman, switch to your card account. Then go to [XRP Ledger Services](https://xrpl.services/), tap the sign-in button, choose **Open in Xumm App**, and sign in with your card.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-9ade49286ad7bd499d9ffa6252bcdb204d314b67%2FSign%20into%20Xumm.png?alt=media" alt="Signing in to XRP Ledger Services with Xaman"><figcaption></figcaption></figure>

**Step 5. Set the regular key**

On XRP Ledger Services, select **Set Regular Key**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-306b13376dfc1e1cdd510614d68478d3b46f5cac%2FXRPL%20Services%20-%20Reg%20Key%20-%201.png?alt=media" alt="The Set Regular Key option on XRP Ledger Services"><figcaption></figcaption></figure>

Paste your **existing account's** r-address into the field labeled "XRPL address which will be able to sign transactions," then tap **Send Set Regular Key to Xumm**.

<figure><img src="https://3221812686-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FMiHAzvIPISVuuzt0AeOR%2Fuploads%2Fgit-blob-8a1a285f6f9c11ce628cd0a81bc5f7eb2824e68f%2FXRPL%20-%20Regular%20keys.png?alt=media" alt="Pasting the existing account&#x27;s r-address into the Set Regular Key form"><figcaption></figcaption></figure>

**Step 6. Sign with your card**

Sign the transaction with your card. You're done! Your existing account can now sign for your card account.

#### Frequently asked questions

**What is the recommended way to set up my cards?**

Use two cards: make your pre-funded card your Primary card, and link your second card to it as a Backup card. See: [Getting started with your new cards](https://help.xaman.app/app/xaman-tangem-cards/getting-started).

**I only have one card. What should I do?**

Every order now includes at least two cards, but some people order three or more cards.

A card's account secret exists only on the card and cannot be copied or viewed. If you have a single card and it is lost or damaged, you lose access to the funds on its account. To protect yourself, you can use Option 3 to make your existing account a backup for your card account. Keep the trade-offs above in mind, and consider ordering a second card at [order.xaman.app](https://order.xaman.app/).

**How do I undo a link?**

Remove the regular key from the account that has it:

1. Go to [XRP Ledger Services](https://xrpl.services/) and sign in with that account.
2. Choose **Set Regular Key**, then **Delete regular key**.
3. Tap **Confirm**, scan the QR code with Xaman, and sign the transaction.

After this, only the account's own secret can sign for it.

If you disabled the account's master key, the XRP Ledger will not let you remove the regular key, because the account would be left with no way to sign. Contact support before you change anything.

#### Questions?

If you have questions about linking an existing account, contact us through the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md) in Xaman.
