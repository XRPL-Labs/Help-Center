---
cover: ../../.gitbook/assets/fireworks-gd7b280d6a_1280.jpg
coverY: 0
---

# Xumm v2.4

**Welcome in Xumm 2.4.0. This version ships exciting features and improvements!**

Some of these include: path finding payments, viewing a list of owned NFTs, and seeing the account reserve on the home screen. There are also bug fixes and visual improvements to make Xumm look better & easier to use.

One of the major updates is that Xumm now allows developers to send sign requests, allowing for pathfinding payments. Pathfinding sign requests allow you to select any liquid asset to pay, while the beneficiary receives the currency and amount they asked for.

Xumm now also features a new native NFT implementation (XLS20), allowing you to view a list of your owned NFTs on the home screen (tap Tokens / NFTs on the home screen to switch between Tokens & NFTs.

Xumm has made changes to its reserve and fiat feature on the home screen to make it less confusing. You can now see the reserved amount of XRP and your XRP balance separately, and tap the XRP balance to toggle between showing the amount of XRP or the fiat equivalent.

Some extra checks and warnings are implemented, like a warning when they you are about to sign a Buy offer for an NFT that can be burned. The transaction Fraud Alert message has been changed to make it clearer that the sender has been reported for suspicious behavior.

When signing a non-XRP token transaction, the app now checks if your Trust Line has been frozen by the issuer and will prompt you to contact the issuer if necessary.

You can now see which third party apps you have interacted with. You can revoke sign reqyest push permissions in the Settings menu. Third-party apps will NEVER have access to your keys.

Smaller new features include Xumm now also supporting manually-entered/pasted hexadecimal memos (for cross chain features) in the manual payment send flow and an immediate warning if an imported account has been configured on another Xumm device.

When opening Xumm from the background, the Event List wil now automatically refresh, showing new sign requests straight away. This update also suppresses a warning about Xumm not endorsing a TrustLine (token issuer) when signing a TrustSet for an issuer & asset listed in the token shortlist.

**Overall, these updates make Xumm more user-friendly and secure.**

***

**For Developers**

* You can now add the Pathfinding option to Sign Request Payment payloads to allow users to pay with other assets. Please make sure you use the DeliverMin payment property correctly so you will get paid at least the expected amount. Please do not rely on the Amount field when checking the transaction results (actual paid amount): look at the delivered\_amount in the transaction meta, as reported by XRPL nodes.
* xApps now feature the share() method with (and/or) a title, text and url property, triggering the native OS (Android / iOS) share dialog.
* You will now obtain a user\_token to deliver Sign Requests in your JWT / OTT when users interact with your xApp / Web3 (OAuth2) sign in. Users can revoke this user\_token at their convenience.
