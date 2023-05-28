---
description: How secure/safe is a Xumm (Tangem) card?
cover: ../.gitbook/assets/Large rock with Lock -2.jpg
coverY: 107
---

# How safe is a card?

There are lots of different cold wallets to choose from in the crypto space. Here are some of the main security features you get with a Xumm (Tangem) card.

### **How the card generates the account secret**

Xumm cards use a EAL 6+ certified microchip for secure operations.&#x20;

Upon first use, a private key is generated on the card using its cryptographically secure True Random Number Generator that lives inside the chip present in the plastic card.

The public key is then derived from the private key using Elliptic curve point multiplication.

Finally the public key is hashed to produce an XRP address.

The private key is stored securely on the card. It is never revealed and is not accessible by anyone - not even by the Xumm application.

### **How the transactions are signed with the card**

Xumm creates a sign request, then asks the user to sign that request by placing the card over the NFC reader on their mobile device. The sign request is sent to the card where it is signed or rejected **on the card**, then the sign request is returned to Xumm.&#x20;

{% hint style="warning" %}
The account secret never leaves the card.
{% endhint %}

So, while the Xumm app starts the signing operation, the card is exclusively responsible for actual signing a transaction and returning a signed hash back to the Xumm app.&#x20;

### **Understanding how NFC works**

Each card has a secure NFC smart-card chip with a Type A contactless interface embedded in it. &#x20;

In case you're wondering,

_**Near-field communication (NFC)** is a set of communication protocols that enables communication between two electronic devices over a distance of 4 cm or less_

_Source:_ [_Wikipedia_](https://en.wikipedia.org/wiki/Near-field\_communication)

The card uses the NFC smart-card chip to communicate with your phone directly to Xumm.

&#x20;

### **NFC vulnerabilities and possible attack vectors**

The primary attack vectors against a Xumm card fall under the category called "proximity" attacks.&#x20;

{% hint style="warning" %}
Proximity attacks are potential attack vectors for **all** wireless and NFC devices, not just Xumm cards.
{% endhint %}

Proximity attacks are those where a potential attacker needs to be really close to the card in order to be successful. The attacker could be a real person with a phone, just a phone laying down on a table, or even small NFC device no larger than Apple AirTag.

Since NFC allows mobile devices to establish radio communication with each other over short distances, there is a possibility, however remote, that an attacker might be able to intercept that radio communication.&#x20;

### **What Xumm is doing to prevent proximity attacks**

We have implemented three main security features to combat proximity attacks.

1. Pin/Passcode\
   Each card has the ability to configure a pin/passcode. By doing this, it greatly increases the security of your funds by forcing you to enter a pin before a transaction can be signed. For more information about configuring this option, please refer to the following article: \
   \
   \- [Creating a pin on your card](creating-a-pin-on-your-xumm-tangem-card.md)\

2. Security Delay\
   You might have noticed that you are required to hold the card against your phone for 15 seconds before it will sign a transaction. By doing this, a potential attacker would need to be within about 4 cm of your Xumm card for at least 15 seconds in order to send a transaction to it. In theory, you would notice someone standing so close to you for this long. \
   \

3.  Strict security settings\
    Tangem cards offer a large variety of settings that can only be configured at the factory. All Xumm cards leave the factory preconfigured to our specifications.&#x20;

    \
    Among them are:&#x20;

    * NFC communication between the card and Xumm app is encrypted
    * Keys are exchanged using the [ECDH](https://en.wikipedia.org/wiki/Elliptic-curve\_Diffie%E2%80%93Hellman) protocol with the pin mixed in for additional randomness
    * NFC communication sessions are short to minimize chance of NFC proximity attacks
    * All card features that are not specifically used by Xumm are disabled to narrow the attack surface
    * Various security checks are enabled to distinguish valid cards produced by Tangem from potentially malicious cards&#x20;

&#x20;
