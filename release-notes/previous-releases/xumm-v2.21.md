# Xumm v2.21

#### Depending on your OS settings, your device may or may not auto-update. Check your App / Play store for the latest version (2.2.0).

#### Fixed in the 2.2.1 patch release

* **Android / iOS** - Fixed a bug where XUMM could crash when opening an item if visiting: Events - Planned tab - open a planned event.
* **Android** - Fixed Tangem card support: scanning a Tangem card didn’t work properly.
* **Android** - Fixed a (really) rare condition causing XUMM to crash on Android devices when an overlay dialog was displayed.

#### Added

* **XUMM now supports network based reserve calulation. This means the current reserves on the XRP Ledger mainnet of 10 XRP (account) and 2 XRP (object, TrustLine / Escrow / Offer / …) will be respected.** If (in the future) the network reserves change again, XUMM will automatically adapt.
* When adding a token (TrustLine) to your account, XUMM now shows a warning message: _XRPL Labs / XUMM does not endorse any token or issuer. Only proceed if you trust the issuer._
* When a token (TrustLine) is added to your account due to a trade on the DEX (Decentralized Exchange), the TrustLine limit is zero (0). This allows you to hold the token, but doesn’t allow others to send this token to you. XUMM now shows an info icon & one tap fix on a per token (TrustLine) basis (on the XUMM home screen), helping you to configure the (on ledger) TrustLine limit.

#### Improved / Changed

* **Improved (easier) account r-address sharing: tapping your r-address / pressing the Request button on the XUMM home screen now opens a dialog to easily view/copy/share your r-address (text / QR / share dialog).** The original XUMM Payment Request link generation can now be accessed from this new flow with a Create payment request link button.
* If your account is **below the XRP Ledger reserve requirement**, a negative balance will now be displayed at the XUMM home screen, making it clear that the first XRP deposited will go to satisfying the XRP Ledger reserve instead of your spendable balance.
* Improved network fee determination: if connected to a busy XRP Ledger node, the transaction fee is now based on network load instead of the individual (connected) node load.
* Fixed a bug where, if on a Transaction (Event) detail page, a push notification with a Sign Request was received and tapped (opened), one could not navigate back after closing the Sign Request.
* When sending funds XUMM now omits incoming transactions with Destination Tags below 10000, resulting in improved Destination Tag requirement detection when users send to a (your) wallet.
* **Automatic token (TrustLine) dust removal for small balances.** Small token (TrustLine) balances (< 0.0001) now allow pressing the Remove TrustLine button, in which case the remaining balance will be sent back to the issuer & a subsequent transaction to close the TrustLine will be opened.
* **Changed**: the “Exchange” (token) page no longer refers to XRP Toolkit as there are more tools allowing more advanced DEX trading now. XRP Toolkit can still be used, just like other DEX interfaces.

#### Fixed

* The All button, to use all funds when using the Exchange button for a token (TrustLine) now correctly handles amounts with many decimals.
* If one was going through a longer list of Sign Requests, one could open a recently (\~10 seconds) resolved Sign Request again. XUMM now always checks if the Sign Request is still valid before signing & submitting a transaction.
* On Android, the native Android ‘hardware’ (OS) back button would trigger the Close/Decline panel for Sign Requests after resolving the Sign Request (harmless but confusing).
* Added some missing translation labels, e.g. the Explain balance link on the Home screen.
* Minor user interface fixes, e.g. height calculation when re ordering accounts (Settings - Accounts), replaced the ugly “NFT” icon.
* Fixed a bug causing the home screen not to reflect the correct tokens & balance after switching network (Settings - Advanced - Node).

#### For Developers

* xApps attached to transactions (through a specially crafted memo) now show the xApp open button for outgoing transactions as well.
* xApp page has been added to the XUMM Developer Console, featuring basic stats & Device UUID whitelisting for OTT re fetching (during development / testing).
* Added client side XUMM SDK / XUMM API calling for xApp/OTT flows using JWT auth. Go backendless if you like ;)
