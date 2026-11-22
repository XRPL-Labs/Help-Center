---
description: How to send XRP from Luno to Xaman (deposit)
---

# How to Send XRP from Luno

Sending XRP from Luno to your Xaman account is a single send flow, but it has one prerequisite that takes time. Luno disables the option to send crypto by default, and after you enable it, a waiting period applies. In some countries that period is up to 30 days. Start with the enablement step first, so the waiting period runs while you read the rest.

#### Before you start

* A Luno account that holds XRP
* The **Send cryptocurrency** option enabled in Luno (see Step 1)
* Your Xaman **r-address** (starts with `r...`)
* New, unactivated XRPL accounts require an activation reserve of **1 XRP** to exist on-chain. That first 1 XRP is not spendable. See [How to activate a new XRP Ledger account](https://help.xaman.app/app/getting-started-with-xaman/how-to-activate-a-new-xrpl-account).

#### Step 1: Enable sending on Luno (one time)

For security, Luno disables crypto sends by default.

1. Open the Luno app and sign in.
2. Go to **Profile**, then **Security**.
3. Turn on **Send cryptocurrency**. Alternatively, tap **SEND** anywhere in the app and accept the terms when asked.
4. Luno starts a waiting period. It is usually 24 hours, but in some supported countries it is up to 30 days. The app shows you the date the option will activate, and you receive an email when it activates.

> **Note:** Do this step first. The waiting period starts when you enable the option, not when you send.

#### Step 2: Find your Xaman r-address

1. Open Xaman.
2. Your r-address is on the account card at the top of the home screen, under your account name.
3. Tap **Receive** to copy the address or share the QR code.

> **No destination tag needed.** Your Xaman account is self custodial and does not use a destination tag. If the Luno send flow shows a tag or memo field, leave it empty. Luno's own help center confirms that Luno does not enforce a destination tag for sends to external wallets. (Uncertain: whether the Luno send flow shows a tag field at all for external XRP sends.)

#### Step 3: Send the XRP from Luno

1. Sign in to the Luno app.
2. Select **Portfolio**.
3. Select your **Ripple (XRP)** wallet.
4. Tap **SEND**.
5. If Luno asks you to choose a network, choose **Ripple**. Do not choose any other network. (Verified: Luno's supported assets list names the XRP network "Ripple".)
6. Paste your Xaman r-address and tap **NEXT**. Alternative: tap the QR code icon at the top right and scan the QR code from your Xaman Receive screen.
7. If the Travel Rule applies in your country, answer the questions Luno asks.
8. Enter the amount and tap **NEXT**.
9. Review the amount and the network fee, then tap **CONFIRM**.

Your XRP should appear in Xaman within a minute or two. The XRP Ledger itself confirms in about 4 seconds. Any delay beyond that is on Luno's side. See [Sending XRP to Xaman](https://help.xaman.app/app/getting-started-with-xaman/sending-xrp-to-xaman).

#### Things to keep in mind

* **Fees:** Luno charges a dynamic network fee based on network activity. It is displayed before you confirm.
* **Limits:** Send limits depend on your country and your verification level. Check the limits screen in the Luno app for your region.
* **Test send:** Luno recommends sending a small test amount first to confirm the transaction works.
* **Irreversible:** Once confirmed, the transfer cannot be reversed. Double check the r-address character by character before you confirm.
* **If it does not arrive:** Contact Luno support with the transaction ID. Xaman cannot see the funds until Luno submits the transaction to the XRP Ledger.
