---
description: What to do when you cannot find your Secret Numbers, Family Seed, or Mnemonic
---

# I've lost my account secret

Losing track of your account secret is a frightening moment, so start with the good news: your account is not gone. Your XRP and tokens are still on the XRP Ledger (XRPL), exactly where you left them. What you need is a way to sign for the account again. This article walks you through every option, starting with the most likely one.

### What you see

You cannot find the place where you wrote down your account secret. You may still have the account in Xaman on your phone, or you may have lost the phone too. Some people do have a secret, but when they enter it in Xaman, it opens a different account with no balance. If that sounds like you, see _I entered my account secret, but Xaman opened a different account_ under _Frequently asked questions_.

### Why it happens

Your account secret is the only key to your account, and it comes in one of these forms:

* **Secret Numbers:** eight rows of six digits, labeled A to H, if you created the account in Xaman. The last digit of each row is a check digit, so Xaman tells you straight away if a row is mistyped.
* **Family Seed:** a code that starts with the letter "s".
* **Mnemonic:** a list of 12, 16, or 24 words.
* **Xaman card:** the secret is created on the card's chip and never leaves it, so there is nothing to write down. The card itself is the key.

The XRP Ledger has no administrator and no back door, so nobody can look up or reset an account secret. Xaman is a self-custody[^1] wallet, which means only you ever held the secret, and we cannot recover it, freeze the account, or reverse a transaction. Xaman also never shows a secret again after setup, so that a thief who takes your phone cannot read it. [_Can I view/export my account secret?_](can-i-view-export-my-account-secret.md) explains that choice.

### What you can do

Work through these in order. The first one that fits your situation is usually the answer.

#### Move to a new account while you can still sign

If your account still has **Full access** in Xaman, on this phone or any other device you have, you are in good shape. You can create a new account, write down its secret carefully this time, and move everything across.

1. Tap **Settings** > **Accounts**.
2. Tap **+ Add account**, then **+Create a new account**.
3. Follow the steps, and write down the new account's Secret Numbers.
4. Send XRP from your old account to the new one. The first payment must cover the new account's reserve[^2].
5. On the new account, add a [trust line](#user-content-fn-3)[^3] for each token you hold.
6. Send your tokens, then the rest of your XRP, to the new account.

Your funds have moved once they show in the new account. NFTs move with a transfer through the marketplace or app you use for them. Once the old account is empty, you can delete it to get back most of its reserve, with _How to delete an XRPL account_.

#### If your account is on a Xaman card

The card is the key, so there are no Secret Numbers to lose. If you still have the card, tap it to sign as usual, and keep it somewhere safe. If the card is lost or damaged,[ _Lost or damaged cards_](../xaman-cards/lost-or-damaged-cards.md) explains what to do, including how a Backup card gets you back in.

#### If your account has a regular key

If you once set a [regular key](#user-content-fn-4)[^4], the account it belongs to can still sign for your account. Add your account to Xaman in **Read only** mode, using its r-address[^5], and sign with the regular key account when Xaman asks. Then move your funds to a new account, as described above. _How to Rekey an XRP Ledger (XRPL) Account_ explains how regular keys work.

#### If someone else has a copy

Think back to when you created the account. Did you share the secret with a family member, or did anyone else keep a copy? If they did, import it into Xaman to get back in. Then move your funds to a new account, since anyone who has a copy of a secret also controls the account.

#### If you created the account in another wallet

Some wallets and platforms have their own recovery options. Contact the one you used to create the account and ask what they offer. Xaman cannot recover a secret that another app created.

#### If your account came from the CasinoCoin swap

Accounts created during the CasinoCoin swap have their own recovery steps. [_How to recover a Casinocoin (CSC) account_](../your-accounts/importing-your-account/how-to-recover-a-casinocoin-csc-account.md) walks you through them.

#### If none of these fit

Look again wherever you might have stored it, such as a notebook, a safe, or an old phone. If the secret is truly gone, the account stays on the XRP Ledger, but nobody can sign for it, including us. We know how hard that is to hear.

{% hint style="danger" %}
People will offer to recover your account secret for a fee. Nobody can do that, from your r-address or anything else, and they will take your money or your remaining funds. Do not pay them, do not download anything they send, and never share an account secret.
{% endhint %}

If you are unsure which option fits, we are happy to help you work it out. Our support team will never ask for your account secret. Anyone who asks for it is trying to take your funds, so never share it.

<a href="https://xaman.app/detect/xapp:xumm.support-md" class="button primary">Open the Xaman Support xApp</a>

### Frequently asked questions

**Can Xaman show me my account secret?**

No. Xaman never displays an account secret after setup, so a thief who takes your phone cannot read it either. If you can still sign, the first option under _What you can do_ is the way forward.

**I can prove the account is mine with ID. Does that not make a difference?**

Sadly, no. The XRP Ledger has no central authority to show your ID to, and identity checks (KYC) never link your details to your account secret. The only thing that can sign for an account is its key.

**My bank can reset my password. Why is Xaman unable to reset my account secret?**

A bank or an exchange holds your money for you, in an account it created and controls, so it can reset your password. A self-custody account works differently. You created it directly on the XRP Ledger, with no company in the middle and no copy of your key anywhere else. Xaman helps you use that key, but it never had a copy of it.

**I entered my account secret, but Xaman opened a different account. Why?**

Picture a building with about 340 undecillion apartments, one for every possible account secret, each with its own lock. Every secret is a key that opens exactly one apartment, and Xaman goes straight to the one your key opens. If that apartment is empty, the key belongs to a different account than the one you are looking for, however sure you are of it. A single mistyped character, a word from the wrong list, or a secret from another account all lead to a different, empty account.

### See also

* [Can I view/export my account secret?](can-i-view-export-my-account-secret.md)
* [How to Test or Verify your Account Secret](how-to-test-your-account-secret.md)
* [Lost or damaged cards](../xaman-cards/lost-or-damaged-cards.md)
* [Rekeying your XRP Ledger account](how-to-rekey-your-account.md)
* [How to delete an XRPL account](../your-accounts/importing-your-account/how-to-delete-an-xrpl-account.md)
* [How to recover a Casinocoin (CSC) account](../your-accounts/importing-your-account/how-to-recover-a-casinocoin-csc-account.md)
* [Recovery scams](../scams-and-staying-safe/recovery-scams.md)



[^1]: You alone hold the keys to your account. No company, including Xaman, can move, freeze, or recover your funds for you.

[^2]: XRP that every active XRP Ledger account must keep and cannot spend. The network sets the amount, and it can change.

[^3]: Your account's permission to hold a specific token from a specific issuer. Each one adds to your reserve while it exists.

[^4]: A second key that can sign for your account, such as a Backup card.

[^5]: Your account's address on the XRP Ledger. It always starts with "r", and it is safe to share.
