---
description: How to Send XRP from Gemini to Xaman (deposit)
---

# How to Send XRP from Gemini

Sending XRP from Gemini to your Xaman account is a single withdrawal flow. You send from Gemini to your r-address on the XRP Ledger. No destination tag is needed.

#### Before you start

* A Gemini account that holds XRP and is fully verified. Gemini restricts withdrawals for accounts that are not fully verified.
* Your Xaman **r-address** (starts with `r...`)
* Two-factor authentication set up on Gemini (Authy or SMS). Gemini requires a 2FA approval for every withdrawal.
* New, unactivated XRPL accounts require an activation reserve of **1 XRP** to exist on-chain. That first 1 XRP is not spendable. See [How to activate a new XRP Ledger account](https://help.xaman.app/app/getting-started-with-xaman/how-to-activate-a-new-xrpl-account).

#### Step 1: Find your Xaman r-address

1. Open Xaman.
2. Your r-address is on the account card at the top of the home screen, under your account name.
3. Tap **Receive** to copy the address or show the QR code.

> **No destination tag needed.** Your Xaman account is self custodial and does not use a destination tag. If Gemini shows a Destination Tag or Memo field, leave it empty. If the form will not accept an empty value, enter 1234. (Uncertain: whether the Gemini withdrawal form shows a tag field for XRP. The official Gemini article does not mention one.)

#### Step 2: Withdraw XRP from Gemini

The steps below match the official Gemini help article "How do I withdraw crypto from my Gemini account".

1. Open the Gemini website and go to the [withdrawal page](https://exchange.gemini.com/transfer/withdraw). Alternative: in the Gemini app, open your XRP wallet and choose the withdraw option. (Uncertain: exact app menu path.)
2. Select **XRP** from the currency dropdown.
3. Enter **your Xaman r-address** as the destination address. Double check the address character by character.
4. Enter the **amount** you want to send.
5. Review the transfer details, then select **Request Withdrawal**.
6. Approve the withdrawal with your two-factor authentication. If you use the Authy app, approve within 4 minutes of requesting the withdrawal. If you use SMS, enter the code from the text message.

**UK, EU, and EEA customers:** Gemini uses a different withdrawal process in these regions. See the [UK instructions](https://support.gemini.com/hc/en-us/articles/20471905178011-How-do-I-withdraw-crypto-from-my-Gemini-account-For-UK-customers-) and the [EU/EEA instructions](https://support.gemini.com/hc/en-us/articles/31698227634715-How-do-I-withdraw-crypto-from-my-Gemini-account-For-EU-EEA-customers) on the Gemini help center.

#### What happens after you send

* The XRP Ledger confirms transactions in about 4 seconds. After Gemini submits your withdrawal, your XRP should appear in Xaman within a minute or two.
* Gemini applies withdrawal holds in some cases. The documented triggers: a sign-in from a new device, a pending bank (ACH) transfer, a pending debit card transfer (24 hour hold), a recent password reset (72 hour hold), a new Authy device (72 hour hold), an unverified account, pending verification, or an open sell limit order. See the [Gemini article on withdrawal restrictions](https://support.gemini.com/hc/en-us/articles/115005752503-Why-can-t-I-withdraw-my-crypto).
* If your XRP does not arrive within a few minutes, contact Gemini support with your withdrawal reference. Xaman cannot see the funds until Gemini submits the transaction to the XRP Ledger.

#### Things to keep in mind

* **Fees and limits:** Gemini charges a withdrawal fee and enforces minimum withdrawal amounts. These depend on your region and can change. Check the fee shown on the review screen before you confirm. (Uncertain: current XRP fee and minimum in your region.)
* **Activation reserve:** If your Xaman account is new, the first 1 XRP you send is held as the account reserve and is not spendable. Send more than 1 XRP if you want spendable XRP left over.
* **Irreversible:** Once confirmed, the transfer cannot be reversed.
* **Not an endorsement:** We list exchanges so you can find the source of your funds. We do not support or endorse Gemini in any way. Each exchange has its own rules and fee structures which you should fully understand before you use it.
