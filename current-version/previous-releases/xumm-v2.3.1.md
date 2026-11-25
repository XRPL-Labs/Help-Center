# Xumm v2.3.1

## Xumm v2.3.1 - Release notes

This update corrects some of the minor issues reported by customers in Xumm v2.3.0.

#### **Improved and Fixed in v2.3.1**

* Sign requests of the type Sign In now explicitly show **Sign In**.
* **Cross currency / Partial payments** can now also be delivered to a destination account that doesn’t have the Trust Line for the originating currency.
* **Reordering tokens** (home screen) on Android was not possible on some slower devices: the sort state would auto-revert
* **Improved TrustSet** transactions where the limit at 0 (zero) but flags set showing up as “Remove token”. We now check for Trust Line default state.
* Some Buttons were not completely visible in the Royal theme
* Sign In requests no longer turn into Events if minimized: they are either signed or get automatically rejected
* Fixed a rare crash on iOS upon enabling Biometric authentication
* The NFTokenAcceptOffer transaction now looks up the offer referenced, and **shows details of the NFT offer** while accepting the offer in the Sign Request review screen. (XLS-20)
* Updated the message in the Biometrics settings if the biometric capabilities of your device do not satisfy Xumm’s security requirements.
* Adding support for ExpandedSignerList amendment.
* Improved icon alignment for xApps with different amount of app title lines.

#### **For Developers**

* With the Developer Mode enabled, the Developer Mode header covered the Account Switch button on the home screen. This has been fixed.
* Payloads now return the network the user was connected to at the time of signing for non-submitted payloads (like SignIn requests) as well.
