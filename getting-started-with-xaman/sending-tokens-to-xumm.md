---
description: How to send tokens to your XRP Ledger account managed by Xaman
---

# Sending tokens to Xaman

**Introduction**

If you are new to Xaman (formerly Xumm), it can be a little bit confusing to understand what all the buttons and features do. Trust us when we say, **it does get easier** after a little bit of practice! 😉

This article talks about how to send funds using Xaman.

### **Background**

The first thing to know is that all tokens issued on the XRP Ledger use the same r-address to send and receive as XRP does.&#x20;

For example, if you want send XRP to your account, you would send it to your r-address. In Xaman you can find your r-address here:

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Of course, your r-address will be different than our r-address. Our account is a [Vanity r-address](../xumm-pro-beta/features-of-pro/vanity-addresses.md).
{% endhint %}

The second thing to know as that you **can not receive tokens** unless you have configured a Trust Line for those tokens.

In our case, we have one Trust Line configured in our account:

* XAH (Xahau)

You can see it here:

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

The final thing, which might be the most important thing, is that you **never send tokens to the tokens issuing account**. If you do that, you will destroy them. (More on this later.)

### Putting it all together

Let's go through an example of how it works.

We want to receive a token in our account. In this case we want to receive Euro tokens (EUR) issued by GateHub. The problem is that we do not have a Trust Line configured in our account for EUR so we can not receive them, so we need to create one.

Here's how to do that:

{% content-ref url="how-to-create-a-trust-line.md" %}
[how-to-create-a-trust-line.md](how-to-create-a-trust-line.md)
{% endcontent-ref %}

Now we have two Trust Lines configured. Here is how Xaman looks after we create the EUR Trust Line.

<figure><img src="../.gitbook/assets/Trust lines on main screen.png" alt=""><figcaption></figcaption></figure>

### **Each Trust Line has its own r-address…**





Now, in our case, let’s say we had another XRPL account and we wanted to send tokens to it. For example, CasinoCoin (CSC), we would send the tokens the same r-address as we would if we were sending XRP. (In this case, **rstargateUoNLmD683...**)

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
