---
description: How we recommend using the cards
---

# Best Security Practices Using the Xumm (Tangem) Cards

A Xumm (Tangem) card is basically a self-custodial, NFC hardware wallet. Its main functions are:

* to securely create an account secret for an XRP Ledger account
* store that account secret securely on the card
* sign transactions on the card with the account secret

Tangem is a vendor of NFC cards that creates and configures each Xumm card to our specifications and guarantees that it is not possible to export, import, restore or in some other way gain access to the account secret on each card. This means that the only place your account secret exists is on the card.&#x20;

### **How the card generates the account secret**

Xumm cards use a EAL 6+ certified microchip for secure operations.&#x20;

Upon first use, a private key is generated on the card using its cryptographically secure pseudo random generator that lives inside the chip present in the plastic card.

The public key is then derived from the private key using Elliptic curve point multiplication.

Finally the public key is hashed to produce an XRP address.

The private key is stored on the card securely. It is never revealed and is not accessible by anyone - not even by the Xumm application.

&#x20;

### **How the transactions are signed with the card**

Xumm creates a sign request, then asks the user to sign that request by placing the card over the NFC reader on their mobile device. The sign request is sent to the card where it is signed or rejected **on the card**, then the sign request is returned to Xumm. The account secret never leaves the card.&#x20;

So, while the Xumm app starts the signing operation, the card is exclusively responsible for actual signing a transaction and returning a signed hash back to the Xumm app.

&#x20;

### **Understanding how NFC works**

Each Xumm card has a secure NFC smart-card chip with a Type A contactless interface embedded in it.  In case you're wondering,

_**Near-field communication (NFC)** is a set of communication protocols that enables communication between two electronic devices over a distance of 4 cm or less_

_Source:_ [_Wikipedia_](https://en.wikipedia.org/wiki/Near-field\_communication)

The card uses the NFC smart-card chip to communicate with your phone directly to Xumm.

&#x20;****&#x20;

### **NFC vulnerabilities and possible attack vectors**

The primary attack vectors against a Xumm card fall under the category called "proximity" attacks. Proximity attacks are potential attack vectors for **all** NFC devices, not just Xumm cards.

Proximity attacks are those where a potential attacker needs to be really close to the card in order to be successful. The "attacker” could be a real person with a phone, just a phone laying down on a table, or even small NFC device no larger than Apple AirTag.

Since NFC allows mobile devices to establish radio communication with each other over short distances, there is a possibility, however remote, that an "attacker" might be able to intercept that radio communication.

&#x20;

### **What Xumm is doing to prevent proximity attacks**

We have implemented three main security features to combat proximity attacks.

1. Passcode/Pin\
   Each card has the ability to configure a passcode/pin. By doing this, it greatly increases the security of your funds by forcing you to enter he passcode/pin before a transaction can be signed. We strongly recommend that you create a passcode/pin on all of your Xumm Tangem cards. \
   \
   [How to create a passcode / pin on a XUMM Tangem Card](https://support.xumm.app/hc/en-us/articles/4420121249938)\
   \

2. Security Delay\
   You might have noticed that you are required to hold the card against your phone for 15 seconds before it will sign a transaction. By doing this, a potential attacker would need to be within about 4 cm of your Xumm card for at least 15 seconds in order to send a transaction to it. In theory, you would notice someone standing so close to you for this long. \
   \

3.  Strict security settings\
    Tangem cards offer a large variety of settings that can only be configured at the factory. All Xumm cards leave the factory preconfigured to our specifications.&#x20;

    Among them are:&#x20;

    * NFC communication between the card and Xumm app is encrypted
    * Keys are exchanged using the [ECDH](https://en.wikipedia.org/wiki/Elliptic-curve\_Diffie%E2%80%93Hellman) protocol with the pin mixed in for additional randomness
    * NFC communication sessions are short to minimize chance of NFC proximity attacks
    * All card features that are not specifically used by Xumm are disabled to narrow the attack surface
    * Various security checks are enabled to distinguish valid cards produced by Tangem from potentially malicious cards&#x20;

&#x20;

**Recommended use of Xumm Tangem cards**

1\) Never use your card in an untrusted environment

You should think of your card account as a **savings account**. The card is best used for your higher value accounts or long term savings. For maximum security, you should be using it at home, in a private and trusted environment.  This means that you should not signing transactions in large public areas. (Think grocery stores, malls, crowded streets, etc.)

For daily spending it is recommended to use a regular XRPL account managed by Xumm. Think of this account as your **daily spending account**. It is the account that you would use in a public place, restaurant, shopping mall, etc. It is best used to store **limited funds** that will used on a daily basis. If your balance gets too low you can top it up from your saving account or if it gets too high you can send the excess to your saving account.

&#x20;

2\) Keep your passcode/pin safe&#x20;

Your Xumm Tangem card is basically an advanced version of your master password to access your XRP Ledger account. You probably are very cautious when entering your passcode/pin for your bank card or credit card and you should be just a vigilant when it come to your pin for your Xumm Tangem card.&#x20;

&#x20;

3\) Never use your card on an untrusted device

Make sure your phone is protected. Install the most recent security and OS updates. Don’t root your phone or install jailbreak.

Ensure that your phone has a strong and long device passcode.

Install applications only from AppStore and Google Play. Do not install “cracked” apps from weird sites on the internet.

Review your installed applications from time-to-time and remove those you don’t use.

4\) Never connect to the internet using public WiFi

Public WiFi can be very dangerous. Malware, viruses, worms, "man in the middle" attacks, network snooping, session hi-jacking... the list goes on and on. If you use Xumm or Xumm Tangem cards, we **strongly recommend against** using public WiFi.

&#x20;

**So I should have two accounts, a Tangem card account and a regular XRPL account?**

It is certainly safer to manage your funds using two or more separate accounts. Doing so provides the following benefits:

&#x20;   1\. It limits the potential attack vectors to your Tangem card account

By limiting the location of where you use the card(s), you limit to potential places where someone might be able to intercept your transaction between Xumm and the card via NFC. Your home would theoretically be a more secure location than a shopping mall for example.&#x20;

&#x20;    2\. Having multiple accounts allows you to spread your funds between them

Some people have gone so far as to have multiple Tangem accounts and divide their funds between them. Having your funds spread out in several different accounts, ensures that if someone were to somehow get access to one account, they would not get access to all of your funds. &#x20;

&#x20;    3\. Having a dedicated "spending" account further limits your potential loss in case your account is compromised

A separate spending account that you actively manage helps to keep your "savings account(s)" safe by only exposing it to the world. Your Tangem card(s) remain at home, in a safe environment.&#x20;

&#x20;

**Additional reading**

* [Xumm cards - Back Up & Configuration](https://support.xumm.app/hc/en-us/articles/4416929335186)
* [How to use the Tangem Backup xApp](https://support.xumm.app/hc/en-us/articles/4417047349394)

&#x20;

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the **XUMM Support xApp** in XUMM or you can simply scan this QR code with XUMM and be directed there automatically.

&#x20;

![Support\_banner.png](https://drtc9zr.dlvr.cloud/hc/article\_attachments/4420057706002/Support\_banner.png)

&#x20;

*
* &#x20;
*
* &#x20;
