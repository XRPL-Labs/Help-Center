---
description: >-
  How much control each access level gives you, and where your account secret
  lives.
---

# What do "Full" and "Read Only" mean in Xaman?

**The access level of an account decides what Xaman can do with it. This article explains the two levels, where your account secret is stored, and why an account that says Full may still not be able to sign.**

#### The two access levels

When you add an account to Xaman, you choose an access level. There are two:

* **Full** : Xaman can sign transactions from this account. You can send from it.
* **Read Only** : Xaman can view this account but cannot sign from it. You can receive into it, but you cannot send from it unless a regular key gives it a way to sign (see below).

You see this label next to each account in the **Accounts** list.

#### Where is your account secret?

Where the account secret is stored depends on how you added the account.

**Your account is on an Xaman card (Tangem)**

The account secret is created and stored on the card. It never enters the app. When you sign, you tap the card to your phone and the card signs. This is why a card account is always shown as **Full** : it can sign, as long as you have the card.

**You imported your account secret (secret numbers, family seed, mnemonic, or hex)**

If you chose **Full**, Xaman stores your account secret in the app, encrypted. When you sign, Xaman uses that stored account secret to sign on your mobile device. You do not need anything else.

If you chose **Read Only**, Xaman does not store an account secret for this account. It can show your balance and activity, but it cannot sign from it.

#### Why might an account that says "Full" not be able to send?

There is one important case. Every XRP Ledger account has a master key. You can switch the master key off. When you do, the account shows a **Master Disabled** state, and the master key can no longer sign for the account.

When the master key is off, the account signs with its regular key (or its multisig list) instead. The XRP Ledger keeps at least one signing method on every account, so a **Master Disabled** account always has a regular key or a multisig list set.

In Xaman, a **Full** account that is **Master Disabled** can only sign through its regular key, and only if that regular key account is also added to Xaman as **Full**. If the regular key is not added, or is added as **Read Only**, Xaman cannot sign for it, even though the account says Full.

#### What is a regular key?

A regular key is a second signing key you can set on an XRP Ledger account.&#x20;

* If your account is **Master Disabled**, a regular key is the only way it can still sign.
* Xaman can use a regular key to sign for another account, but only if the regular key account is also added to Xaman as **Full**.
* A **Read Only** account can also sign this way, if its regular key is added to Xaman as **Full**.

Setting a regular key is a transaction on the XRP Ledger. If you are not sure how to set one, or you need help working out which account holds the regular key for your account, contact support via the [**Xaman Support xApp**](https://xaman.app/detect/xapp:xumm.support-md) and we will walk you through it.

#### What to check if you cannot send from an account

1. Open the **Accounts** list and look at the access level. Is it **Full** or **Read Only**?
2. If it is **Read Only**, you cannot send from it unless a regular key is added to Xaman as **Full**.
3. If it is **Full** but you get a signing error, check whether the account is **Master Disabled**.
4. If it is **Master Disabled**, find the regular key for the account and add that account to Xaman as **Full**.
5. If you do not have the regular key, or you did not make the **Master Disabled** change yourself, contact support. Do not try to move funds from a device or app you do not trust.

#### Frequently asked questions

**Can I change an account from Read Only to Full?**

You can upgrade an account if you have its account secret. If you do not have the account secret for that account, you cannot upgrade it to Full access. You can add the account again as Full by importing its account secret.

**My Xaman card account says Full. Can I lose access to it?**

You can lose the ability to sign from it if you lose the card and do not have a backup card. If the account is also **Master Disabled** and there is no regular key added to Xaman, then losing the card means the account can no longer sign. Keep a backup card and keep a regular key set if the account holds a large balance.

#### See also

* [I've lost my account secret!](ive-lost-my-account-secret.md)
* [How to import your Xaman card](../getting-started-with-xaman/importing-your-account/...a-xaman-tangem-card.md)

<br>
