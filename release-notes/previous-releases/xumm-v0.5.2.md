# Xumm v0.5.2

* _**The XUMM 0.5.2 update will be available in the Apple App Store & Google Play Store around October 2nd, 2020.**_\*

This (minor) update will contains some improvements and addresses some minor bugs.

Depending on the settings on your phone, you’ll either have to visit the App Store/Play Store and tap the update button, or XUMM will auto-update.

**The next release we will add in-app automatic update checks, so you’ll receive a message in the XUMM app when an update is available 🎉**

**Improved**

* Read Only accounts don’t show the (confusing) “Request” button anymore at the home screen
* Added “keyboard incognito mode” for Android
* If the ‘Account’ field is specified in a Sign Request, that account is now preselected if present as Read/Write account
* Allow importing mnemonics from a QR code
* Add “exchange all funds” button in the “Other assets” (IOU) exchange screen

**Changed**

* Exchange accounts can not be imported as Read Only account anymore. Added a check for destination tag requirements when importing Read Only accounts, and don’t allow users to import a Read Only account with mandatory (or likely) destination tag requirement, to prevent confusion.
* iOS FaceID / Fingerprint reader now falls back to OS passphrase/PIN on “Enter Password”
* Improved QR destination address recognition
* Updated push notification handling, and when an payload is already open (on screen) after scanning a QR, a notification for the same payload will be hidden
* Changed “passphrase” to “password” for XUMM account encryption/decryption (to prevent confusion with mnemonics)

**Fixed**

* Sign Requests (by URL) are now picked up from the clipboard when opening the app from background (minimized) state as well
* When you have an offer on the Decentralized Exchange, when a part of your offer is consumed, XUMM now shows only the affected amounts for the partial fill (instead of the entire consuming offer)
* On rare occasions the wrong currency exchange (IOU) amount was displayed in the transaction history (right amount was exchanged)
* Lots of decimal places are now truncated in the Exchange (IOU) screen
* Fixed app crash on scanning a Coinbase destination QR code
* Fixed Android app crash on empty asset list

**Notes**

* Link to the issue tracker for this release:[https://github.com/XRPL-Labs/XUMM-Issue-Tracker/projects/4#column-9337118](https://github.com/XRPL-Labs/XUMM-Issue-Tracker/projects/4#column-9337118)
* Official XRPL Labs / XUMM communication channels:[https://support.xumm.app/en/articles/4299954-official-xumm-communication-channels](https://support.xumm.app/en/articles/4299954-official-xumm-communication-channels)
* New (simple) XRPL Labs website:[https://xrpl-labs.com](https://xrpl-labs.com)
