---
description: How to upgrade your account to a stronger encryption algorithm
---

# Upgrading your encryption

/hint

{% hint style="info" %}
Before we continue, we want to assure you that the whichever version of Xumm that you are currently using is incredibly **safe**. Upgrading your accounts using our new algorithm simply increases the security from '**insane**' level to '**crazy insane'** level. This process is completely optional and while we recommend that you go through the process, it is not required.&#x20;
{% endhint %}

### A Brief background

All versions of Xumm prior to v2.4 use the AES 256-CBC encryption algorithm to encrypt your secret keys on your phone. It is the same algorithm currently used by banks, large businesses and even governments all over the world and is extremely secure.  The AES 256 is a standard encryption algorithm in the crypto industry and is widely used however...

### Pushing the envelope...

While the AES 256 (Advanced Encryption Standard) still remains the encryption algorithm of choice for governments and financial institutions around the world, it is still decades old. The latest AES 512-GCM algorothm is more advanced and &#x20;

The AES algorithm successively applies a series of mathematical transformations to each 128-bit block of data. Because the computational requirements of this approach are low, AES can be used with consumer computing devices such as laptops and smartphones, as well as for quickly encrypting large amounts of data. For example, the IBM z14 mainframe series uses AES to enable pervasive encryption in which all the data in the entire system, whether at rest or in transit, is encrypted.

AES is a symmetric algorithm which uses the same 128, 192, or 256 bit key for both encryption and decryption (the security of an AES system increases exponentially with key length). With even a 128-bit key, the task of cracking AES by checking each of the 2128 possible key values (a “brute force” attack) is so computationally intensive that even the fastest supercomputer would require, on average, [more than 100 trillion years](https://www.eetimes.com/document.asp?doc\_id=1279619) to do it. In fact, AES has never been cracked, and [based on current technological trends](https://www.researchgate.net/publication/316284124\_The\_AES-256\_Cryptosystem\_Resists\_Quantum\_Attacks), is expected to remain secure for years to come.

Introduced in Xumm v2.4, you now have the option of upgrading your encryption algorithm from AES 256 CBC to AES 512 GCM.



