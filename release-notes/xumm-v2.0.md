# Xumm v2.0

<figure><img src="../.gitbook/assets/Xumm 20.png" alt=""><figcaption></figcaption></figure>

This version (XUMM 2.0) is the second major XUMM update adding xApps, dark mode and much more.

* For the XUMM roadmap / version number explanation, see: [XUMM 1.1 » 2.0 » 3.0 - Update 🎉](https://support.xumm.app/hc/en-us/articles/360020965240)
* This release enables the CasinoCoin token swap. For more info, check the content by the CasinoCoin team: [casinocoin.im/swap](https://casinocoin.im/swap)

#### **Known bugs**

**The XUMM 2.0.0 release contains two known (minor) bugs.** **XUMM 2.0.1 has been released and fixes these bugs. Please update.**

1. When opening the details panel for a token (aka “IOU”, previously: “Asset”, on the XUMM home y screen) the “Exchange” button is unavailable if you don’t have an existing token balance. This effectively means you can’t obtain a token on the DEX after adding a Trust Line.
2. When opening the details panel for a token (aka “IOU”, previously: “Asset”, on the XUMM home screen) the “Send” button is disabled for NFT’s. This _does_ work using the “Send” button on the home screen, then to select the NFT (token) from the Token list.

#### **Added**

* The ‘**Scan QR**’ button in the middle of the bottom button bar has been replaced by a ‘**launcher**’ button, where the Scan QR button is located & where xApps are listed:
* Introducing **xApp**s 🚀 xApps are small apps by the XRPL Labs team and curated 3rd parties. xApps are available in XUMM to access specific XRP Ledger features straight from the ‘launcher’ button
* Added **themes** 😎. Besides the existing Light theme, Dark, Moonlight and Royal are now avaialble (Settings - General - Theme)
* Account **reordering**. You can now reorder your accounts (Settings - Accounts). The manual account order will be respected in the Account Switch panel & drop down with your accounts when sending / signing
* Added exchange rate conversion from fiat to XRP and vice versa
* Added entering amount of XRP to send in fiat currency, to be converted to the XRP equivalent
* Add amount to Request button, resulting in a QR code & link to be shared with your account (destination) and prefilled amount of XRP
* Added support for holding, sending & receiving NFT’s based on the XLS-14d Standard Proposal
* Added support for the Tickets amendment (TicketCreate transaction, not available on the XRP Ledger main net yet)
* Add option to **hide accounts** from the account switching panel, e.g. for unused, inactive accounts only used as regular key
* XUMM now forces the default OS keyboard to open, to prevent keyboard entry hijacking with possible malicious 3rd party keyboards

#### **Improved / Changed**

* Allow re-registering push notifcations if once disabled and later enabled (Settings, Advanced, Push notifications)
* XUMM now accepts token amounts > 6 decimal positions, no rounding will be applied
* Timeout when querying backend services / the XRP Ledger (eg. in case of flaky internet connection) now re-enables the tapped button after timing out, so another attempt tapping the button is possible
* Known issuers are now displayed with their brand icon instead of hashicon in the Event list & transaction details / send flow / … screens
* New Trust Lines added from the XUMM asset list (home screen) now set the Tust Line limit to the actual token supply instead of a fixed amount of 1bn
* Improved (alphabetical) address book sorting
* Found a couple of strings fixed in English (couldn’t be translated) & split a couple of translations so their translation can be improved in non English languages
* When starting the app, the Show / Hide balance state doesn’t fall back to the last used setting, but to the default specified at the Settings - Security tab
* Improved requirement checking pre AccountDelete transactions (e.g. no objects like escrows, offers, Trust Lines, etc. are to exist)
* Changed full history node `xrpl.ws` to `xrplcluster.com` for improved full history XRP Ledger node availability
* Improved scroll position when the keyboard opens to enter an amount (e.g. in the Send flow)
* When XUMM is configured to a non-English language, longer words / sentences would push elements (buttons) out of the visible screen, and some button labels would show up misaligned
* Improved transaction sending checks, e.g. if the destination account is blackholed, XUMM will reject sending a transaction to the account to prevent lost funds
* Language selection (Settings) now shows languages in alphabetical order
* Added T9 chars to the XUMM PIN pad

#### **Fixed**

* Slide to Send-button in the last screen of the ‘Send’ flow was really close to the left edge of the screen. When swiping, this could result in swiping back to the home screen instead of sending the transaction
* Improved transaction type displaying in the Events / Transaction Detail screens: e.g. in case of async. partial Decentralized Exchange trades
* Improved transaction amount parsing: e.g. in case of async. partial Decentralized Exchange trades the right from/to amounts are now displayed in the Event list
* Fixed an issue sometimes causing the Tangem read dialog not to show when attempting to sign with a Tangem account (card)
* For more complex (multi path) transactions an exchange of funds would show up as Payment instead of Exchange, and the transaction wouldn’t always show the amounts affecting the own XRP Ledger account
* The Switch button (exchange token) would be hard to tap at times
* The Account Reserve (spendable amount of XRP, Explain balance panel) would sometimes calculate a higher on ledger reserve
* Fixed rare condition where XUMM (on Android) would bypass the PIN screen when starting the app (this didn’t apply to singing transactions)
* Some users couldn’t scroll down in the Release Notes panel

#### **For Developers**

* Added “Developer Mode” (Settings - Advanced) enables showing if you are on livenet or testnet
* Added KYC flow
* Added user KYC status to the XUMM API / SDK
* Added xApps & one time token methods to the XUMM API / SDK
* Added flow to import non-standard alphabet accounts (XRPL forks, eg. CSC)
