# How secure is Xumm?

## Comparing different wallets

It is not uncommon for people to want to try to compare to different wallets, different platforms and different devices in terms of how secure they are. They want the best security they can get when it comes to their assets so why not?  It makes sense to get the best when it comes to protecting your assets.

The problem with this approach is that crypto security is a huge and highly technical subject which requires years of education and experience to understand. Simply reading an article and thinking you are in any way qualified to make a valid comparison is...dangerous. Certainly read as much as you can about this topic, but please, this article is not meant to be an exhaustive discussion on Xumm's security. It is merely a glimpse

## **It is a crazy time in the crypto world, how secure is Xumm?**

There are several ways to view security when it comes to your XRP Ledger account.

Your first line of security starts with your phone.

Here are the top 9 security threats to your phone.

* Social Engineering
* Data Leakage via Malicious Apps
* Unsecured Public WiFi
* End-to-End Encryption Gaps
* Internet of Things (IoT) Devices
* Spyware
* Poor Password Habits
* Lost or Stolen Mobile Devices

Source: [The Nine most common security threats to mobile devices](https://auth0.com/blog/the-9-most-common-security-threats-to-mobile-devices-in-2021/) &#x20;

So, here are some things to consider:

* Is your mobile device up to date with all security and OS updates?
* Do you use a VPN?
* Do you have an anti virus program that is up to date?
* How often do you use public wifi?
* Do you have a firewall on your phone?
* Do you have strong passwords?
* How often do you change your passwords?

If your phone is not secure, the best, most secure software wallet in the world (aka Xumm) will not be able to protect your assets. Starting out with a modern, up to date, secure mobile device is essential when it comes to securing your assets.

## **No problem. My phone is secure.**

So your phone has no spyware or malware installed. It is up to date. You use a top of the line VPN, anti-virus software and firewall. You have installed Xumm and you used Xumm to create your XRP Ledger account. Well done!

Let's consider your XRPL account. Xumm can generate three hundred and forty undecillion, two hundred and eighty-two decillion, three hundred and sixty-six nonillion, nine hundred and twenty octillion, nine hundred and thirty-eight septillion, four hundred and sixty-three sextillion, four hundred and sixty-three quintillion, three hundred and seventy-four quadrillion, six hundred and seven trillion, four hundred and thirty-one billion, seven hundred and sixty-eight million, two hundred and eleven thousand, four hundred and fifty-six different accounts using the secret number standard. Xumm will provide you with one of those possible accounts.

It is hard to imagine how many accounts that actually is, so maybe this will help.

If you had a job that paid you 390 trillion euros per hour, you would have to work 24 hours per day, 7 days per week, 365 days per year for about 99 quadrillion years to earn 340 undecillion euros.

It is unimaginably difficult for someone to guess your account number out of 340 undecillion possible accounts. you would need to make 390 trillion guess per hour for **99 quadrillion years** to guess them all.

## **How is that different from a cold/hard wallet?**

It is no different. Whether an account is generated off line or online, there is no difference in the total number of possible accounts. The chances of guessing your account secret is the same.

## **There must be some difference…**

It comes down to [entropy](https://en.wikipedia.org/wiki/Entropy\_\(information\_theory\)).  How well does the software generate randomness? How does it pick from the 340 undecillion possibilities?&#x20;

**Is that why you are always telling people to protect their Secret Numbers?**

Exactly! The only way someone can access your account is if they know your Secret Numbers. The chances of someone figuring them out are 1 in 340 undecillion.

**What about the 6 digit passcode to access Xumm. That is only 1 million possibilities. Anyone could guess that.**

You are absolutely right. Let’s say that someone has acquired your phone and somehow circumvented your password and now has full access to it.

An attacker launches Xumm and tries to hack your 6 digit passcode. Six digits is only 999,999 possible combinations, (000000, 000001, 000002 -> 999997, 999998, 999999), so they start entering various passcodes at a rate of 1 one passcode per second and about 11 days later they have tried all of the possible combinations. So now they have access to Xumm.

**Except** for one small countermeasure we implemented in Xumm. We have configured Xumm to only allow 5 attempts before Xumm starts to add time to the next attempt. After the ninth wrong entry, Xumm requires a delay of **2 hours** to input again. That means 12 attempts per day. Now instead of 11 days to try all of the possible combinations, it would take about 83,332 days to try them all… Or about **228 years**.

**Ha! So now its down from 99 quadrillion years to 228 years!**

However, let’s say someone manages to guess your 6 digit passcode in under 228 years, now they have to figure out your signing password. Honestly, how hard can that really be right? Well, we set the limit for the number of characters you can make your password to a mere 2,091,752 terabytes.  In other words, you could make your password so long, it would take up all of the storage space on your 512GB phone and about 4 million other 512GB phones before you ran out of space to store it. Provided that you selected a strong signing password, this could take awhile to guess.

**Basically you’re saying it is impossible. Why would I need the Xumm Tangem cards then?**

It is basically impossible to guess the Secret Numbers in your lifetime and if your phone is lost or stolen, you have plenty to time to move your assets to another account. The Xumm Tangem cards are the perfect way of mitigating the risk of a compromised phone, especially if you follow our recommend guidelines here:

* [Tangem cards - Best Practices](https://support.xumm.app/hc/en-us/articles/4416929335186)

Although we believe that your phone is secure and that it will never get lost/damaged or stolen, having a pair of cards will ensure that even if your phone was compromised, your XRPL account is safe. Here’s how…

A Xumm Tangem card will generate a set of private keys **on the card**. They never leave the card. No one will ever see them, (including you) and there is no way to access them. You can never be tricked into giving your account secret away and the only way to access your account is by having the card with you.

**This sounds better than a cold wallet.**

You’re right. Most cold wallets give you the account secret (Secret Numbers/Family Seed/Mnemonic) so you can be tricked into giving it away. This can not happen with the Xumm Tangem cards. Your private key (keypair) is generated by a chip inside the Tangem card. The keypair **cannot be extracted or wiped** from the card. The [key generation by the chip inside the card is very secure](https://twitter.com/Tangem/status/1346555757009899520?s=20) and has been audited. There is no way for you to access them so you can never give them away. Like we said, the account secret is **on the card** and the only way to access you account is by physically having the card with you.

**Could someone hack the card?**

Just like Xumm, the chances of guessing the account secret is 1 out of 340 undecillion.

Here are some more facts about the cards.

* Contains $0 & 0 XRP in value upon delivery: the card will generate a keypair when first used with Xumm, and the newly generated keypair (and r-address on the XRPL) will have to be [activated with 10 XRP as per XRP Ledger requirement](https://support.xumm.app/hc/en-us/articles/360018166079) first.
* Card dimensions: 85.60 mm x 54.00 mm x 0.80 mm
* Weight: about 4 grams
* **S3D350A microchip from Samsung**
* **Common Criteria EAL6+ Assurance Level**
* Uses 3DES, AES, RSA, & ECC cryptography
* **Arm SecurCore SC000 Core**
* Compatible with Android 5.1+ or iPhone with NFC (select models, iOS 13+)
* **Firmware** [**audited**](https://research.kudelskisecurity.com/2018/08/06/audit-of-tangems-smartcard-wallet-code/) **by Kudelski Security**

**I want to know more about the cards.**

Of course. check out this article.

* [Safer savings: Introducing the Xumm Tangem Card!](https://support.xumm.app/hc/en-us/articles/360018166539)

**What about if I connect Xumm to a “questionable” website or I scan an untrusted QR code?**

Xumm will never share your private keys with a third party website or application. The website/app will deliver a sign request to Xumm and Xumm will display the sign request for you to approve or deny. Once you approve it, Xumm signs it locally on your phone and returns only the signature to the website/application. Your private keys never leave your phone. Xumm only signs after approval, locally, and then only returns the end product: the signed transaction.

**…and a Trust Line? Can I be hacked by creating a Trust Line?**

It is not possible for someone to access the tokens in your XRPL account via a Trust Line. A token issuer can freeze or misconfigure their own Trust Line though, which would make their issued tokens unusable, but they can not access your account. It is also possible that a token issuer could send you messages via the XRPL (once they know your r-address) and somehow convince you to send them your secret numbers. While not really considered a “hack”, the results are pretty much the same.

#### **What about spam transactions? Are they dangerous?**

Unfortunately there is nothing that can be done to stop prevent spam on the XRP Ledger. There are no “spam filters” yet, so when we identify a spam transaction or a transaction that is coming from a fraudulent address, XUMM will alert you with a warning message about the sender of the transaction.

Although annoying, most people are choosing to ignore the messages.

If you are interested in learning more about spam on the XRPL, check out this article:

[https://support.xumm.app/hc/en-us/articles/6156825861394-Spam-on-the-XRP-Ledger](https://support.xumm.app/hc/en-us/articles/6156825861394-Spam-on-the-XRP-Ledger)

**Can the government freeze my funds via Xumm? What happens if the government seized XRPL Labs?**

The XRP Ledger is a decentralized blockchain. A governmental agency might be able to shut down some of the XRPL validators and nodes in a particular region, but a single government could not shut down all of them all over the world. The XRPL servers are distributed around the planet to form a global network. In other words, the XRP Ledger will still run and validate transactions regardless if a bunch of servers were shut down. That is part of the idea behind decentralization.

Another feature of the XRPL is that no one, not a government or an exchange or even us can access your non custodial XRPL account. You are the only one with the account secret, so without that, there is no way to confiscate or freeze your XRP.

Finally, Xumm will run regardless if XRPL Labs exists or not. Xumm does not need our backend servers to function. All of the XRPL communication and signing happens locally on your mobile device, from within Xumm. It does not need our backend servers for that.

…plus, if worse came to worse, you could always take your account secret and just use another wallet if you wanted to.

**Ok. Summarize it for me.**

* **Keep your phone safe, up to date and free of spyware and malware**
* **Never give your account secret (Secret Numbers/Family Seed/Mnemonic) to anyone, for any reason**
* **Xumm is designed with security in mind. Security is number one priority (but Xumm can’t be safer than your device and your own practices are)**
* **Xumm Tangem cards are the best solution for maximum security**

**Additional reading**

* [2FA and XUMM](https://support.xumm.app/hc/en-us/articles/4417265298834)
* [XUMM Security Measures](https://support.xumm.app/hc/en-us/articles/360018166719)
* [Will XUMM operate after a Natural Disaster?](https://support.xumm.app/hc/en-us/articles/4499411625618)

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the **Xumm Support xApp** in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
