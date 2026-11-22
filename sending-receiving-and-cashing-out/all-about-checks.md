# All about Checks

#### **What is a Check?**

A Check is a deferred payment on the XRP Ledger. One person writes you a Check for a set amount. No money moves at this point. The money only moves when you **cash** the Check.

Think of it like a paper check from a bank. The sender is promising to pay you up to a certain amount. You decide when to cash it.

A Check is different from a normal payment. With a normal payment, the money leaves the sender immediately. With a Check, the sender keeps control of the funds until you cash the Check.

#### **How a Check works**

Here is the life of a Check, step by step:

* **The sender creates the Check.** This names you as the recipient and sets the maximum amount they agree to pay.
* **You receive the Check.** The Check now lives on the XRP Ledger, waiting for you.
* **You cash the Check.** When you cash it, the XRP Ledger pulls the funds from the sender and sends them to you.
* **The Check is removed.** Once you cash it, the Check disappears from the ledger.

If the sender does not have enough money when you cash the Check, the cash fails. The Check stays on the ledger, and you can try again later. You can keep retrying until the Check expires.

Some Checks have an expiration date. Some do not. A Check without an expiration date stays on the ledger until someone cancels it.

#### **A Check can be for XRP or for a token**

A Check can be written for XRP or for an issued token, such as a stablecoin. This matters because of trust lines.

* **A Check for XRP.** Nothing to set up. Cash it and the XRP arrives.
* **A Check for a token.** You must be able to hold that token. On the live XRP Ledger, cashing a token Check sets up the needed trust line for you automatically. In most cases you do not need to create the trust line yourself first.
* **A token you issue yourself.** If the Check is for a token that your own account issues, you do not need a trust line at all.

If a token Check fails to cash, see the section below on why a cash can fail. A common cause is that your account cannot yet hold the token. In that case, create a trust line to the token's issuer and try again. See [How to create a Trust Line](http://./all-about-scams/how-to-create-a-trust-line.md).

#### **How to find a Check in Xaman**

A Check that someone has sent you shows up in your **Events** list.

1. Tap the **Events** button on the home screen.
2. Tap the **Requests** tab.
3. Find the Check. From there you can cash it or cancel it.

If you see a red dot next to the **Events** button, a Check (or another item) is waiting in **Requests** for your attention.

#### **How to cash a Check**

When you open the Check in the **Requests** tab, you cash it by confirming the amount. You have two options:

* **Cash the exact amount.** You enter the exact amount you want, up to the Check maximum.
* **Cash a flexible amount.** You enter a minimum amount. The XRP Ledger delivers as much as possible, up to the Check maximum, as long as it meets your minimum.

When you sign, the XRP Ledger tries to move the funds from the sender to you. If the sender has enough, the funds arrive and the Check is gone. If the sender does not have enough, the cash fails and the Check stays.

#### **Why a cash can fail**

A failed cash does not hurt you. The Check remains, and you can retry. Here are the common reasons a cash fails:

| What you may see                   | What it means                                                                                   | What to do                                             |
| ---------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| `tecPATH_PARTIAL` or `tecPATH_DRY` | There is no path to deliver the token to you. This usually means you cannot hold the token yet. | Create a trust line to the token's issuer, then retry. |
| `tecEXPIRED`                       | The Check has expired.                                                                          | It can no longer be cashed. Someone can cancel it.     |
| `tecNO_PERMISSION`                 | You are not the recipient named on the Check.                                                   | Only the named recipient can cash this Check.          |
| The sender is low on funds         | The sender cannot pay the full amount right now.                                                | Wait and retry, or cash a smaller flexible amount.     |

If the Check is for a token with no holders and no visible backing, it is often a scam token. No amount of trust line setup will make an empty token deliver real value. Read the safety note below before you act.

#### **Cancelling a Check**

A Check can be cancelled at any time. Cancelling removes the Check from the ledger without moving any money.

* **Before it expires.** Only the sender or the recipient can cancel it.
* **After it expires.** Any account can cancel it.

You can cancel a Check you have received from the same **Requests** tab where you would cash it. Cancelling is useful if a Check was sent to you by mistake, or if it is a scam Check you do not want to keep around.

#### **A word on safety**

A Check is not money in your pocket until you cash it. Keep these points in mind:

* **Do not send anything to the person who sent you a Check.** A Check is a promise to pay you, not a request to pay them.
* **Watch for the advance fee pattern.** A stranger sends you a Check for an unusual or unknown token, then asks you to send XRP, pay a "fee," or release a payment so they can "claim" theirs. This is a common scam. Stop and check the token first.
* **Check the token before you cash.** If the token has no holders, no issuer you recognize, or no backing, treat the Check with strong suspicion.
* **When in doubt, ask.** Open a ticket with Xaman Support. We can look at the Check and the token on the ledger before you act.

#### **Frequently Asked Questions**

**Do I need a trust line to cash a Check?**

For a Check written in XRP, no. For a Check written in a token, you must be able to hold that token. On the live network, cashing the Check usually sets up the trust line for you. If the cash fails, create a trust line to the token's issuer and try again.

**I cashed a Check and it failed. Can I try again?**

Yes. A failed cash does not remove the Check. You can retry until the Check expires. If it keeps failing, check whether the sender has funds and whether your account can hold the token.

**Can I stop receiving Checks?**

Yes. An account can block incoming Checks with the `DisallowIncomingCheck` setting. If you want to enable this, contact Xaman Support. We will walk you through it.

**What happens to a Check if I do nothing?**

If the Check has no expiration date, it stays on the ledger until the sender or you cancel it. If it has an expiration date, it expires and can no longer be cashed. Either way, it does not affect your other balances.
