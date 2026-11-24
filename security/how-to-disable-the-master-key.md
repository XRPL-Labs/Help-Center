---
description: How to stop your account secret from signing, once a regular key is in place
---

# Disabling your master key

Your master key is the key that comes from your [account secret](#user-content-fn-1)[^1]. Until you change something, it is the only thing that can sign for your account. Once you have set a [regular key](#user-content-fn-2)[^2], you can turn the master key off, so the regular key becomes the only way to sign. People do this when they want their account secret to stop working, for example because they think it has leaked, or because they want all signing to happen from one account they keep somewhere safer.

It is a powerful change, so it pays to slow down. After this, your account depends entirely on the regular key account, and the steps below include checking that it is ready before you start.

### Before you get started

* A regular key already set on your account, belonging to another account you hold with **Full access** in Xaman. [_Rekeying your XRP Ledger account_](how-to-rekey-your-account.md) explains how.
* Your main account in Xaman with **Full access**, since only the master key itself can turn the master key off.
* Enough XRP in your main account to pay the [network fee](#user-content-fn-3)[^3].
* The regular key account's secret written down and tested, with [_How to Test or Verify your Account Secret_](how-to-test-your-account-secret.md).

{% hint style="danger" %}
Once the master key is off, only your regular key account can sign for your account. If you lose that account's secret too, no one can ever sign for your account again, including us. Test the regular key account's secret before you start.
{% endhint %}

### Disable the master key

Xaman has no button for this on purpose, just like setting a regular key. You use XRP Ledger Services, the site Xaman has pointed people to for years, made by an independent XRP Ledger developer. It prepares the transaction and sends it to Xaman, where you check it and sign. These steps use your phone, with XRP Ledger Services open in your phone's web browser.

1. In Xaman, switch to your main account on the **Home** screen.
2. In your phone's web browser, go to [XRP Ledger Services](https://xrpl.services/).
3. Open **Account Set**.
4. Select **Disable Master Key**.
5. Tap **Send Account Settings to Xaman**.
6. Check the summary, then tap **Confirm**. Xaman opens.
7. Enter your passcode or use biometrics. The **Review transaction** screen opens.
8. Check that **Sign with** shows your main account.
9. Read the **WARNING** and **DANGER** notes under **Memo**
10. Slide to accept.

### Check that it worked

Open **Settings** > **Accounts**. Your main account's status line now reads **Read only (Master key disabled)**. From now on, your regular key account signs for your main account, and your account secret no longer can.

### Turn the master key back on

If you change your mind, you can turn the master key back on, signing with your regular key account. The master key cannot turn itself back on, since it no longer signs. [_How to enable the Master Key_](how-to-enable-the-master-key.md) explains how.

### If your account secret has leaked

Disabling the master key only protects you if you get there first. Anyone who has your account secret can set their own regular key, or turn the master key off themselves, and lock you out. If you think someone is already using your secret, moving your funds to a new account is often the safest choice, since it does not depend on winning that race. [_Account present on another device_](all-about-security/account-present-on-another-device.md) explains both options.

### Frequently asked questions

**Should I still keep my account secret after disabling the master key?**

Yes. It no longer signs while the master key is off, but it works again the moment the master key is turned back on. Keep it as safe as before.

**What happens if I lose the regular key account too?**

Your account would be locked for good, with your funds still in it. No one can sign for it again, including us, which is why testing the regular key account's secret comes first.

**Can I disable the master key without a regular key?**

No. The XRP Ledger refuses, since it would leave the account with no way to sign. You need a regular key, or a multi-signing setup, in place first. These are rules of the XRP Ledger itself, not of Xaman.

### See also

* [Rekeying your XRP Ledger account](how-to-rekey-your-account.md)
* [How to enable the Master Key](how-to-enable-the-master-key.md)
* [How to Test or Verify your Account Secret](how-to-test-your-account-secret.md)
* [Account present on another device](all-about-security/account-present-on-another-device.md)
* [Security in Xaman](security-in-xaman.md)

[^1]: The secret that controls your account, as Secret Numbers, a Family Seed, or a Mnemonic. Never share it with anyone.

[^2]: A second key that can sign for your account, such as a Backup card.

[^3]: A tiny amount of XRP paid with every transaction. It is destroyed, not paid to anyone, which protects the network from spam.
