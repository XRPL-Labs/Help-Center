# Xumm v1.0.0

### **XUMM V1 will be available in the Apple App Store and Google Play Store around new year (2020-2021).**

**🎉  This is the first major XUMM release. The updates in this release contain significant improvements and new features 😎**

### Added

* All XUMM and XRPL features are now fully tested. There is always room for improvements, but after two years of development, this is version 1.0.0 🚀
* The XUMM app is now available in **46 languages**, thanks to community translators 😘
* [**Added support for (all, even non-XRP) Tangem cards**](https://coil.com/p/XUMM/Safer-savings-XUMM-Tangem/mkzI5zZX2) **😎** Keep your accounts safe & sign with a plastic card instead of a secret key
* Respect the “Disallow Incoming XRP” flag when sending XRP to an account. Some IOU (token) issuers enabled this.
* Added a quick Copy (r-address to clipboard) button next to the Share button in the “Receive” / “Request” panel
* New Destination Tag confirmation screen when sending to an account with a Destination Tag. A big font and digit spacing will make it easier to check the entered Destination Tag, to prevent deposit mistakes
* Added explanations & disclaimers during the app onboarding (first start)
* When scanning a Sign Request from a QR code, when the Sign Request is Closed (instead of Rejected) it now shows up in your Event - Requests list

### Improved / Changed

* Better account switching (panel), now showing the r-address per account as well
* When entering the wrong password for an account (to sign), a dialog with explanation is now displayed (instead of an “Invalid authentication” message)
* When XUMM is started for the first time after changing phones and restoring from a backup (eg. iCloud) without the keychain, XUMM now warns you at first start that for security reasons, you’ll have to import your secret keys again on your new phone.
* Minor user interface & usability improvements all over the place
* Updated “Passphrase” to “Password” text (English) when referring to the password used for account encryption
* Improved pasting (from clipboard) / scanning (QR-Code) Destination Tags: stricter checks for valid Destination Tag formatting
* Better HEX private key import validation
* Updated (new) extended Terms of Service
* Improved warnings / education when importing Read Only accounts (please don’t import Exchange hot wallets / deposit accounts)
* Addded warnings / explanation when signing an AccountDelete Sign Request

### Fixed

* Fixed a bug that would crash XUMM when running with the “System currency formatting” disabled, when typing an amount (eg. Send transaction flow)
* When sharing an account address on larger iOS phones, the share dialog would close immediately after opening
* Fixed a bug that caused XUMM to crash when XUMM was opened while not in airplaine mode, but without a working internet connection
* On Android, when navigating back (eg. when sending funds) while the keyboard was visible, the keyboard wouldn’t close.
* After adding a contact, all existing views are updated to reflect the contact name (instead of after a new start of the XUMM app)
* When you issued an IOU and someone else removed a Trust Line to your account, it now shows up as Removed instead of Added in the Events list
* Fixed scrolling issues for Sign Requests: at times the account selection / Sign button wasn’t reachable
* Fixed an issue where return payments would sometimes excludes prefilling the Destination Tag
* When sending to accounts where no destination tag was required, a 0 (zero) Destination Tag is no longer used
* Fixed a discrepancy between the displayed spendable balance on the home screen and on the Send-screens (reserves weren’t subtracted)

### For Developers

* The XUMM SDK / API now returns the signing security level & request origin flow for Sign Requests:
  * `payload.origintype`
    * QR
    * DEEP\_LINK
    * EVENT\_LIST
    * PUSH\_NOTIFICATION
  * `payload.signmethod`
    * TANGEM
    * PASSPHRASE
    * BIOMETRIC
