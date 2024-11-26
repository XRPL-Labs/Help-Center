---
description: I can not find my Secret numbers / Family seed / Mnemonic
---

# I've lost my account secret!

### What is an account secret?

Have you ever heard the saying,&#x20;

_"Not your keys, not your crypto"_

On the XRP Ledger, an account secret is the private key to your XRPL account. It is how you get full access your XRPL account.

An account secret comes in three main forms:

* **Secret numbers** - If you created your XRP Ledger account using Xaman (formerly Xumm), you would have received a set of secret numbers consisting of 8 rows, (A-H), each with 6 digits.&#x20;
*   **Family Seed** - A 29 character string of numbers and letters starting with the letter "s".\


    A typical family seed looks something like this:

    &#x20;          sn3e4r5t6ygtfr5tgy6tr4edse3wq
* **Mnemonic** - A set of 12, 16 or 24 words chosen from the [BIP 39 list](https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt).

Xaman is fully compatible with all three account secret formats.

### Why is an account secret important?

The XRP Ledger is a decentralized network. It does not have any administrator functions. It does not have any 'back doors' which allows access to an account. There is no 'secret way' to access an XRPL account. They **only** way to get full  access an XRPL account is with the correct account secret. An account secret is important because it is the only thing that will allow you to get full access to an XRPL account.

### Can I view an account secret in Xaman?

No.&#x20;

Xaman does not have the ability to display or recover an account secret. It was designed specifically to **NOT** display them just in case your phone was ever stolen or compromised.

You can read more about this here:

{% content-ref url="can-i-view-export-my-account-secret.md" %}
[can-i-view-export-my-account-secret.md](can-i-view-export-my-account-secret.md)
{% endcontent-ref %}

### I can't find my account secret. What are my options?

#### Option 1 - You still have existing access on your device

Are you able to access your XRPL account on your mobile device **and** you can you still sign transactions on your account?&#x20;

If so,  you can create a new XRP Ledger account using Xaman then move your assets over to the new account. Here's how to do this:

1\) Press **Settings** then **Accounts**.

2\) Choose **+ Add account** then **Create a new account**

3\) Once you have completed the steps (and written down your new secret numbers), you can activate it with 10 XRP, then start moving your assets over to your new account using the **Send** feature on the main page of Xaman.

Note: You will need to create Trust Lines for any tokens you might have and arrange to move any NFTs with your NFT platform.

By creating a new account, you will get a new set of secret numbers which you can use to access your account on your phone.&#x20;

#### Option 2 - You have existing access on another device

Do you have an old phone or mobile device which still has signing access to your account. Does anyone else have signing access to your account? (Family member) If so, you can run through the steps in Option 1 to create a new account.

#### Option 3 - You created your XRP Ledger account using another wallet or platform

If you used another wallet to create your XRP Ledger account, it is possible that they might have a recovery option or utility to recover your account secret. You can try contacting them and see if they have any options for accessing your account secret.

#### Option 4 - Your account was created during the Casino Coin swap.

If your account was created during the Casino Coin swap, there is a special set of instructions for recovering an account. Check out this article for more information:

{% embed url="https://eminence.freshdesk.com/support/solutions/articles/80000965171-how-to-recover-a-swapped-casinocoin-xumm-account" %}

**Option 5 - Someone else knows your account secret.**

Have you shared your account secret with anyone? (Family member?) Was anyone else with you when you created your XRPL account? If so, do they have a copy of your account secret? If they do, you can use it to access your account.

## Frequently asked questions

### I can prove that I own the account. I went through the KYC process. I can prove I activated it. I can provide ID that I own it. Doesn't that make a difference?

The XRP Ledger is a decentralized network. There is no central authority for you to prove your identity to. The KYC process has nothing to do with the private keys to your XRP Ledger account. When you go through the KYC process it does not 'link' your personal information to your private keys nor does it grant you access to your XRPL account. The only way to access an XRP Ledger account is if you know the private keys (account secret) for it.

### If I have a bank account or an account with a crypto exchange, they can access my funds, why can't Xaman access my funds for me?

Banks and crypto exchanges offer 'custodial' accounts.&#x20;

For example, if you were to open an account with a crypto exchange, you would go through the KYC process and they would create a record in their **internal database** containing all of your personal information. They would then create an account on their internal systems and assign you a password to access it. If you ever lost your password for your account with them, they would go into their company database and simply change it for you. They can do that because they created your account. They control your account. They control your personal information. They have full custody of your funds and have complete control over them.

Self custody accounts on the XRP Ledger do not work that way.

When you create an XRPL account, you do not have to go through KYC. You do not have to provide personal information about yourself. You are interacting directly with the XRP Ledger. There are no internal databases. No records of your personal information. No centralized authority. No 'middle men'. It is just you and the XRP Ledger. Xaman is an application which allows you to interact with the XRP Ledger by managing your account secret. It does not have access to your account.

### I already have my account secret but it accesses another account!

If you import your account secret into Xaman and you get a **different r-address**, you actually imported another XRPL account that has not been activated, and does not contain your balance and tokens.&#x20;

The only way to get full access to your account, is by importing the **correct** account secret.

Importing the correct account secret into Xaman will always result in the same r-address, with balance and tokens in place.

### ...but I'm sure my account secret is correct...

Xaman is just an interface to the XRP Ledger.&#x20;

When you enter an account secret into Xaman, it provides you access to the XRPL account that the account secret belongs to.  Xaman can only access the account that the account secret belongs to.&#x20;

Imagine a big apartment building with about 340 undecillion apartments in it. Each apartment has a lock on the door and there is only one key that opens that lock. When you create an XRP Ledger account, you basically get the one and only key to one of those apartments. There are many other keys that fit other apartments, but your key is the only one that fits your apartment. When you enter your account secret into Xaman, it searches through all 340 undecillion apartments and finds the only apartment which your key opens. Your key will not open any other apartments. It will only open one apartment. Xaman can not open another apartment with your key. It can only open the apartment that the key belongs to.

Consider the possibility that there is another account secret for your account.



