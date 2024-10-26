---
description: >-
  Is Xaman a safe place to store my secret keys? Has it been audited? How secure
  is Xaman?
cover: ../../.gitbook/assets/Tokens and coins -1 (1).png
coverY: 0
---

# How secure is Xaman?

## Comparing different wallets

It is not uncommon for people to want to try to compare different wallets, different platforms and different devices to determine which one is "best".  When it comes to protecting your assets, for many people, only the best will do so it only makes sense to get the best when it comes to protecting your funds, right...?

The challenge with this approach is that crypto security is a huge and highly technical subject which requires years of education and experience to fully understand. Simply reading an article or watching a Youtube video then thinking you have enough information to make a comprehensive comparison between wallets is...dangerous. Certainly we recommend reading as much as you can about this topic, but please keep in mind, this article is not meant to be an exhaustive discussion of Xaman's (formerly Xumm) security. It is merely a glimpse...

## **It is a crazy time in the crypto world, how secure is Xaman?**

There are several ways to view security when it comes to your XRP Ledger account but your first line of security always starts with your mobile device.

Here are the top 9 security threats to look out for when it comes to your phone.

* Social Engineering
* Data Leakage via Malicious Apps
* Unsecured Public WiFi
* End-to-End Encryption Gaps
* Internet of Things (IoT) Devices
* Spyware
* Poor Password Habits
* Lost or Stolen Mobile Devices

Source: [The Nine most common security threats to mobile devices](https://auth0.com/blog/the-9-most-common-security-threats-to-mobile-devices-in-2021/) &#x20;

So before you even get around to installing Xamana, here are some things to consider:

* Is your mobile device up to date with all security and OS updates?
* Do you use a VPN?
* Do you have an anti virus program that is up to date?
* How often do you use public wifi?
* Do you have a firewall on your phone?
* Do you have strong passwords?
* How often do you change your passwords?

If your phone is not secure, the best, most secure software wallet in the world (aka Xaman) will not be able to protect your assets. Starting out with a modern, up to date, secure mobile device is essential when it comes to securing your assets.

## **No problem. My phone is secure.**

So your phone has no spyware or malware installed. It is up to date. You use a top of the line VPN, anti-virus software and firewall. You have installed Xaman and you used Xaman to create your XRP Ledger account. Well done!

Let's consider your XRPL account. Xaman can generate three hundred and forty undecillion, two hundred and eighty-two decillion, three hundred and sixty-six nonillion, nine hundred and twenty octillion, nine hundred and thirty-eight septillion, four hundred and sixty-three sextillion, four hundred and sixty-three quintillion, three hundred and seventy-four quadrillion, six hundred and seven trillion, four hundred and thirty-one billion, seven hundred and sixty-eight million, two hundred and eleven thousand, four hundred and fifty-six different accounts using the secret number standard. Xaman will provide you with one of those possible accounts.

It is hard to imagine how many accounts that actually is, so maybe this will help.

If you had a job that paid you 390 trillion euros per hour, you would have to work 24 hours per day, 7 days per week, 365 days per year for about 99 quadrillion years to earn 340 undecillion euros.

It is unimaginably difficult for someone to guess your account number out of 340 undecillion possible accounts. You would need to make 390 trillion guess per hour for **99 quadrillion years** to guess them all.

{% hint style="success" %}
Entire books have been dedicated to this topic but if you are interested in learning a bit more about it, you can check out this link on [entropy](https://en.wikipedia.org/wiki/Entropy\_\(information\_theory\)). It is not exactly "easy reading" but it will get you going in the right direction.
{% endhint %}

## **How is that different from a cold/hard wallet?**

It is no difference. Whether an account is generated off line or online, there is no difference in the total number of possible accounts. The chances of guessing your account secret is the same.

## **Why you are always telling people to protect their Secret Numbers?**

The only way someone can access your XRP Ledger account is if they know your Secret Numbers. Keeping them safe is the best way to keep your assets safe. The second you share your Secret Numbers with anyone, you give them 100% access to your funds and give them permission to use your funds in any way they choose.&#x20;

{% hint style="danger" %}
**Never** give your Secret Numbers to anyone. If someone asks for them, that person is trying to steal your funds!
{% endhint %}

## **What about the 6 digit passcode to access Xaman. That is only 1 million possibilities. Anyone could guess that.**

You are absolutely right. Let’s say that someone has acquired your phone and somehow circumvented your phone's password and now has full access to it.

An attacker launches Xaman and tries to hack your 6 digit passcode. Six digits is only 999,999 possible combinations, (000000, 000001, 000002 -> 999997, 999998, 999999), so they start entering various passcodes at a rate of 1 one passcode per second and about 11 days later they have tried all of the possible combinations. So somewhere along the way, they would get  access to Xaman, right?

That makes sense, **except** for one small countermeasure we implemented in Xaman. We have configured Xaman to only allow 5 attempts before it starts to add time to the next attempt. After the ninth wrong entry, Xaman requires a delay of **2 hours** before you can input a passcode again. That means 12 attempts per day. Now instead of 11 days to try all of the possible combinations, it would take about 83,332 days to try them all… Or about **228 years**.

## **Ha! So now its down from 99 quadrillion years to 228 years!**

However, let’s say someone manages to guess your 6 digit passcode in under 228 years, now they have to figure out your signing password. (If you configured one, which we recommend that you do.) Honestly, how hard can that really be right? Well, we set the limit for the number of characters you can make your password to a mere 2,091,752 terabytes.  In other words, you could make your password so long, it would take up all of the storage space on your 512GB phone and about 4 million other 512GB phones before you ran out of space to store it. Provided that you selected a strong signing password, this could take awhile to guess.

The point is, there are multiple layers of security in Xaman to protect your XRPL account. A potential hacker who gets your phone, needs to crack the phone's passcode, then crack Xaman's passcode, then crack Xaman's signing password. This is very, very difficult to do if you use good passcodes/passwords.

## Does the Xaman passcode and signing password protect my XRPL account?

Yes and no.&#x20;

The passcode that you configure in Xaman is designed to keep people from accessing the Xaman application. It **does not** protect your Secret Numbers from being used by someone else.

For example, let's say you have two phones and you have installed Xaman on both of them. You could import your secret numbers into both phones and access your XRP Ledger account from both devices. The passcode that you setup on one phone does not affect your second phone. You could configure one phone with one passcode and your other phone with a different passcode. Changing your passcode on either device does not affect the other device. In other words, the Xaman passcode (and signing password) are local security measures on your device to prevent accessing the Xaman app.

The goal for Xaman is to protect your Secret Numbers **on your phone**. The passcode and signing passwords are designed to help do this.

## **Why would I need the Xaman (Tangem) cards then?**

By this point, hopefully you realize it is basically impossible to **guess** the Secret Numbers in your lifetime. The amount of possibilities is just too great, but... there is the risk that your phone could be lost or stolen. If that were to happen, and given enough time and resources, your phone could be hacked and once someone gained access to your phone, they might be able to hack Xaman and if they did that they might be able to decrypt your secret numbers, and if they did that, they could access your funds! &#x20;

We are talking theoretical here but still, it might be possible, so we decided to offer a way to mitigate the risk of a lost or stolen phone... enter **Xaman (Tangem) cards**.

Xaman cards are the perfect way to alleviate the risk of a compromised phone, especially if you follow our recommend guidelines here:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">Best Security Practices Using Xaman (Tangem) cards</td><td></td><td></td><td><a href="../../xumm-tangem-cards/best-security-practices-using-a-xumm-card.md">best-security-practices-using-a-xumm-card.md</a></td><td><a href="../../.gitbook/assets/Rocky stream.png">Rocky stream.png</a></td></tr></tbody></table>

Although we believe that your phone is secure and that it will never get lost/damaged/stolen or hacked, having a pair of cards will ensure that even if your phone **was** ever compromised, your XRPL account would still be safe. Here’s how they work…

A Xaman card will generate a set of private keys **on the card**. They never leave the card. No one will ever see them, (including you) and there is no way to access them. You can never be tricked into giving your account secret away and the only way to access your account is by having the card with you.

## **This sounds better than a cold wallet.**

You’re right. Most cold wallets give you the account secret (Secret Numbers/Family Seed/Mnemonic) so you can be tricked into giving it away. This cannot happen with the Xaman cards. As well, most cold wallets also require that you have a computer to use them and computers can be VERY difficult to secure. This is not an issue with the Xaman cards.

Your private key (keypair) is generated by a chip inside the Xaman card. The keypair **cannot be extracted or wiped** from the card and the [key generation by the chip inside the card is very secure](https://twitter.com/Tangem/status/1346555757009899520?s=20). (And has been audited.) There is no way for you to access them so you can never give them away. Like we said, the account secret is **on the card** and the only way to access your account is by physically having the card with you.

## **I want to know more about the cards.**

Of course. check out this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">All about Xaman (Tangem) cards</td><td></td><td></td><td><a href="../../xumm-tangem-cards/xumm-tangem-cards.md">xumm-tangem-cards.md</a></td><td><a href="../../.gitbook/assets/monolith in stream.jpg">monolith in stream.jpg</a></td></tr></tbody></table>

## **What about if I connect Xaman to a “questionable” website or I scan an untrusted QR code?**

Xaman will never share your private keys with a third party website or application. The website/app will deliver a sign request to Xaman and Xaman will display the sign request for you to approve or deny. Once you approve it, Xaman signs it locally on your phone and returns only the signature to the website/application. Your private keys never leave your phone. Xaman only signs after approval, locally, and then only returns the end product: the signed transaction.

## **…and a Trust Line? Can I be hacked by creating a Trust Line?**

It is not possible for someone to access your **XRP** in your XRPL account via a Trust Line, however creating a Trust Line does pose several risks.

* &#x20;A token issuer can freeze their own Trust Line, which would make their issued tokens unusable. ( but they can not access your account or your XRP.)
* A token issuer can misconfigure their Trust Line, which could make their issued tokens unusable. (Again, they can not access your account or your XRP.)
* A token issuer could send you messages via the XRPL (once they know your r-address) and somehow convince you to send them your secret numbers. (While not really considered a “hack”, the results are pretty much the same.)
* A token issuer could initiate the 'clawback' feature on their Trust Line which allows them to take back as much of their token as they like, as often as they like, whenever they like.

See this link for more information about the Clawback feature on the XRPL:\
\
[https://github.com/XRPLF/XRPL-Standards/tree/master/XLS-0039d-clawback](https://github.com/XRPLF/XRPL-Standards/tree/master/XLS-0039d-clawback)

## **What about spam transactions? Are they dangerous?**

A 'spam' transaction is one which is unsolicited.&#x20;

In most cases, someone will send a small amount of XRP to an account along with a message, advertisement, special offer, marketing idea, business opportunity, etc. The idea is that you will read the message then decide to investigate and either buy their product, visit their website, invest in their business opportunity, etc.

The spam transactions themselves **do not pose a threat** to your XRPL account and do not cost you anything, but the 'special offer" they advertise is often risky and dangerous

If you would like to learn more about spam on the XRPL, check out this article:&#x20;

{% embed url="https://help.xumm.app/learning-more-about-xumm/spam-on-the-xrp-ledger" %}

## **Can the government freeze my funds in Xaman? What happens if the government seized XRPL Labs?**

The XRP Ledger is basically a giant, decentralized network. While it is possible that a governmental agency might be able to shut down parts of the XRPL in a particular region, (validators, nodes, internet access points) a single government could not shut down all of them all over the world. The XRPL servers are distributed around the planet to form a global network. It will still run and validate transactions regardless if a bunch of servers were shut down. (That is part of the idea behind decentralization.)

Another feature of the XRPL is that no one, not a government or an exchange or even us can access your XRPL account. You are the only one with the account secret, so without that, there is no way to confiscate or freeze your XRP.

Finally, Xaman will run regardless if XRPL Labs exists or not. Xaman does not need our backend servers to function. All of the XRPL communication and signing happens locally on your mobile device, from within Xaman. It does not need our backend servers for that.

…plus, if worse came to worse, you could always take your account secret and just use another wallet if you wanted to.

{% embed url="https://help.xumm.app/app/learning-more-about-xaman/moving-your-xrpl-account-to-another-wallet" %}

## **Ok. Summarize it for me.**

* **Keep your phone safe (physically), up to date and free of spyware and malware**
* **While security is our number one priority, Xaman can be made safer if you avoid risky interactions with the internet (eg. - public wifi, shady websites, etc.), install a good firewall and use a VPN when possible.**
* **Never give your account secret (Secret Numbers/Family Seed/Mnemonic) to anyone, for any reason**
* **Xumm (Tangem) cards are the best solution for long term storage, large account balances and maximum security**
