---
description: How to let a second account sign for yours, and when it makes sense
---

# Rekeying your XRP Ledger account

Every XRP Ledger (XRPL) account starts with one key, its [master key](#user-content-fn-1)[^1], which comes from its account secret. Rekeying adds a second key, called a regular key, that can sign for the account as well. The regular key belongs to another account you control, so you can approve transactions for your main account from that second account. Your XRP and tokens stay exactly where they are.

People rekey for two main reasons. Some want a second way to sign, kept somewhere separate, so that losing one key does not lock them out. If you use Xaman cards, you have seen this already: your Backup card is a regular key for your Primary card’s account. Others rekey because they believe their account secret has leaked, and want to take signing away from it, which takes a second step after this one.

### Before you get started

* Your main account in Xaman, with **Full access** and enough XRP to pay the network fee.
* A second account in Xaman, also with **Full access**. It does not need any XRP, and it does not need to be activated.

{% hint style="danger" %}
A regular key can sign anything for your account, including sending all of your funds away. Anyone who asks you to set a regular key to their address is trying to take your account. Only set a regular key to an account you own and control in Xaman.
{% endhint %}

### Set a regular key

Xaman has no button for this on purpose. A regular key gives full control of an account, and scammers often try to talk people into setting one. To set a regular key, you use XRP Ledger Services, the site Xaman has pointed people to for years, made by an independent XRP Ledger developer. It prepares the transaction and sends it to Xaman, where you check it and sign. Xaman treats it as security sensitive, so before it shows the details, it asks a few questions about how you came to be signing. If someone else is walking you through this, stop and close the request.

These steps use your phone, with XRP Ledger Services open in your phone’s web browser.

1. In Xaman, switch to your main account on the **Home** screen.
2. In your phone’s web browser, go to [XRP Ledger Services](https://xrpl.services/).
3. Open **Set Regular Key**.
4. In **XRPL address which will be able to sign transactions**, enter your second account’s r-address. Check it character by character.
5. Tap **Send Set Regular Key to Xaman**.
6. Check the address under **Set RegularKey to**, then tap **Confirm**. Xaman opens.
7. Enter your passcode or use biometrics. The **Review transaction** screen opens.
8. Answer each safety question.
9. Check that **Sign with** shows your main account, and **Regular Key** shows your second account’s r-address.
10. Slide to accept.

### Check that it worked

Open **Settings** > **Accounts**. Under your second account's name, the status line now reads **Regular key for** followed by your main account's name. From now on, you can sign for your main account with either account.

### If you rekeyed because your account secret leaked

A regular key on its own does not lock anyone out. The master key keeps working until you turn it off, so anyone who has your account secret can still sign anything for your account. They could send your funds away, or replace your regular key with one of their own. If they then turned off the master key, you would be locked out of your account for good. Your next step is to disable the master key, as soon as you can, with [_How to disable the master key_](how-to-disable-the-master-key.md).&#x20;

If you think someone is already using your account secret, moving your funds to a new account is often the safest choice, since it does not depend on getting there first. [_Account present on another device_](all-about-security/account-present-on-another-device.md) explains both options.

### Change or remove a regular key

The XRP Ledger allows only one regular key per account. Setting a new one replaces the old one straight away, and the old account can no longer sign. To remove a regular key, follow the first three steps, then tap **Delete Regular Key** instead of entering an address. Confirm and sign the request the same way. You can sign the removal with your main account or with the regular key account.

The XRP Ledger also refuses to remove the regular key when it is the only way left to sign. That happens when the master key is disabled and no multi-signing setup is in place. Removing the key would lock you out for good, so turn the master key back on first, with [_How to enable the Master Key_](how-to-enable-the-master-key.md). These are rules of the XRP Ledger itself, not of Xaman, so they work the same way in every wallet.

### Frequently asked questions

**Can I still use my master key after rekeying?**

Yes. Rekeying adds a second key alongside the first, so your master key keeps working until you choose to disable it. Your main account stays **Full access** in Xaman, and you can go on signing with it exactly as before.

**Does the second account need XRP?**

No. It only signs for your main account, so it does not need to be activated. The network fee is paid by your main account.

**If someone else has my account secret, can they still use it after I rekey?**

Yes, until you disable the master key. They can sign anything, replace your regular key with their own, and then turn off the master key to lock you out. _If you rekeyed because your account secret leaked_ explains what to do, and why moving your funds is often the safer choice.

**Can the regular key move my funds?**

Yes, and that is why it matters who holds it. A regular key can sign any transaction for your account, so set it only to an account you control.

### See also

* [How to disable the master key](how-to-disable-the-master-key.md)
* [Account present on another device](all-about-security/account-present-on-another-device.md)
* [Security in Xaman](security-in-xaman.md)
* [How to rekey a Xahau account](../xahau/how-to-rekey-a-xahau-account.md)

[^1]: The key created with your account, from its account secret. It can be turned off once another key is in place.
