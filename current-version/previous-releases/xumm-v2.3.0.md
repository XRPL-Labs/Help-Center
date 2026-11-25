# Xumm v2.3.0

This version contains the long-awaited brand new **token list**, featuring **ordering/sorting, filtering and more**!

We also made other functional changes to the Xumm app including several **improvements** and **important fixes and changes our logo design**.

#### **Highlights in v2.3.0**

* The long-awaited new Xumm app home screen offers asset (token) **filtering**, **ordering/sorting**, marking assets as **favorite** & hiding assets without a positive balance.
* Updates to the **Xumm icon, app start splash screen and primary blue color**
* **A warning will is displayed if an offer has the potential to consume the entire balance of the selling asset** when signing an ‘OfferCreate’ transaction to make a trade on the Decentralized Exchange,
* Updates to **support the renamed XLS-20 NFT transaction types** & **field names** that restores full XLS-20 ‘DevNet’ network functionality.
* **Four more xApps are now displayed** in the ‘Xumm xApp Dock’ (the menu that opens after selecting the ‘x’ button in the centre of the bottom navigation bar
  * the first four xApps are highlighted / recently used Xumm xApps
  * the second row of four xApps contain the most recently opened xApps provided as add-on, or by ecosystem developers
  * The Xumm Dock now also contains placeholders displayed while loading the relevant & recent xApps.
* **The biometric authentication implementation has been upgraded**: if you open Xumm and/or sign transactions with your face / fingerprint, Xumm will now check if the authorized fingerprint(s) / face(s) have been updated (the iOS/Android security settings). If updated, Xumm will disable biometric authentication and fall back to the six digit PIN configured during initial Xumm setup, after which biometric authentication can be re-enabled in the Xumm security settings.
* **With Xumm Pro almost ready to go into public Beta**, the Profile button (bottom navigation bar) has been replaced with a Pro button, allowing access to the public Xumm Pro beta.

#### **New in v2.3.0**

* Sign Requests now check for the Disallow XRP flag and Black-Holed status of the destination account and, if found, a warning is displayed before the transaction can be signed.
* When signing an empty ‘AccountSet’ transaction, Xumm now indicates that it’s an empty AccountSet transaction. If used to remove a Ticket, Xumm will now indicate this as well.
* Improved Ticket information availability: the amount of Tickets matching the claimed reserve has been added to the Explain balance panel, TicketCreate transactions show the created Ticket numbers on the Event detail page and the Planned event tab now shows open Tickets as well. Finally, the Ticket details page features a Cancel ticket button.
* Tapping a Contact address (from the Manage Contact panel) now allows for easier copying of the contact’s address to the clipboard.
* (_Developers_) xApp OTT data now includes the `wss://` WebSocket node endpoint to connect to the network the Xumm is connected to.
* (_Developers_) Sign Requests can now include a Forced Signer, resulting in Xumm enforcing that the payload (Sign Request) can only be signed explicitly by the account provided as forced signer in the Sign Request. This way developers / platforms / apps can compose Sign Requests that can only be signed by users having access to the specific account in Full Access mode. (Useful for e.g. multi sign transaction flows)

#### **Improved & fixed in v2.3.0**

* The Return Payment button is no longer available for incoming Payment transactions. Returning an incoming payment ‘as is’ is hardly ever being used, while it adds the risk of users sending back to custodians (e.g. exchanges) without supplying the proper Destination Tag (as the tag can’t be resolved from the incoming transaction)
* Transaction flags are now also displayed on the Event details page. They already were in the Sign Request flow.
* For a small number of transactions (based on the transaction output), an incorrect interpretation of values for certain types of trades on the Decentralized Exchange resulted in the wrong amounts being displayed on the event details page. (Special thanks to _Richard Slater_ 😘 for reporting this!)
* For accounts being the issuer of a token, removed Trust Lines (by a third party) for the issued assets would show up in the Event List as Incoming instead of Removed.
* If system locale decimal separator is Unicode or anything other than a comma or dot, typing the decimal separator would be replaced with an empty string when entering amounts.
* The Event list Planned tab did not always show all open offers.
* The Remove button for a specific asset would stay in spinner mode when the Remove was cancelled.
* Added a couple of initially undocumented but relevant NFT (XLS-20) related fields/flags.
* Resizing an Android app in Android Desktop Mode allowed bypassing the app Login Passcode.
* In the Send flow, in the Token dialog, when typing the `[` character, the app would crash.
* Fixed the NFT `NFTokenMint` factor 10 TransferFee offset.
