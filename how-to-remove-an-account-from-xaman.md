---
description: How to remove an account from Xaman
---

# How to remove an account from Xaman

Removing an account from Xaman deletes it from the device only. Your account still exists on the XRP Ledger with your funds, tokens, and transaction history intact. You can always access it again by importing your account secret back into Xaman.

{% hint style="info" %}
Before you remove an account, make sure you have its **account secret** (Secret Numbers, Family Seed, or Mnemonic) written down somewhere safe. It's also a good idea to check that it is the correct one for your account. See: [How to test your Account Secret](learning-more-about-xaman/how-to-test-your-account-secret.md)&#x20;
{% endhint %}

***

### Steps

1. Open Xaman and tap **Settings** (gear icon, bottom tab).
2. Tap **Accounts**.
3. Tap **Edit** on the account you want to remove.
4. Scroll to the bottom and tap **Remove from Xaman** (red button).
5.  A warning appears:

    > **Warning** Your account will be deleted permanently from Xaman. Are you sure?
6. **Full-access accounts** (imported with a secret or a Tangem card): you'll be asked to enter your 6-digit passcode. Biometrics are not offered at this step. **Read-only accounts:** no passcode is needed.
7. Tap **Yes, I'm sure**.

The account is removed and you're returned to the Accounts list.

***

### What gets removed from your device

| Item                               | Full access | Read-only         |
| ---------------------------------- | ----------- | ----------------- |
| Account record (address, label)    | Removed     | Removed           |
| Trust lines                        | Removed     | Removed           |
| Encrypted private key (keychain)   | Removed     | N/A (none stored) |
| Push notifications for the address | Disabled    | Disabled          |

### What stays

* **Everything on-chain.** Your XRP balance, tokens, and full transaction history remain on the XRP Ledger. Removing the account from Xaman does not touch any of it.
* **Your account secret.** It was never stored in a recoverable form on the device. It's the paper (or offline note) you wrote down at creation.
* **Other accounts in Xaman.** Removing one account does not affect the others.

### How to get the account back

Open Xaman, tap **+ Add account** → **Import an existing account**, and enter the same account secret (Secret Numbers, Family Seed, or Mnemonic). You'll be logged back into the **same** r-address with the same balance and history. It's not a new account — it's the same one.

For Tangem card accounts, re-pair the card the same way you did originally (see [Importing your account](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account)).

***

### Removing an account vs. uninstalling the app

|                        | Remove an account          | Uninstall the app                     |
| ---------------------- | -------------------------- | ------------------------------------- |
| Scope                  | One account on this device | All accounts, all data on this device |
| Funds on the ledger    | Unaffected                 | Unaffected                            |
| Address Book           | Unaffected                 | Wiped                                 |
| Support tickets in-app | Unaffected                 | No longer reachable                   |
| Re-import needed       | Only the removed account   | Every account                         |
| Passcode               | Unchanged                  | Reset on reinstall                    |

If you only need to get rid of one account, use **Remove from Xaman**. If you're setting up a fresh install, see [How to reset the 6 digit passcode](https://help.xaman.app/app/learning-more-about-xaman/how-to-reset-the-6-digit-passcode) for the uninstall/reinstall path.

***

### Frequently Asked Questions

**Will I lose my funds?** \
No. Removing an account from Xaman is a local operation. Your XRP and tokens stay in your account on the XRP Ledger. The account, balance, and history are all still there, you just can't see them from Xaman until you re-import your account secret.

**Can I undo the removal?**\
No. There's no "undo" option or trash bin. But because nothing on-chain is affected, you can re-import the account at any time with its secret and everything comes back.

**Do I need my passcode to remove an account?**\
Full-access accounts (imported with an account secret or a Xaman card): yes, the app asks for your 6-digit passcode. Read-only accounts: no.

**What happens to my transaction history?**\
Transaction history lives on the XRP Ledger, not in the app. It's not deleted. If you re-import the account, the full history will be visible again.

**Does removing a Xaman card account affect the card?**\
No. Neither the card itself nor the account is affected. You can re-pair it to Xaman at any time.

**I removed an account and now I can't find its address. Is it gone?**\
The address is gone from your Xaman app, but the account still exists on the XRP Ledger. If you have the account secret for the account, you can re-import it if you like. See: [Importing a Xaman card](getting-started-with-xaman/importing-your-account/...a-xumm-tangem-card.md)
