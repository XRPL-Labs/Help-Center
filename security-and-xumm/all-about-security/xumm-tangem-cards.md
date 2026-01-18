---
description: 'Safer savings: Introducing the Xaman Tangem Card!'
coverY: 0
---

# Xaman (Tangem) Cards



At XRPL Labs, we are constantly working on improving the XRP Ledger user experience for consumers and for businesses.

Xaman (formerly Xumm) is a self-custodial (un-hosted) XRP Ledger client (wallet). This means that you, and only you, have access to your funds because your funds are in your own account, to which you own the keys. Your keys are encrypted securely on your iOS/Android device.

**Keeping your keys safe**

While keeping your keys encrypted on your device makes a lot of sense for your daily spending (lower-value accounts, to be accessed on the fly), your keys to your XRPL savings are best kept offline, away from your iOS/Android device (or any device you carry around, for that matter).

Existing methods to keep your private keys to your higher value accounts safe all have disadvantages, if you want to be able to potentially/periodically move funds from your savings to your spending account.

A paper wallet (your secret offline, written down) is not user friendly. It’s hard to use, because it will have to be imported to eg. Xaman when you want to access your funds. Many hardware wallets have to be charged, are slightly harder (or even scary) to use. Air gapped clients require manual data entry when signing.

**Enter Xaman (Tangem) Cards**

Just like XRPL Labs, [Tangem](https://shop.tangem.com/pages/start) is making the cryptocurrency space a safer, more user-friendly place. Their take on keeping keys for XRPL accounts safe is one we at XRPL Labs appreciate a lot. To the point where we feel confident using their cards ourselves to keep our savings safe.

Instead of using a hardware wallet, or a static, written down secret (that can’t be used easily), their cards contain a chip and use NFC ([near field communication](https://nl.wikipedia.org/wiki/Near-field_communication)). The first time you use the card, the chip generates a private key, while being powered using NFC (by your iOS/Android device). This means the cards are shipped without a private key on them, so there is no chance of it being compromised between you and the factory. The chip used in Xaman cards offers bank grade security and have been fully audited.

**Security + usability**

Because the key stays **in** the (chip in the) card, signing happens **in** the (chip in the) card. This means your secret will **never** leave the card.

You hold your card against your NFC enabled iOS/Android device to sign a transaction. Xaman will then send transaction details to the card, the card will sign and return the signature (for the signed transaction) to Xaman so Xaman can submit it to the XRP Ledger.

This offers the best combination of user experience and security. Using your smartphone with decent screen size, and the Xaman + XRPL ecosystem to compose and review transactions, while using a separate (dedicated, low level, offline) piece of hardware (the Xaman card) to sign transactions.

While Tangem already offered XRP cards, one could only use them for regular XRP payments. The XRPL has much more to offer than simple XRP payments: Issued tokens / IOU’s (decentralized exchange), account settings, multi signing, escrows, NFTs, AMM, etc. All fully supported by Xaman.

**Recovery**

Because the chip inside a Xaman card generates and holds the (non-extractable) private key to access your funds, a lost card means you won’t be able to access your funds anymore

Fortunately, we’ve got your covered. Xaman includes an xApp called “Tangem Backup” which allows you to **configure a second card as a backup**. By doing this, you don’t have to worry about a lost, stolen or damaged card… you will have a backup card to protect your assets.

* [How to use the Tangem Backup xApp](https://support.xumm.app/hc/en-us/articles/4417047349394)

### **Further explanation & FAQ’s**



*   **What’s the typical use case for a Xaman card?**

    Your Xaman card has its own r-address. It’s a separate XRP Ledger account. Xaman, in combination with your Xaman card, enables all XRPL features.

    The most common use case would be to use two XRP Ledger accounts: one for receiving funds & daily spending and one for your savings. Your daily spending account in Xaman (as read/write account), and your savings account using a Xaman card.

    When you want to top up your spending account, you use your Xaman card to sign a transaction from your savings account to your spending account.

    When your spending account has a higher balance than you’re comfortable with, you simply use Xaman to send some of your funds to your Xaman card account.<br>
*   **Can I use a Xaman card in** [**ATM’s**](https://twitter.com/WietseWind/status/1329910752325619715) **/** [**Retail**](https://twitter.com/WietseWind/status/1329909916631494665) **payment terminals?**

    No, you cannot. While all Tangem cards feature a bank grade secure chip, the chip is programmed to work only for crypto-currencies with Apps supporting the cards. ATM’s and retail payment terminals **will not recognize** a Xaman card.<br>
*   **Can I use an existing XRP Tangem cards with Xaman?**

    Yes and no. The most current Tangem cards are V2 multi-cards. These cards are **not** compatible with Xaman. Some of the older Tangem cards will work with Xaman but your plan is to participate and interact with the XRP Ledger and Xahau communities, Xaman cards are the way to go. <br>
*   **How can I purchase Xaman cards?**

    They are available via our [**Get cards xApp**](https://xumm.app/detect/xapp:xumm.tangem-order):\
    \
    [https://xumm.app/detect/xapp:xumm.tangem-order](https://xumm.app/detect/xapp:xumm.tangem-order)\
    \
    or via our website:\
    \
    [https://xrpl-labs.com/tangem/product](https://xrpl-labs.com/tangem/product)<br>
*   **Can I extract or backup the secret / private key from my Xaman card?**

    No, you cannot. The secret / private key of a Xaman card is stored safely inside the chip in the card. The card can only sign for you, it will **never expose the secret / private key**.

    While you cannot extract & backup the secret / private key of the card, **Xaman can setup a recovery account, and attach the recovery account to your Xaman card account.** Using this recovery account, you will be able to regain access to your funds in case of a lost, stolen or damaged card.<br>

    See: [How to use the Tangem Backup xApp](https://support.xumm.app/hc/en-us/articles/4417047349394)<br>
* **Does a Xaman card require another 1 XRP reserve?**

That depends on how you configure the cards. While primary cards require that they be activated,               backup cards do not require activation.

See: [Tangem cards - Back Up & Best Practices](https://support.xumm.app/hc/en-us/articles/4416929335186)

**Additional reading**

* [Where are your funds stored? (Explainer video 2/5)](https://support.xumm.app/hc/en-us/articles/4408081411474)
* [How secure is Xaman?](https://support.xumm.app/hc/en-us/articles/4427109779986)

