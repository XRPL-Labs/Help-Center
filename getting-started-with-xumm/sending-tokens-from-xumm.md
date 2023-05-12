---
description: How to send tokens from your XRP Ledger account managed by Xumm
---

# Sending tokens from Xumm

Sending tokens from Xumm is a very easy process. In fact, sending tokens is one if its primary functions! Here is how it's done...

### **Step 1**

From the main screen in Xumm, press the **Send** button.

<figure><img src="../.gitbook/assets/Send button.png" alt=""><figcaption></figcaption></figure>

On the following screen, you will see the option to enter the **amount** you would like to send.

(You can also change the account you would like to send the tokens **from** and you can change the **type** of token you would like to send.)

<figure><img src="../.gitbook/assets/Send screen - 2.png" alt=""><figcaption></figcaption></figure>

In our case, we are going to send 1 XRP from our account.

Press the **Next** button to continue.

### **Step 2**

In this screen you can enter the **recipient's** account that you are sending your tokens to.

<figure><img src="../.gitbook/assets/Recipient screen.png" alt=""><figcaption></figcaption></figure>

Keep in mind, there are two types of accounts on the XRPL.

* **Self custodial** accounts - You are solely responsible for managing your private keys.
* **Custodial** accounts - A company is responsible for managing the private keys to their account. (Usually a crypto exchange.) You are assigned an account number with the exchange called a destination tag.

Both types of accounts will have an r-address but a custodial account will also require a destination tag. (More about destination tags later.)

Press **Next** after you have entered/selected the correct destination r-address.

### **Step 3**

Finally we reach the **Summary** screen. Here you can review your transaction to make sure it is correct.

<figure><img src="../.gitbook/assets/Summary.png" alt=""><figcaption></figcaption></figure>

If you are sending to a self-custodial account, you can simply **Slide to send** and your transaction will be sent to the XRP Ledger to process.

However, if you are sending to a **custodial** account, (ie. an exchange account) this where you would enter your **destination tag**.



<figure><img src="../.gitbook/assets/Summary + DT.png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Remember, non-custodial accounts, like the ones managed with Xumm **do not** require destination tags. Only **custodial** accounts require them.
{% endhint %}

#### **A little bit more about destination tags**

You may have noticed that most crypto exchanges have **one** receiving r-address for **all** of their XRP customers? Have you ever wondered how thousands of customers can use just one XRP account?&#x20;

When you create an account with a crypto exchange, they issue you a customer account on their internal database. They also create a destination tag which points to your new customer account and they provide you with **their** XRP Ledger account which you can send and receive XRP. You do not own their XRPL account. They have complete control over it. Since thousands of customers are sending funds to and from the same XRPL account, the only way they can tell which funds belong to which customer is by the destination tag included in each transaction. &#x20;

If you would like to learn a bit more about destination tags, check out this video:

{% embed url="https://www.youtube.com/watch?index=5&list=PL7cEYW-Kob0p9EcJexpZRc-vY93vnpp_l&v=gAWnIw4gzW8" %}

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
