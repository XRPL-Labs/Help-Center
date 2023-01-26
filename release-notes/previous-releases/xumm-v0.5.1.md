# Xumm v0.5.1

We’re happy to announce the release of the next version of XUMM, v0.5.1, containing well over 50 improvements and fixes. Although the version number indicates this is to be a minor release, the effort and changes are more like a major release.

There are some important changes and fixes added to this release after we already communicated the version number. We have listened to your feedback and we will continue to do so. We appreciate your effort for making XUMM a better app everyday!

Special thanks go out to [@nixerFFM](https://twitter.com/nixerFFM) and [@saschofield52](https://twitter.com/saschofield52)

**Bookmarks for suggestions, support & development progress:**

* Support (FAQ’s & 1:1 private support):[https://support.xumm.app](https://support.xumm.app)
* Feature requests / suggestions & vote at existing community provided requests & suggestions:[https://feedback.xumm.dev](https://feedback.xumm.dev)
* Public issue tracker & progress:[https://github.com/XRPL-Labs/XUMM-Issue-Tracker/projects/4](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/projects/4)

**Improvements**

* **Transaction detail page** [**redesign**](https://user-images.githubusercontent.com/4756161/82672211-5a986c00-9c40-11ea-9149-c1fa0e124ee0.png)
* Added Support for [checks](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/issues/203)
* Memo icon in events page if a transaction contains a memo
* Show local date & time (timezone) for transaction details page and show account info like [this](https://user-images.githubusercontent.com/4756161/83822570-b5ff3b00-a6d1-11ea-9cee-8fb295555369.png)
* “Discreet mode”: hide account address and balances on app start (remembers last state & setting to start hidden by default)
* **Improved liquidity check for IOU asset, added liquidity check before** [**buying**](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/issues/141) **& price quote based on requested amount to exchange**
* Improved exchange rate accuracy for exchanging IOU [assets](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/issues/98)
* Added support for branding (logo, name) for non-shortlisted IOU’s (tokens)
* **TrustLines with negative balances (self issued IOU’s) now show in the XUMM home screen (obligation) and are available for sending (self issued tokens 🎉) - eg. using** [**https://xrpl.services**](https://xrpl.services)
* Added support for DepositPreauth
* Show year in events page if it is not the current year
* Added labels to XRP accounts in settings page
* Show received [value](https://user-images.githubusercontent.com/4756161/83573622-22403a00-a52c-11ea-95b4-8cb7160e4293.png) for currency exchanges & the currency code in events page
* Show received XRP with an Account Delete transaction
* Improved secret numbers validation on generating new XRP account
* Allow signing with all accounts for “sign in requests” (eg. unactivated accounts, like “regular keys”)
* Change [labels](https://user-images.githubusercontent.com/4756161/83822226-b945f700-a6d0-11ea-8c60-4128f5372710.png) for OfferCreate transaction
* Show destination for AccountDelete event
* Tapping the XUMM app version (Settings, Advanced) will popup the release notes
* Improved “maximum amount reached”-message for sending IOU currencies, updating the value to the max. spendable amount
* Hide balance section on Account home screen if the account is not activated
* Explanation for un-activated accounts regarding the 10 XRP reserve (when importing/adding an account)
* Improved user flow (and on screen information) when importing rekeyed accounts like Toast vanity addresses (using “Regular keys”)

**Bug fixes**

* **Improved XRP Ledger (node) connectivity**
* Copy an address with privacy mode copies only dots
* When scrolling down in the Event list (transactions), when opening a transaction and navigating back to the list, the list offset changed.
* Sign button on request not reachable on iOS
* Numpad fix for [iOS](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/issues/226)
* Submitting signed transaction by QR code resulted in a blank page
* Scrolling stopped within switching an account after certain number
* Support for 21:9 aspect ratio phones regarding UI behavior
* Regular key account showed as an read only account, changed to Read/Write
* Fixed iOS 10 error when scrolling within changelog
* Backspace first PIN digit didn’t work on all devices
* Account reserve list & balance calculation inaccuracy solved
* On Android when clicking multiple times on share link the app will no longer open multiple share dialogs
