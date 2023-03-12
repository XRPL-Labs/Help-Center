# Quantum Attacks and Xumm

{% hint style="info" %}
This article is currently under construction
{% endhint %}

## **Introduction**

This article is not meant to be a definitive source of information about all things quantum related. It is meant to answer some basic questions about quantum computing and to explain our view on the future of quantum attacks as they relate to Xumm and the XRP Ledger.

### **What is a quantum computer?**

Theoretically there will be several different types of quantum computers that can address some types of computation, but the ones you are going to be most concerned about are those which will be suitable for analyzing cryptographic algorithms. Those are referred to as CRQC's or “Cryptographically Relevant Quantum Computers”. CRQCs will theoretically be capable attacking real world cryptographic systems.&#x20;

### **When will a quantum computer be ready to initiate a quantum attack?**

Recently we have receive a number of questions about “quantum attacks” and what Xumm is doing to

Any quantum-resistant standard will be secure against all envisioned and understood quantum computing capabilities.

Have you ever sent or received an email? Checked your credit card balance online? Visited and e-commerce site?  All these sites and services use a web protocol called HTTPS that encrypts the data that is sent across the internet.

### You just created the worlds first CRQC. What should we do?

You've spent decades educating yourself in cryptography, physics, coding, mathematics and computer science. You've spent millions of dollars in equipment and research. You could easily work for any of the biggest companies in the world or get a top level government or military contact, but instead you decide to use your CRQC to pursue a life of crime....

You decide to risk financial ruin, millions of dollars of highly technical and sophisticated equipment, federal prosecution and life in prison to break the encryption on the XRP Ledger.  You could break the encryption on any of the thousands of banks in the world, or any of the sites on the world wide web. You could decrypt military and government databases across the planet. You could go after any private or public blockchain in the world, any crypto exchange, any company, but you decide that the XRP Ledger is the best place to start your criminal empire. That's simply brilliant. Let's go through this.

You decide to skip over the 4 accounts with over 1 billion XRP in them and the 26 accounts with over 500  million XRP in them and the 55 accounts with over 100 million XRP in them and just go after the accounts with under 100 million. Good plan, you don't want to be greedy after all. Keep in mind the XRPL is a **public blockchain**, so all of the transactions that you do are public, easily traceable and that large transactions are monitored and flagged by many organizations and individuals around the world. You could have picked from thousands of private institutions, but you want to take the risk so you decrypt a couple of accounts and send them to your favorite crypto exchange to 'cash out".  &#x20;

So how does that work? You have already decrypted and accessed the crypto exchange and falsified your identity. You probably already erased your true identity from all government databases and created new identities around the world as well. Now you need to convince the crypto exchange to convert your crypto into fiat. In the meantime, word has gotten out about your little heist. People have noticed your transaction and have started to investigate and the word quickly spreads around the XRPL ecosystem that something is no quite right. What do you think happens to the price of XRP the second the community learns that multi-million dollar accounts are being decrypted? What do you think happens to the value of your tokens?

Now what…? The second that word gets out that a quantum computer hacker is attacking any blockchain, the price of that token goes down to zero. Who would want to own a token that is worthless?

#### ****

#### **But what if they wanted to risk multi-million dollar quantum computer and criminal prosecution to hack my account?**

Let’s assume they skip over the the 4 accounts with over 1 billion XPP and the the 26 accounts with over 500 million XRP and the 55 accounts with over 100 million XRP and target your XRPL account. Before they can target you, they need to know your r-address.

/attachments/token/1zF79x5wiu6nQvq99z8W84yQU/?name=image.png

So you have two options to protect against quantum attacks until quantum resistant algorithms are delayed on the XRPL:

1. Create a new XRPL account and move your assets to your new account then leave it alone. Once you perform any transaction on your new account, it will be vulnerable to quantum attacks.
2. Create a new XRPL account and re-key your existing account to point to your new account then disable your master key on your existing account and leave it alone, Once you perform any transaction on your new re-keyed account, it will be vulnerable to quantum attacks.

#### **What is a quantum computer and what are quantum attacks?**

Recently we have receive a number of questions about “quantum attacks” and what Xumm is doing to

#### **When will a quantum computer be ready to initiate a quantum attack?**

Recently we have receive a number of questions about “quantum attacks” and what Xumm is doing to

#### **Could someone direct a quantum attack at Xumm?**

No, a quantum attack could not be directed at Xumm. (Xumm is non-custodial, unhosted wallet.) A quantum attack would be directed at an XRP Ledger account and the only way to attack an XRPL account is to know what the public address is. (The “r” address.)

/attachments/token/1zF79x5wiu6nQvq99z8W84yQU/?name=image.png

Once someone knows your r-address, they can launch an attack on you.  You have two options to protect against quantum attacks until quantum resistant algorithms are delayed on the XRPL:

1. Create a new XRPL account and move your assets to your new account then leave it alone. Once you perform any transaction on your new account, it will be venerable to quantum attacks.
2. Create a new XRPL account and re-key your existing account to point to your new account then disable your master key on your existing account and leave it alone, Once you perform any transaction on your new re-keyed account, it will be venerable to quantum attacks.

quantum resistant algorithms will be needed to protect crypto assets. Currently, there is no agreed upon definition of what makes an algorithm quantum resistant. However, there are a few general criteria that are often used. First, an algorithm must be resistant to quantum computers that can perform quantum factoring. This type of quantum computer would be able to factor large numbers very quickly, which could potentially break RSA encryption. Second, an algorithm must be resistant to quantum computers that can perform quantum search. This type of quantum computer would be able to search through a large space very quickly, which could potentially break elliptic curve cryptography. Third, an algorithm must be resistant to quantum computers that can perform quantum machine learning. This type of quantum computer would be able to learn algorithms very quickly, which could potentially break hash-based signatures.

Experts estimate that a quantum computer possessing about 4000 qubits of processing power could theoretically crack Bitcoins cryptography. However, we may still be a long way away from this as the Eagle, the most powerful quantum computer in the world developed by IBM has only 127 qubits of processing power.

XRP uses a cryptographic algorithm called RSA-2048. This algorithm is believed to be resistant to quantum computers that can perform quantum factoring. However, it is not known to be resistant to other types of quantum computers. In addition, XRP uses elliptic curve cryptography. This type of cryptography is believed to be resistant to quantum computers that can perform quantum search.

JoelKatz reply:

Additional algorithms can easily be added, just as we added Ed25519. Existing accounts can be re-secured with a new key if desired. So you won’t need a new ripple address.

We haven’t actually added any quantum-safe algorithms yet because none of the ones available today are perfect for our use case. And any algorithm we add we’ll have to support forever. So we’d prefer to wait as long as we safely can so that we’ll have the most information to make the choice of algorithm(s) to implement.

“XRPL is not quantum resistant. It could be made so, but with the present mechanims we have, the result would kind of suck because the quantum resistant algorithms we know of all have painful disadvantages in blockchain applications. My current thinking is that we monitor the state of the art carefully and implement the best quantum resistant algorithms whenever the risk looks to be within about 5 years of materializing. I don’t think we’re there yet.”

Per [XRPL.org](http://xrpl.org) ->[https://xrpl.org/cryptographic-keys.html#future-algorithms](https://xrpl.org/cryptographic-keys.html#future-algorithms)

#### Future Algorithms

In the future, it is likely that the XRP Ledger will need new cryptographic signing algorithms to keep up with developments in cryptography. For example, if quantum computers using[Shor’s algorithm](https://en.wikipedia.org/wiki/Shor's\_algorithm)(or something similar) will soon be practical enough to break elliptic curve cryptography, XRP Ledger developers can add a cryptographic signing algorithm that isn’t easily broken. As of mid 2020, there’s no clear first choice “quantum-resistant” signing algorithm and quantum computers are not yet practical enough to be a threat, so there are no immediate plans to add any specific algorithms.

* Elliptic curve schemes including secp256k1 and Ed25519 are vulnerable to Shor’s algorithm on theoretical quantum computers. Current quantum computers are not capable of performing Shor’s algorithm with enough qubits to break elliptic curve keys of the size used by the XRP Ledger. Quantum computing technology continues to advance and it is unknown how soon it may become feasible to break these keys, but estimates of “within a decade” are plausible.

Quantum computing is a hot topic right now and there are many opinions on how it will affect current security on the XRP Ledger.

You can find plenty of theories out there only what will happen but consider this:

Even when Quantum computers arrive, why would they go after your account or mine? The XRPL is a public blockchain. All transactions are public so lets say they crack my account secret then they take my 5000 XRP. The second that word gets out that a quantum computer hacker is attacking any blockchain, the price of that token goes down to zero. Who would want to own a token that is worthless? And why would they even bother? Why not hack any one of a thousand different banks? They are private organizations… or how about the Federal reserve? Plus why bother being a criminal with all that computer power? It’s far easier to make legitimate money rather than becoming a criminal. Companies would line up and pay millions for access to that kind of computing power  …and a quantum computers will cost millions and millions of dollars to create and operate. Why risk that investment and jail time when people would be kicking down your door with truck loads of money to pay you for that kind of computing power?

But assuming that someone is dumb enough to try to attack my account, (rather than the 4 accounts with over 1 billion XPP, or the 26 accounts with over 500 million XRP, or the 55 accounts with over 100 million XRP or the 107 accounts with over 20 million XRP, etc) the attacker would need to know my r-address in order to target my account So I have two options to protect against quantum attacks until quantum resistant algorithms are implemented on the XRPL:

1. Create a new XRPL account and move my assets to the new account then leave it alone. As long as I do not perform any transactions on my new account, it will not be vulnerable to quantum attacks.
2. Create a new XRPL account and re-key my existing account to point to my new account then disable the master key on my existing account and leave it alone, As long as I do not perform any transactions on the new re-keyed account, it will not be vulnerable to quantum attacks.

The current encryption methods were not meant to remain secure indefinitely. Even when quantum cryptography arrives, it will only replace current cryptographic methods until the next class of computers arrive. (Which will probably be ones that can overcome the Church-Turning thesis) At that time quantum cryptography will become obsolete. After that, I’m sure another system based on a yet-to-be-determined branch of physics will make all other forms of cryptography useless. The cycle never ends.
