---
description: How to send tokens to your XRP Ledger account managed by Xaman
---

# Sending tokens to Xaman

### **Introduction**

If you are new to Xaman, it can be a little bit confusing to understand what all the buttons and features do. Trust us when we say, **it does get easier** after a little bit of practice! 😉

This article talks about how to send tokens to Xaman.

### **First things first...**

All tokens issued on the XRP Ledger should be sent to your r-address. For example, if you want send XRP to your account, you would send it to your r-address. which you can find here:

<figure><img src="../.gitbook/assets/r-address.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Of course, your r-address will be different than our r-address. Our account is a [Vanity r-address](../xaman-pro/features-of-pro/vanity-addresses.md).
{% endhint %}

Similarly, if you want to send a token to your account, your would send it **to your r-address**.



The second thing to know as that you **can not receive tokens** unless you have configured a Trust Line for those tokens.

In our case, we have several Trust Lines configured in our account:

* XAH (Xahau)
* USDC
* Euros (issued by GateHub)
* RLUSD

This means that we can receive and hold these tokens in our account.

### Putting it together

Let's go through an example of how it works.

We want to receive a token in our account. (In this case, **rstargateUoNLmD6837twth...**)

We can receive XAH, USDC, Euros (issued by GateHub) or RLUSD tokens because we have Trust Lines configured for those tokens.

Our friend has their own XRP Ledger account.

<figure><img src="../.gitbook/assets/r-address - Atlantis (1).png" alt=""><figcaption></figcaption></figure>

We can see that they have XAH tokens (issued by GateHub) just like we do, and they have Euro tokens (issued by GateHub) like us.

They are going to send us 10 Euro tokens.

First, our friend taps the '**Send**' button.

<figure><img src="../.gitbook/assets/r-address - Atlantis -1.png" alt=""><figcaption></figcaption></figure>

then they press the **down arrow** in the 'Token' arrow section and select **Euro** (issued by GateHub), then they enter '10' in the 'Amount' field, then press the '**Next**' button.

<figure><img src="../.gitbook/assets/r-address - Atlantis -2.png" alt=""><figcaption></figcaption></figure>

Now it's time for our friend to enter our r-address since we will be the recipient of the tokens. After our complete r-address has been entered, they will press the '**Next**' button.

<figure><img src="../.gitbook/assets/r-address - Atlantis -3.png" alt=""><figcaption></figcaption></figure>



Finally, we have the Summary screen. Our friend will review the transaction, then slide the 'Slide to send' button to complete the transaction.





&#x20;

in our case, let’s say we had another XRPL account and we wanted to send tokens to it. For example, CasinoCoin (CSC), we would send the tokens the same r-address as we would if we were sending XRP. (In this case, **rstargateUoNLmD683...**)

…and we wanted to send a different token to our account, maybe, Sologenic (SOLO) or Coreum (CORE) or Elysium (ELS), we would still use the our same r-address. (Again, in this case, **rstargateUoNLmD683...**)

Keep in mind, in all of the above examples, the relevant Trust Line would need to be setup before the token will show as an asset in the destination account.

For more information how to create a Trust Line, check out this article:

{% content-ref url="how-to-create-a-trust-line.md" %}
[how-to-create-a-trust-line.md](how-to-create-a-trust-line.md)
{% endcontent-ref %}

### **Each Trust Line has its own r-address…**

In order to receive and hold a particular XRP Ledger token, (there are over 8200 of them), you need to create a Trust Line to their project.

Let’s look at the CasinoCoin (CSC) project for example.

The CasinoCoin project issued the CSC token back in March of 2021 from this r-address:

**rCSCManTZ8ME9EoLrSHHYKW8PPwWMgkwr**

If you would like to hold CSC tokens in your account, you will need to create a Trust Line to their issuing account.&#x20;

{% hint style="warning" %}
When you create a Trust Line, you are basically saying that you have researched their project and are satisfied that they are a trustworthy company.
{% endhint %}

For more information about Trust Lines and how they work, check out this link:

* [All about Trust Lines](https://xrpl.org/trust-lines-and-issuing.html#trust-lines-and-issuing)

{% hint style="danger" %}
One final note, you should never send tokens back to an issuing account. Doing this will destroy them. If you are unsure about this, please contact us to discuss.
{% endhint %}

The problem is that we do not have a Trust Line configured in our account for EUR so we can not receive them. We need to create one.

Here's how to do that:

{% content-ref url="how-to-create-a-trust-line.md" %}
[how-to-create-a-trust-line.md](how-to-create-a-trust-line.md)
{% endcontent-ref %}

After we follow the instructions in the above article, we now have two Trust Lines configured. Here is how Xaman looks after we create the EUR Trust Line.
