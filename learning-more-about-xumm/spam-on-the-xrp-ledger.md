---
description: Understanding SPAM
---

# Spam on the XRP Ledger

### **What is spam?**

A spam transaction is any unwanted or unsolicited transaction that gets sent out in bulk across the XRP Ledger. Here is how spam transactions look in Xaman:

<figure><img src="../.gitbook/assets/Spam - 1 (1).png" alt=""><figcaption></figcaption></figure>

### **Is spam dangerous?**

The spam transactions themselves are not dangerous. In most cases, spam transaction are simply a marketing ploy to try to get you to participate in their project, but in other cases, they are trying to scam you.&#x20;

For example:

<figure><img src="../.gitbook/assets/Scam transaction.png" alt=""><figcaption></figcaption></figure>

If you were to follow the instructions in the Memo field, you would certainly be scammed.

### **Can they access my account in any way?**

Absolutely not. No one can access your XRPL account unless they know your account secret. (Secret numbers / Family seed / Mnemonic) As long as you keep your account secret safe and secure, your funds are safe. The only way someone can access your XRPL account is if you give them your account secret. See this article for more information:

* [How secure is Xaman?](../security-and-xumm/all-about-security/how-secure-is-xumm.md)

### **Do these spam transactions cost me XRP?**

No. Each transaction costs the **sender** to send them. The sender pays the XRPL transaction fees, **not** you.

### **What can I do about spam on the XRPL?**

Begininng in Xaman v3.3.1, we have included a way to block out spam transactions from the Events list.



Some people who receive spam, take it upon themselves to contact the scam token issuers and explain (often in very strong language) spamming a public network is… unwanted and undesirable.

Others take to social media to condemn the token issuers and warn others not to participate.

Most people simply ignore the transactions. We advise you to do this as well.



### **Can I delete the spam transactions from my account?**

Nobody can delete a transaction from the XRP Ledger or from Xaman (formerly Xumm). If it exists on the XRPL, Xaman will display it.

### **What can I do about spam on the XRPL?**

Some people who receive spam, take it upon themselves to contact the scam token issuers and explain (often in very strong language) spamming a public network is… unwanted and undesirable.

Others take to social media to condemn the token issuers and warn others not to participate.

Most people simply ignore the transactions. We advise you to do this as well.

###

### **Should I return the tokens to them?**

That is completely up to you. These spammers **want** to get some sort of reply from you. That way they know you are reading their messages. Once you reply, it is possible that they will send you **targeted** messages. There is no telling what their intentions are. We recommend that you ignore them.

### **If I return it will I be charged a transaction fee?**

Yes. The XRPL automatically charges transaction fees in order to process transactions. It **will cost you XRP** to send the tokens back to them.

### **I clicked the transaction to view it, am I in any danger?**

No. Reviewing a transaction on the XRPL is not dangerous. The only way someone can access your XRPL account is if they get access to your account secret. See this article for more information:

* [How secure is Xumm?](../security-and-xumm/all-about-security/how-secure-is-xumm.md)

### **I don't even know them! How did they get my r-address? I’ve been very careful who I’ve interacted with in the XRP community…**

The XRP Ledger is a public blockchain. There are many ways to get a list of random r-addresses. If you have created a Trust Line or sent funds to/from a crypto exchange, or participated in an airdrop, or even if you activated an account, your r-address can be filtered and obtained.&#x20;

Here is an example:

<figure><img src="../.gitbook/assets/scam transaction1.png" alt=""><figcaption></figcaption></figure>

In this case, a person has just activated their account and suddenly they receive a spam transaction advertising a website.

Legitimate projects do not send unsolicited transactions across public networks.

There is currently no way of preventing this from happening on the XRP Ledger.

### **How does Xaman handle spam?**

We have numerous ways of identifying spam on the XRPL. When we find accounts that appear to be sending spam, we analyze the history of the account, immediately suppress the memo field and add a notification indicating the transaction may be dangerous. As well, for our [**Xaman Pro**](https://support.xumm.app/hc/en-us/articles/6138022550418) users, the push notifications are suppressed so you are not notified when the spam transactions arrives in your account.

### **Is there any solution to this problem?**

Actually there is. It is called the Xahau network and you can easily interact with the Xahau network using Xaman.

The Xahau network is an XRP Ledger protocol side chain that has all of the same features as the XRP Ledger but it includes additional features like a spam filter.  Once the Spam filter is installed on your account, spam transactions are stopped before they even get to your account.

### **How it works**

Some people have figured out that they can combine the low fees of the XRPL with the Memo field to send low value transactions to a large number of accounts.

By doing this, they can get their “message” out to thousands of people at a very low cost.

### **How it looks in Xaman**

If you look in the Events log in Xaman (formerly Xumm), you will see something like this:

Notice the red triangle with the exclamation mark. This indicates a spam transaction.
