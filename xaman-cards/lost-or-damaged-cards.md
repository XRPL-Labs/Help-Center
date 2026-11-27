---
description: What to do if you lose or damage a card
---

# Lost or damaged cards

Losing a card is stressful, and the good news is that a Backup card exists for exactly this moment. Each Xaman card creates its [account secret](#user-content-fn-1)[^1] on the card itself, and the secret never leaves it. No one else can know it, including us. That keeps the secret out of everyone else's reach, but it also means a lost, damaged, or stolen card cannot be recovered. Xaman is a self-custody[^2] wallet, so we cannot recover a lost card, freeze an account, or reverse a transaction for you.

That is why every order includes at least two cards. With a second card linked to your Primary account as a Backup card, you can still reach your funds if something happens to one of them. This article walks you through each case, for accounts on the XRP Ledger (XRPL).

### How your Backup card protects you

When you set up your cards, Xaman links your Backup card to your Primary account. It uses the XRP Ledger's [regular key](#user-content-fn-3)[^3] feature, which lets a second key sign for an account. After the link, either card can sign for your Primary account, so losing one card does not lock you out.

If you have not linked a Backup card yet, do it now, while both cards are with you. Open your Primary account in Xaman and tap **No back-up card configured**. [Setting up a Backup card](setting-up-a-backup-card.md) walks you through it.

{% hint style="info" %}
Write down your Primary account's r-address and keep it somewhere safe. If you lose your phone and your Primary card together, you need it to reach your account with your Backup card.
{% endhint %}

### What you can do

#### If your Primary card is lost or damaged

Use your Backup card to move your funds to another account you control. Your Backup card can sign for your Primary account, so your funds are still within reach.

{% hint style="warning" %}
Anyone holding your Primary card can sign for your Primary account. They could send every coin and token in it away. If your Primary card may have been stolen, move your funds right away, before anything else.
{% endhint %}

1. Open Xaman, and select your Primary card account.
2. Send your XRP and tokens to another account you control.
3. Sign each transaction with your Backup card.

To receive a token, the other account needs a [trust line](#user-content-fn-4)[^4] for it first. If you do not have another account yet, see [How to create an XRP Ledger account](../getting-started-with-xaman/what-is-xaman/how-to-create-an-xrpl-account.md), or set up a new pair of Xaman cards. Your funds have moved once they show in the other account.

Once your funds are safe, you can delete the old Primary account to get back most of its reserve, signing with your Backup card. [How to delete an XRPL account](../your-accounts/importing-your-account/how-to-delete-an-xrpl-account.md) explains how.

#### If your Backup card is lost or damaged

Use your Primary card to remove the link to your Backup card. After that, the Backup card can no longer sign for your Primary account, even if someone else has it. Your Primary card still controls everything.

{% hint style="warning" %}
Until you remove the link, anyone holding your Backup card can sign for your Primary account. They could send your funds away. If your Backup card may have been stolen, remove the link right away, before anything else.
{% endhint %}

1. Tap **Settings** > **Accounts**.
2. Tap **Edit** next to your Primary card account.
3. Tap **Update** next to **Back-up card**.
4. Tap **Remove back-up card**. Xaman warns that your account will no longer have a back-up card.
5. Tap **Remove**.
6. Check that the account and the back-up card shown are the right ones, and tap **Scan original card**.
7. Hold your Primary card against your phone until the scan finishes.
8. When **Back-up card removed** appears, tap **Done**.

Once the link is removed, the **Back-up card** line on your Primary account's **Edit account** screen shows **Not set up yet** again. If you have a spare card, tap **Set up** to link it as your new Backup card. [Setting up a Backup card](setting-up-a-backup-card.md) walks you through it.

#### If something here does not match what you see

We can help you work out which card is affected and what to do next. Our support team will never ask for your account secret. Anyone who asks for it is trying to take your funds, so never share it.

<a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Open the Xaman Support xApp</a>

### Frequently asked questions

**What if I lose my phone and my Primary card at the same time?**

You can still reach your account with your Backup card. This is where the r-address[^5] you wrote down comes in.

1. Install Xaman on your new phone.
2. Import your Backup card. See [How to import your Xaman card](...a-xaman-tangem-card.md).
3. Add your Primary account in **Read only** mode by entering its r-address. See [How to import an account in Read Only mode](../your-accounts/importing-your-account/...in-read-only-mode.md).
4. Send your funds from the Primary account to another account you control.
5. Sign each transaction with your Backup card.

**What if I lose my phone but still have both cards?**

Nothing is lost, since your account secrets are on your cards, not your phone. Install Xaman on your new phone and import both cards again. Your Backup card link is stored on the XRP Ledger, so it still works. See [Got a new phone?](../your-accounts/importing-your-account/migrate-to-a-new-phone.md).

**My card is damaged, but it still works sometimes. What should I do?**

Treat it as a lost card while you can still use it. If it is your Primary card, move your funds to another account now. If it is your Backup card, remove its link. Do not wait for the card to stop working completely.

**What if I lose both cards?**

We are truly sorry, but there is no way to recover an account once both cards are lost. Neither we nor anyone else can reach the account secret on a card, and anyone who offers to recover it is trying to take your money (see [Recovery scams](../scams-and-staying-safe/recovery-scams.md)). Keeping your two cards in different places means a single fire, theft, or lost bag cannot take both. See [Best security practices for the Xaman cards](best-security-practices-using-a-xaman-card.md).

### See also

* [Setting up a Backup card](setting-up-a-backup-card.md)
* [Setting up your Xaman cards](getting-started.md)
* [Xaman cards](xaman-tangem-cards.md)
* [Best security practices for the Xaman cards](best-security-practices-using-a-xaman-card.md)
* [Got a new phone?](../your-accounts/importing-your-account/migrate-to-a-new-phone.md)
* [Recovery scams](../scams-and-staying-safe/recovery-scams.md)

[^1]: The secret that controls your account, as Secret Numbers, a Family Seed, or a Mnemonic. Never share it with anyone.

[^2]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^3]: A second key that can sign for your account, such as a Backup card.

[^4]: Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.

[^5]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.
