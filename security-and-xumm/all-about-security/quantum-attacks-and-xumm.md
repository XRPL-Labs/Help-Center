---
description: A little bit about Quantum attacks
---

# Quantum Attacks and Xumm

## **Introduction**

This article is meant to answer some basic questions about quantum computing and to explain our view on the future of quantum attacks as they relate to Xumm and the XRP Ledger.

### **What is a quantum computer?**

Theoretically, in the near future, there will be several different types of quantum computers that will be capable of doing certain types computation at very high speeds. Some of those computers will most likely be suitable for analyzing cryptographic algorithms. Those are referred to as CRQC's or “Cryptographically Relevant Quantum Computers”. CRQCs will theoretically be extremely adept at attacking and deciphering real world cryptographic systems.&#x20;

### **Which cryptographic systems are at risk of being attacked?**

The XRP Ledger uses asymmetric-key algorithms to secure XRPL account. Also referred to as public-key algorithms, asymmetric-key algorithms use paired keys (a public and a private key) in performing their function. The public key is known to all, but the private key is controlled solely by the owner of that key pair. The private key cannot currently be mathematically calculated through the use of the public key even though they are cryptographically related. In theory, CRQC's will be able to calculate the private key based solely on the information contained in the public transactions recorded on the XRPL.&#x20;

### **When will a quantum computer be ready to initiate a quantum attack?**

Some estimates suggest CRQC's will be viable in about 5 years time. One study suggests that a quantum computer possessing about 4000 qubits of processing power could theoretically crack the cryptography used by Bitcoin. Currently, IBM has a machine with just over 400 qubits of processing power.

### How does this apply to the XRP Ledger?

Currently, there is no agreed upon definition of what makes an algorithm quantum resistant.

In theory, a quantum resistant algorithm for the XRP Ledger must be able to:

* resist quantum factoring (See [Shor's algorithm](https://en.wikipedia.org/wiki/Shor's\_algorithm))
* resist quantum searching (See [Grover's algorithm](https://en.wikipedia.org/wiki/Grover's\_algorithm))
* resist quantum machine learning&#x20;

When such an algorithm is developed, integrating it into the XRPL should be a straight forward process. (Just as the Ed25519 algorithm was added).&#x20;

Keep in mind, any new algorithm that is added to the XRPL will need to be supported forever, so while it is a fairly easily process to add additional algorithms, it is not something to be taken lightly. Ideally, the XRPL community will wait as long as safely possible before adding a new one.

### What can I currently do to protect my assets?

There are currently two options to options to help protect against quantum attacks until quantum resistant algorithms are implemented on the XRPL:

1. Create a new XRPL account and move your assets to your new account then leave it alone. A CRQC will need an outgoing public transaction to analyze the public key of you account. Once you perform any transaction on your new account, it will be vulnerable to a quantum attack.
2. Create a new XRPL account and re-key your existing account to point to your new account then disable your master key on your existing account and leave it alone, Once you perform any transaction on your new re-keyed account, it will be vulnerable to a quantum attack.

### What is Xumm doing to prepare against quantum attacks?

One of the major projects the XRPL Labs team has been developing is adding smart contact functionality to the XRP Ledger. We call it, "Hooks".

A Hook can be developed to create any signing scheme you desire. For example, you could delegate a transaction through a Hook which would allow you to change your signing scheme to which ever algorithm you like. Such a hook would give you complete control over how your transactions would be signed and allow you to choose from various quantum resistant algorithms.

Another option would be to create a Hook that simply blocks any transaction that doesn't include a quantum resistant signature. This type of hook would prevent you from accidentally signing a transaction using a non-quantum resistant algorithm.&#x20;



**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
