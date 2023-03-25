---
description: Overview and use cases
cover: ../.gitbook/assets/monolith in stream.jpg
coverY: 251
---

# All about Xumm (Tangem) cards

At XRPL Labs, we are constantly working on improving the XRP Ledger user experience for consumers and for businesses.

Xumm is a self-custodial XRP Ledger wallet. This means that you, and only you, have access to your funds because your funds are in your own account, to which you own the keys. Your keys are encrypted securely on your iOS/Android device.

### **Keeping your keys safe**

While keeping your keys encrypted on your device makes a lot of sense for your daily spending (lower-value accounts, to be accessed on the fly), your keys to your XRPL savings are best kept offline, away from your iOS/Android device (or any device you carry around, for that matter). Existing methods to keep your private keys to your higher value accounts safe all have disadvantages, if you want to be able to potentially/periodically move funds from your savings to your spending account. A paper wallet (your secret offline, written down) is not user friendly. It's hard to use, because it will have to be imported to eg. Xumm when you want to access your funds. Hardware wallets have to be charged, are slightly harder (or even scary) to use. Air gapped clients require manual data entry when signing.

### **Enter Xumm (Tangem) Cards**

Just like XRPL Labs, [Tangem](https://shop.tangem.com/pages/start) is making the cryptocurrency space a safer, more user-friendly place. Their take on keeping keys for XRPL accounts safe is one we at XRPL Labs appreciate a lot. To the point where we feel confident using their cards ourselves to keep our savings safe. Instead of using a hardware wallet, or a static, written down secret (that can't be used easily), their cards contain a chip and use NFC ([near field communication](https://nl.wikipedia.org/wiki/Near-field\_communication)). The first time you use the card, the chip generates a private key, while being powered using NFC (by your iOS/Android device). This means the cards are shipped without a private key on them, so there is no chance of it being compromised between you and the factory. The chip used in Xumm (Tangem) cards offers bank grade security and have been fully audited.

### **Security + usability**

Because the key stays **in** the (chip in the) card, signing happens **in** the (chip in the) card. This means your secret will **never** leave the card. You hold your card against your NFC enabled iOS/Android device to sign a transaction. Xumm will then send transaction details to the card, the card will sign and return the signature (for the signed transaction) to Xumm so Xumm can submit it to the XRP Ledger. This offers the best combination of user experience and security. Using your smartphone with decent screen size, and the Xumm + XRPL ecosystem to compose and review transactions, while using a separate (dedicated, low level, offline) piece of hardware (the Xumm (Tangem) card) to sign transactions. While Tangem already offered XRP cards, one could only use them for regular XRP payments. The XRPL has much more to offer than simple XRP payments: Issued tokens / IOU's (decentralized exchange), account settings, multi signing, escrow, etc. All fully supported by Xumm.

> ![](https://coil.com/static/media/quote.7f7bd428.svg)We are very excited and proud to share that, by supporting Tangem cards in Xumm, all XRP Ledger features and all transaction types will be available for all existing Tangem card owners.

### **Recovery**

Because the chip inside a Xumm (Tangem) card generates and holds the (non-extractable) private key to access your funds, a lost card means you won't be able to access your funds anymore. Fortunately, we've got your covered. Xumm includes an xApp called "Tangem Backup" which allows you to **configure a second card as a backup**. By doing this, you don't have to worry about a lost, stolen or damaged card... you will have a backup card to protect your assets.&#x20;

* ****[**How to use the Tangem Backup xApp**](how-to-configure-a-backup-signing-account.md)****

### &#x20;Frequently asked Questions

* **What's the typical use case for a Xumm (Tangem) card?**\
  Your Xumm Tangem card has its own r-address. It's a separate XRP Ledger account. Xumm, in combination with your Xumm Tangem card, enables all XRPL features. The most common use case would be to use two XRP Ledger accounts: one for receiving funds & daily spending and one for your savings. Your daily spending account in Xumm (as read/write account), and your savings account using a Xumm (Tangem card). When you want to top up your spending account, you use your Xumm Tangem card to sign a transaction from your savings account to your spending account. When your spending account has a higher balance than you're comfortable with, you simply use Xumm to send some of your funds to your Xumm (Tangem) card account.\
  &#x20;
* **Can I use a Xumm Tangem card in an ATM / payment terminals?**\
  No, you cannot. While all Tangem cards feature a bank grade secure chip, the chip is programmed to work only for crypto-currencies with Apps supporting the cards. ATM's and retail payment terminals **will not recognize** a Xumm (Tangem) card.\
  &#x20;
* **Can I use an existing XRP Tangem cards with Xumm?**\
  Yes, definitely! All existing & future Tangem XRP cards will work with Xumm. All XRPL features will be available to all Tangem card owners using Xumm.\
  &#x20;
* **Xumm Pro (Beta) is a paid subscription, do I need Pro to use Xumm (Tangem) cards?**\
  When you subscribe to Xumm Pro (Beta), you will receive two free Xumm (Tangem) cards with your order.(Note: Not all countries are eligible to receive the cards due to customs restrictions.) [**How to subscribe to Xumm Pro Beta 🎉**](../xumm-pro-beta/how-to-subscribe-to-pro.md)\
  &#x20;
* **Can I extract or backup the secret / private key from my Xumm (Tangem) card?**\
  No, you cannot. The secret / private key of a Xumm (Tangem) card is stored safely inside the chip in the card. The card can only sign for you, it will **never expose the secret / private key**. While you cannot extract & backup the secret / private key of the card, **Xumm can setup a recovery account, and attach the recovery account to your Xumm (Tangem) card account.** Using this recovery account, you will be able to regain access to your funds in case of a lost, stolen or damaged card.\
  \
  See: [**How to use the Tangem Backup xApp**](how-to-configure-a-backup-signing-account.md)\
  &#x20;
* **How is the Xumm (Tangem) card protected? Can someone else use my card if they have physical access?**\
  Xumm will allow you to setup a PIN / Password **on** your card. If you do so, signing transactions with your card also requires that you to enter the PIN / Password. This will protect you against physical access attacks, as one not only needs your card, but your PIN / Password as well.\
  If you did not configure a PIN / Password on your card, anyone with physical access to the card can move all your funds.\
  &#x20;\
  See: [**Creating a pin on your card**](creating-a-pin-on-your-xumm-tangem-card.md)\
  &#x20; &#x20;

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the <mark style="color:blue;">**Xumm Support xApp**</mark> in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
