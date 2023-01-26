# Xumm v2.2.3 / v2.2.4

#### Depending on your OS settings, your device may or may not auto-update. Check your App / Play store for the latest version (2.2.0).

#### XUMM 2.2.3 / 2.2.4 is containing **small improvements** & **important fixes**.

#### Improved

* **iOS** **Android** Warning displayed when buying (DEX) a non-vetted token
* **iOS** **Android** All Trust Lines (more than 200) will now be displayed
* **iOS** **Android** The Event List will now auto-update (live) after receiving on ledger transactions
* **iOS** **Android** When a transaction fails (e.g. due to insufficient reserve) a description will now explain what happened, and why.
* **iOS** **Android** Add descriptions in transaction details screen for setRegularKey transactions
* **iOS** **Android** Warn users when setting a weak passcode
* **iOS** **Android** Required passcode authentication for removing or downgrading account security

#### Fixed

* **iOS** **Android** Fixed a bug causing XUMM to occasionally (incorrectly) display a Balance insufficient warning (e.g. when using Pathfinding)
* **iOS** **Android** The KYC Flag (blue checkmark) wasn’t being displayed in the Event list if the account didn’t have a name associated with it
* **iOS** Fix bug that caused XUMM to crash on startup on iPod Touch devices
* **iOS** Screen blurring (security, privacy) now also happens on overlay dialogs (like the account switcher)
* **Android** The Exchange panel (DEX swap for tokens, Trust Lines) had a text input position/alignment bug causing entered amounts to be partially visible
* **Android** Disable Android Hardware Back button in xApps to prevent accidental xApp closes
* **Android** Disable auto suggestion on plain text view password fields like the Family Seed import field (eye icon, when password / family seed is visible)
* **Android** Fixed the keyboard staying visible on Android after pasting an amount in the Send flow (amount input)
* **Android** Fixed rare, random app startup crash on Android
* **Android** Fixed minor UI (alignment, positioning) bugs
