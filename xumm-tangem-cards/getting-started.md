# Getting started with your new cards 🤗

Your Xaman cards have arrived! 🎉

Let’s open the package together. In about ten minutes, you will go from a sealed pouch to a working cold wallet: two cards, one account, and your XRP secured by a card you can hold in your hand. We will walk you through every step, from your first tap to linking your backup.

#### What you can expect in the package

Your package arrives in a sealed pouch and contains:

* **At least two cards**, in the designs you picked when you ordered. The cards are loose in the pouch. This is normal.
* **Your pre-funded card**, which is one of your cards in a clear plastic sleeve with an orange label telling you to import it first. This card comes with 1 XRP that you claim when you set it up, so you do not need to buy XRP to get started. The sleeve is only there so you can spot the card. It does not change how the card works.
* **A printed instruction sheet**, which covers the same setup as this article, in less detail.
* **A thank-you card** with links to download Xaman from the App Store or Google Play.

Whichever designs you picked, every card works exactly the same way, including partner ecosystem cards. The only difference is that one card comes pre-funded, and that is the card you will use as your Primary.

If your package arrived opened, see [Are my Xaman cards safe?](https://help.xaman.app/app/xaman-tangem-cards/are-my-xaman-cards-safe)

{% hint style="info" %}
**Already have an XRP Ledger account in Xaman?** Read [How to link an existing account to a Xaman card](https://help.xaman.app/xaman-tangem-cards/how-to-link-an-existing-account-to-a-xumm-card) before you start. It helps you decide whether to keep using your existing account or move everything to a new card account.
{% endhint %}

#### Before you start

To use Xaman cards, you need:

* a phone with NFC (the same technology used for tap-to-pay), with NFC turned on
* an up-to-date version of iOS or Android
* the latest version of the official Xaman app from the [App Store](https://apps.apple.com/app/id1492302343) or [Google Play](https://play.google.com/store/apps/details?id=com.xrpllabs.xumm)

#### The one thing to understand first

**Each new card creates and holds its own account.**

A new card holds no account at all. When you import it, the card creates a brand new XRP Ledger account inside itself. So after you import your two cards, they are **two different accounts**, not one.

That is normal. Here is what you do next. Your pre-funded card becomes your **Primary** card. The Primary card is where your XRP will live. Then you link your other card to it as your **Backup** card. (The printed sheet in your package calls this the **Signing** card. It is the same thing.) After the link, both cards can sign for the **same** account (the Primary account).

Think of it like two keys to the same door. The Primary card is the master key. The Backup card is a second key to that same door.

{% hint style="info" %}
The Backup card is not a clone of the Primary card. It is an alternative way to access the same account.

* **If you lose the Backup card**, use your Primary card to remove the link to the Backup card, then keep using your Primary card.
* **If you lose the Primary card**, use the Backup card to move your assets to another account.

Write down your Primary account's r-address and keep it somewhere safe. If you ever lose your phone and your Primary card at the same time, you will need it to get back into your account with the Backup card.

See [Lost or damaged cards](https://help.xaman.app/app/xaman-tangem-cards/lost-or-damaged-cards) for step-by-step help.
{% endhint %}

#### What the cards are for

A Xaman card is a cold wallet option. It is a physical card with a secure chip (a secure element). Its three jobs are:

* create an account secret for an account
* store that account secret inside the chip
* sign transactions on the account that the card created

The account secret never leaves the chip, and it never touches your phone. Xaman never sees it. Since the secret is stored on the card, the only way someone can sign for that account is to **physically have the card**. This also means you should treat your cards like cash or house keys: anyone who holds a card can use it to sign.

{% hint style="info" %}
The cards work with **both** XRP (on the XRP Ledger) and XAH (on Xahau).
{% endhint %}

#### What the cards are not for

The cards are not bank cards. You cannot use them:

* to connect to your bank account
* at an ATM or bank machine
* as a debit or credit card

They only do one thing. They protect and control your XRPL/Xahau account.

#### Setting up your two cards, step by step

This is the setup we recommend. It takes about ten minutes.

**Step 1. Import the pre-funded card and claim your XRP.**

Take the card out of the clear sleeve and import it first. In Xaman, go to **Settings**, then **Accounts**, then **+ Add account**, and choose **Add Tangem card**. The app walks you through the rest.

See: [How to import your Xaman card](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card) for more information.

{% hint style="danger" %}
When you first tap a new card, Xaman checks that the card is genuine and has never been used. If the app warns you that a card was used before, **stop**. Do not import that card. Contact us through the [**Xaman Support xApp**](https://xaman.app/detect/xapp:xumm.support-md) before you do anything else.
{% endhint %}

After the import, tap the **Activate** button in the app to claim the pre-funded 1 XRP. This activates the account, which is now your Primary account. See [What is a "Pre-funded" Xaman card?](https://help.xaman.app/app/getting-started-with-xaman/how-to-activate-a-new-xrpl-account/what-is-a-pre-funded-xaman-card)

{% hint style="info" %}
**Why can't I spend the 1 XRP?** An XRP Ledger account that holds funds must keep a minimum balance, called the **reserve**. The 1 XRP on your Primary account is that reserve. You will see it in your balance, but you cannot spend it. This is a rule of the XRP Ledger, not a Xaman fee. The reserve amount is set by the network and can change over time.
{% endhint %}

**Step 2. Import your second card.**

Import the second card the same way. This card becomes your Backup card. It does not need any XRP, because its only job is to sign for your Primary account. Xaman shows its account as not activated. This is expected, and you can leave it that way.

<details>

<summary>I would rather use the other card as my Primary card</summary>

You can, but it takes a few extra steps. Do these after Step 2:

1. Activate the second card's account yourself by sending it at least the reserve amount of XRP. See: [How to activate a new XRPL account](https://help.xaman.app/app/getting-started-with-xaman/how-to-activate-a-new-xrpl-account).
2. Delete the account on the pre-funded card, and choose your new Primary account as the destination. The remaining XRP is sent there. See: [How to delete your account](../learning-more-about-xumm/deleting-an-xrpl-account.md).
3. Continue with Step 3 below, linking the pre-funded card as your Backup card.

Deleting an account costs a small network fee, so you will get back slightly less than the reserve. Once deleted, an account can be activated again later, but only by sending it new XRP.

</details>

**Step 3. Link the Backup card to your Primary account.**

Use the [Tangem Backup xApp](https://xaman.app/detect/xapp:xumm.tangem-backup) to link the Backup card to your Primary account. After this step, both cards can sign for the Primary account. This uses the XRP Ledger "regular key" feature. You do not need to understand the feature to use it. The xApp walks you through every step.

See: [How to configure a backup signing account](https://help.xaman.app/app/xaman-tangem-cards/how-to-configure-a-backup-signing-account) for more information.

**Step 4. Move your funds to your Primary account.**

Send your XRP (and any other assets) to the Primary account.

**Step 5. Decide what to do with your old account (if you have one).**

If you had an XRP Ledger account before the cards, you can move everything to the card account or keep both. Both are fine. See: [How to link an existing account to a Xaman card](https://help.xaman.app/app/xaman-tangem-cards/how-to-link-an-existing-account-to-a-xumm-card).

#### Which card do I use day to day?

Most people store the **Primary** card somewhere safe (in a safe, a safe deposit box, or a locked drawer), because it is the master key to the account where the money lives. They carry the **Backup** card with them and use it to sign everyday transactions on the Primary account.

This setup limits the damage if something goes wrong. If you lose the Backup card you carry, you use your Primary card to remove the link to it, and your Primary card still controls everything. See [Lost or damaged cards](https://help.xaman.app/app/xaman-tangem-cards/lost-or-damaged-cards). Either choice works, though. Both cards control the same account after the link.

#### I have more than two cards. What do I do with the others?

The regular key feature allows **one** Backup card per account, so you cannot link a third card to the same account as a second backup. People use extra cards in a few ways:

* as a spare, ready to become your new Backup (or new Primary) if one of your cards is ever lost or damaged
* as a separate account for daily spending, NFTs, trading, or testing
* to give to a friend or family member
* as part of a [multi-signing](https://xrpl.org/multi-signing.html) setup (advanced)

Extra cards are not pre-funded, so you need to activate each one you plan to use as its own account.

#### Summary

The Xaman card is a cold wallet option. Each card holds its own account secret in a secure chip. You import the pre-funded card and claim its XRP, import your second card, and link it as your Backup. After that, two cards control one account, and you keep your XRP under your own control.

For more, read [Best security practices with a Xaman card](https://help.xaman.app/app/xaman-tangem-cards/best-security-practices-using-a-xumm-card). If you have questions, contact us through the [**Xaman Support xApp**](https://xaman.app/detect/xapp:xumm.support-md)  in Xaman.
