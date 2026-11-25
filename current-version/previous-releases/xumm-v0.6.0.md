# Xumm v0.6.0

The XUMM 0.6.0 update will be available in the Apple App Store & Google Play Store around November 16th, 2020 - while already published, it may take a couple of hours before the 0.6.0 update will be visible in the iOS App Store and Google Play store.

This major update contains significant improvements 😎 changes a few things and fixes some bugs 🎉

This release contains in-app automatic update checks, so you’ll receive a message in the XUMM app when an update is available 🎉 Meaning **this is the last version** you’ll have to get from the App/Play Store update page without notice.

Especially for this version we relied on a lot of help, input and debugging by XUMM users & community members. Thank you **so so so** much for helping us out, [reporting issues](https://support.xumm.app/en/), sending [feedback](https://twitter.com/XummWallet) & [posting suggestions](https://feedback.xumm.dev/)!

This version contains these suggestions form the XUMM [Suggestion Board](https://feedback.xumm.dev/xumm):

* XRPL Check functions on mobile by “Pay The Piper”
* In App update check by “Brad Marsh”
* [WooCommerce Plugin for payments](https://nl.wordpress.org/plugins/xumm-payments-for-woocommerce/) by “Salvo Leone”

This is most likely the last XUMM Beta release, the next release will most likely be version 1.0, where the Beta label will be removed. But we already removed the balance warning last version, as XUMM security, sending & receiving has been thoroughly tested.

>

**Added & improved**

* Major makeover of the Event list, now [showing account icons](https://gsa4buc.dlvr.cloud/IMG\_7374.PNG) and [active Ledger Objects (like Escrows and Checks) on dedicated tabs](https://gsa4buc.dlvr.cloud/IMG\_7381.PNG), with appropriate actions in the transaction detail screen.
* Unactivated accounts will now show a button at the home screen to show the QR code for sending initial funding.Added support for alternate derivation paths when importing Mnemonic based accounts.
* QR Scanner can now be used to [scan just the Destination Tag](https://gsa4buc.dlvr.cloud/IMG\_7378.PNG) (when sending) as well.
* When cancelling a Check, the Check destination account will now be displayed in the Sign Request screen.
* Added support for opening Explorer links with alternative browsers on iOS.
* XUMM shows In-App update warnings from now on, when there’s a new version available in the App/Play store.
* Improved transaction search in the event list.
* New “Transaction sent” (in case of successfully signed a request) confirmation screen.
* XRP balance (home screen) [now displays thousand separators, support for EU and US notation](https://gsa4buc.dlvr.cloud/IMG\_7376.PNG).

**Changed**

* Android: the Settings panel now allows you to temporary enable taking screenshots and screencasts.
* The device Clipboard will no longer be read from the home screen, instead the clipboard can be [read opt-in from the Scan (Camera) dialog](https://gsa4buc.dlvr.cloud/IMG\_7375.PNG).
* Improved some internals resulting in a much faster cold app start on Android and iOS.
* Incoming Trust Lines (for issuers) in the Event list [now explicitly show the Trust Line is incoming](https://gsa4buc.dlvr.cloud/IMG\_7380.PNG).
* Account selection dropdown (Sign requests) is no longer a dropdown if there’s only one account (read/write) to select.
* Payments by 3rd parties partially consuming your DEX offer are now listed in the list as [“Exchanged assets” instead of Payments](https://gsa4buc.dlvr.cloud/IMG\_7379.PNG) (which was confusing, as the payment is from and to 3rd parties, but consuming your DEX offer).

**Fixed**

* Fixed a bug that may cause XUMM to display an error message at startup after migrating a backup (eg. new/replaced phone).
* Fixed a bug where the Event list would stay white for Regular Key accounts after signing for another acount.
* iOS: When long-tapping to paste in the Destination Tag field (when sending funds) the input would hide below the keyboard.
* A bug preventing cancelling Check transactions to be signed is now fixed. You can now cancel Checks.
* Fixed a bug that would calculate 5 XRP reserve for unused (limit: 0) Trust Lines.
* Fixed a bug causing some Android devices not to show the account r-addres on the home screen.
* Fixed a bug on causing some users being unable to store a Pin code during the onboarding, on some Android 7 / Android 7.1 devices.
* Fixed a bug that (in rare occasions) could crash the app on Android.
* Fixed a bug that would crash the app when scanning a PayID when adding a contact to the address book.
