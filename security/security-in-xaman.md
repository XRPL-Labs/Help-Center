---
description: How Xaman protects your accounts, and the habits that keep them protected
---

# Security in Xaman

When you trust Xaman with your XRP, it is natural to ask how well it is protected. This article walks you through it: what protects your account, how Xaman guards it on your phone, and the few habits that make a big difference.

XRP is the native coin of the XRP Ledger (XRPL), the network your Xaman accounts live on. This article covers XRP Ledger accounts.&#x20;

Xaman is a self-custody wallet. Your account secrets belong to you alone, and they are never stored with us. This also means we cannot recover a lost secret, freeze your account, or reverse a transaction. It is the same reason no one else can do those things either.

### Everything starts with your account secret

Your account is protected by one thing above all: your account secret. This is the Secret Numbers, Family Seed, or Mnemonic you received when you created the account. Whoever holds it can use the account, from any wallet, on any device.

That is why you hear us say it so often. Keep your account secret private, and never share it. As long as it stays with you, it is the strongest protection your account has.

{% hint style="danger" %}
Never share your account secret with anyone. Anyone who has it can take everything in your account. Xaman support never asks for it, so anyone who asks is a scammer.
{% endhint %}

### Could someone guess your account secret?

No. Your Secret Numbers are picked at random from about 340 undecillion possibilities. That is 340 followed by 36 zeros, a number so large it is hard to picture.

Here is one way to imagine it. Suppose you had a job that paid 390 trillion euros an hour, and you worked every hour of every day. To earn 340 undecillion euros, you would need about 100 quintillion years. Someone trying to guess your account secret faces the same task. Even at 390 trillion guesses an hour, trying them all would take about 100 quintillion years.

### How Xaman guards your secrets on your phone

Your account secrets are stored on your phone, so Xaman protects them in layers. Someone who gets hold of your phone first has to get past your phone's own lock. Next comes the Xaman passcode. Then, before any transaction can be signed, comes your account's own signing password. Each layer has to be broken, one after the other.

A 6-digit passcode might not sound like much since there are only 1,000,000 combinations, and at one guess per second, someone could try them all in under 12 days. Unfortunately Xaman does not allow that. After a few wrong attempts, Xaman makes each new attempt wait, and the wait grows to 2 hours before you can make another attempt. At that pace, trying every combination would take about 228 years.

These layers protect the copy of your secrets stored on this phone. Each phone with Xaman has its own passcode, so if you use the same account on two phones, a change on one does not affect the other.&#x20;

### Your phone is your first line of defense

Xaman can only be as secure as the phone it runs on. The good news is that a few everyday habits make a big difference:

* **Keep your phone updated.** System updates close security holes, so install them as soon as they arrive.
* **Lock your phone.** Use a strong passcode together with Face ID, a fingerprint, or another biometric lock.
* **Install apps only from the App Store or Google Play.** Apps from other sources are a common way for malware to get in.
* **Do not jailbreak or root your phone.** Doing so removes protections that Xaman relies on.
* **Never install a screen-sharing or remote-access app because someone asks you to.** Scammers use these apps to watch and control your phone.
* **Never enter your account secret on a website or in another app.** Xaman never needs you to.

### Xaman cards: protection that stays with you

Even with all these layers, a phone can be lost or stolen. If you want your account to stay protected even then, a Xaman card is designed for exactly that.

With a Xaman card, your account's key is created inside the card's chip and never leaves it. No one ever sees it, not even you. There is no account secret to write down, and nothing anyone could trick you into sharing.

To sign a transaction, you hold the card against your phone. A thief who takes your phone still cannot sign anything without the card. With a Backup card stored somewhere separate, you keep access to your account even if one card is lost.&#x20;

To get the most out of your cards, see [_Best security practices for the Xaman cards_](../xaman-cards/best-security-practices-using-a-xaman-card.md).

### Connecting to websites, xApps, and QR codes

When you use Xaman with a website, an xApp, or a QR code, your account secret stays on your phone. The website or app sends Xaman a sign request, Xaman shows it to you, and nothing happens unless you approve it. When you do, Xaman signs on your phone and sends back only the signed transaction.

This keeps you in control, and it also places the final decision in your hands.

{% hint style="warning" %}
A sign request can do anything your account can do, including sending all your funds or changing who controls your account. A transaction you approve cannot be reversed. Read every sign request, and reject any you do not fully understand.
{% endhint %}

### Trust lines and tokens

Adding a trust line does not open your account to anyone. It cannot give anyone access to your XRP or let them sign for you. What it does is let your account hold a token, and tokens come with risks of their own that are worth knowing before you add one:

* **An issuer may be able to freeze its token.** Depending on the issuer's settings, you may then be unable to send or trade it.
* **An issuer may be able to take its token back.** If an issuer turned on clawback before it issued its token, it can take back that token, up to the balance you hold.
* **A token's name proves nothing.** Any issuer can give a token any name. A token called "RLUSD" from a different issuer is not the real RLUSD. The issuer identifies the token, not the name.

Before you add a token, see _T_[_oken vetting and the token warning_](../tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning.md)_._

### Unexpected payments and messages

You may sometimes receive a tiny payment you did not expect, often with a message attached. Anyone can send these to any account on the XRP Ledger, and the payment itself cannot harm your account. The message is the part to be careful with. Many are scams, so do not follow their links or contact the sender.

To learn more, see [_Spam on the XRP Ledger_](../scams-and-staying-safe/spam-on-the-xrp-ledger.md).

### Your account belongs to you

The XRP Ledger runs on independent servers around the world, so no single company or government can switch it off. No one can freeze or move the XRP in your account without your account secret, including XRPL Labs.

Your account does not depend on Xaman either. If you ever wanted to, you could use your account secret in another wallet that supports the XRP Ledger. See [_Moving your XRPL account to another wallet_](../your-accounts/importing-your-account/moving-your-xrpl-account-to-another-wallet.md). That is what self-custody means: your account is yours.

### In short

If you remember only four things from this article, make it these:

* Keep your phone updated, locked, and free of apps from outside the official stores.
* Never share your account secret with anyone, for any reason.
* Read every sign request before you approve it.
* Consider a Xaman card for large balances and long-term storage.

### Frequently asked questions

**Has Xaman been audited?**

Yes. See [Has Xaman been audited?](all-about-security/has-xaman-been-audited.md)

**Does my Xaman passcode protect my account on my other phones?**

No. The Xaman passcode protects the Xaman app on one phone, and each phone has its own. Your account secret works on any phone, which is why it needs to be protected and kept private.

**Is an account created in Xaman easier to guess than one created on an offline device?**

No. The number of possible account secrets is the same wherever the secret is created.

**If I contact Xaman support, will they ask for my account secret?**

Never. Xaman support never asks for your account secret, through the Xaman Support xApp or anywhere else. If anyone asks, they are trying to steal your funds. To reach us, use the [Xaman Support xApp](https://xaman.app/detect/xapp:xumm.support-md).

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Best security practices for the Xaman cards](../xaman-cards/best-security-practices-using-a-xaman-card.md)
* [Xaman cards](../xaman-cards/xaman-tangem-cards.md)
* [_Token vetting and the token warning_](../tokens-trust-lines-and-nfts/token-vetting-and-the-token-warning.md)
* [_Moving your XRPL account to another wallet_](../your-accounts/importing-your-account/moving-your-xrpl-account-to-another-wallet.md)
