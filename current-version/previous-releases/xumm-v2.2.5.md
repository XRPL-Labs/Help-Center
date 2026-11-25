# Xumm v2.2.5

### Please read these release notes carefully: some of the issues addressed have been reported by many users.

#### **Note: token filtering/sorting will be added to the next XUMM release.**

#### **Added in 2.2.5**

* **Fee selection: XUMM now automatically checks the XRP Ledger for elevated fees, selects the best network fee and allows users to select a fee level (low, medium or high).**
* Support for signing transactions involving `*Tickets**` (TicketBatch amendment).

#### **Improved in 2.2.5**

* Several performance improvements for accounts with many Trust Lines.
* **Transfer Rate** and **Transaction Fee** are now displayed in the **Payment Summary** screen (manual Send flow).
* When sending to an unactivated XRPL account, the destination account is now checked on the XRPForensics Advisory list as well.
* Improved displaying truncated amounts & currencies in the Event list. Currency codes containing 3 or 4 characters (length) are now always fully visible (untruncated).
* The **Swipe Button** (to confirm and sign a transaction) is now optimized for the visually impaired. More improvements for the visually impaired are on our 2022 roadmap 😉
* Rejected transactions (by XRP Ledger nodes) now also show a human readable message containing more information (if sent by the XRPL node rejecting the transaction).
* Improved user interface flickering when one would navigate really (really!) quickly between user interface elements/flows in XUMM.

#### **Fixed in 2.2.5**

* **Fixed a bug causing some (or all) TrustLines not to be displayed for accounts with a significant amount of TrustLines.**
* **Fixed a bug causing the Delete button to stay disabled for certain (or all) TrustLines for accounts with a significant amount of TrustLines.**
* **Fixed a bug causing XUMM to display an error when sending tokens to another XRPL account: XUMM would report the destination didn’t have the correct TrustLine setup, while the destination account in fact had that TrustLine setup already.**
* **Fixed a “Decimal Precision” error when using the Trust Line Exchange button.**
* When the **Event List** contained a Sign Request from an already past day, transactions (events) from more recent days were rendered in the Event List **after** the day the Sign Request was from, meaning the chronological order was broken. It could come across as if recent XRPL transactions weren’d being displayed. This would resolve after resolving the (older) Sign Request. **Sign Requests are now displayed chronological as well.**
* Fixed a condition causing XUMM to crash when a Tangem card would be imported for the first time (everything would work fine after).
* Fixed a bug causing a firmware error to be displayed when using the Tangem Multi Assets/currency cards.
* Fixed a bug causing XUMM failing to sign a Payment transaction when the transaction contained a Path field (custom DEX paths).
* Fixed a bug where values (amounts) were not being displayed correctly for Payment transactions to self (own account) containing custom Paths.

#### **For Developers in 2.2.5**

* Fixed MultiSign signer (payload) account response (returns correct MultiSign signature account).
* Implemented API Rate Limiting on a per endpoint / per app (if whitelisted) basis (when hit: returns a 429 HTTP status/error code).
* When switching between MAINNET and TESTNET, the displayed network (developer mode) didn’t update on the first switch.
* XUMM API now actively rejects payloads with invalid SignerEntries for SignerListSet transaction.
* XUMM API now actively rejects MultiSign payloads without **Fee** or **Sequence** pesent in the transaction template (payload).
