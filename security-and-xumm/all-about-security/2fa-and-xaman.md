---
description: Understanding Two-factor authentication (2FA)
---

# 2FA and Xaman

### **What is 2FA?**

Two-factor authentication (2FA) is a security process in which users provide two different authentication factors to verify themselves. Two-factor authentication provides a higher level of security than single-factor authentication (SFA), in which the user provides only one factor -- typically, a password or passcode.&#x20;

### **Are there different types of 2FA?**

Some 2FA methods are:

* OTP (one time passcode) over SMS
* Out of Band SMS
* Google Authenticator
* Mobile Authentication
* Push Notification
* Soft Token
* OTP (one time passcode) over Email
* Out of band email
* Display Hardware token
* Yubikey hardware token
* Security Questions
* Phone verification
* Voice verification

### **The XRP Ledger and 2FA**

2FA relies on a “shared secret”.

For example, when Google asks you to enter a 6 digit code to access your account, you and Google have a shared secret that is used to “derive” these codes.

The trick is that the secret is never sent, only the codes are. So an attacker can’t get the secret and they can’t generate the code.

This works great on a centralized system like Google but it does not work so well on the XRP Ledger since there is no place to store a “shared secret” on the XRPL. In order to implement 2FA, the XRPL would need to implement a centralized, 3rd party system to "control" access. This does not make sense on a public, decentralized blockchain. (Adding a centralized system on a decentralized blockchain.)

You might think that multi-signing accomplishes the same thing as 2FA in that you could require 2 or more signers to submit a transaction, but that only simulates 2FA, and even then, only if you sign with two separate devices that are not in the same location.

### **Xumm uses "4FA"**

Consider the following requirements to get access to your XRP Ledger account managed with Xumm:

1\) physical access to your phone

2\) some way to unlock your phone

3\) some way to access Xumm (could be the same as #2, e.g. FaceID / Fingerprint)

4\) some way to sign transactions on your account (optional extra security using a configured password)

**We can not control the first two options. You are responsible for your phone and keeping it safe. You are also responsible for creating a secure password to unlock your phone.**

However, let's say that someone has acquired your phone and somehow circumvented your password and now has full access to it.

An attacker launches Xumm and tries to hack your 6 digit passcode. Six digits is only 999,999 possible combinations, (000000, 000001, 000002 -> 999997, 999998, 999999), so they start entering various passcodes at a rate of 1 one passcode per second and about 11 days later they have tried all of the possible combinations. So now they have access to Xumm.

Except for one small countermeasure we implemented in Xumm. We have configured Xumm to only allow 5 attempts before Xumm starts to add time to the next attempt. After the ninth wrong entry, Xumm requires a delay of **2 hours** to input again. That means 12 attempts per day. Now instead of 11 days to try all of the possible combinations, it would take about 83,332 days to try them all... Or about **228 years**.

However, let's say someone manages to guess your 6 digit passcode in under 228 years, now they have to figure out your signing password. Honestly, how hard can that really be right? Well, we set the limit for the number of characters you can make your password to a mere 2,091,752 terabytes.  In other words, you could make your password so long, it would take up all of the storage space on your 512GB phone and about 4 million other 512GB phones before you ran out of space to store it. Provided you selected a strong signing password, this could take awhile to guess.

&#x20;

### **Problems with 2FA**

<figure><img src="../../.gitbook/assets/Rubber hose.png" alt=""><figcaption></figcaption></figure>

&#x20;

2FA only works when:

* You have a centralized system (Google, Twitter, Exchanges, name it)
* You are registered and need to login (via email / user name)

This only makes sense if the access password is on a separate device, ie. NOT on your smartphone. If your receive your 2FA password via SMS on your phone, 2FA won't help. The main weakness here is the dependency on the service provider. Even without access to your phone, if your 2FA password is delivered via SMS, all someone needs to do is get access to your phone number. This is easier than you might think. Xumm does not have any of these issues.

&#x20;

### **Ok, what do you recommend I do then?**

XRP Ledger accounts created using Xumm are already incredibly safe but we certainly understand the desire maximize the security of your account. That is why we partnered with Tangem to create the Xumm Tangem card.

<figure><img src="../../.gitbook/assets/Xumm Tangem card -3.png" alt=""><figcaption></figcaption></figure>

Instead of using a hardware wallet, or a static, written down secret (that can't be used easily), the Xumm Tangem cards contain a chip and use NFC ([near field communication](https://nl.wikipedia.org/wiki/Near-field\_communication)). The chip **generates** an account secret, while being powered using NFC (by your iOS/Android device). This means the cards are shipped without an account secret on them, and can only be generated on the card, by the owner of the card. The chip used in Xumm Tangem cards offers bank grade security and have been fully audited.

If you are interested in learning more about the cards, check out this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">All about Xumm (Tangem) cards</td><td></td><td></td><td><a href="../../xumm-tangem-cards/xumm-tangem-cards.md">xumm-tangem-cards.md</a></td><td><a href="../../.gitbook/assets/monolith in stream.jpg">monolith in stream.jpg</a></td></tr></tbody></table>
