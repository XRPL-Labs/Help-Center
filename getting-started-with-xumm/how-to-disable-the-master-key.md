---
description: Disabling the Master key on an XRPL account
cover: ../.gitbook/assets/Large rock with Lock.jpg
coverY: 168
---

# How to disable the Master key

### Why disable the Master key?

There are two main reasons why you would want to disable the Master key for an XRPL account:

* Your account has been compromised
* You want to configure your account so that you can only sign and submit transactions using a regular keyed account.&#x20;

### Before you get started

You should confirm that you have the correct account secret for your account.

\<Enter link to article - How to check your account secret>

Once you have done this, you should be aware of the following before you proceed:

1\) To disable the master key pair, **you must use the master key pair.**&#x20;

2\) Your account must have at least one method of authorizing transactions other than the master key pair. e.g. - assign a regular key

3\) Once the Master key has been disabled, you will not be able to use it to re-enable your Master key. It can only be re-enabled using the assigned regular key account.

### Make sure you configure a Regular key account

The XRP Ledger will not let you disable the Master key unless there is an alternate way to sign and submit transactions. This article explains how to do this by adding a regular key to your account.

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">How to rekey your account</td><td></td><td></td><td><a href="how-to-disable-the-master-key.md">how-to-disable-the-master-key.md</a></td><td><a href="../.gitbook/assets/Large rock with Key.jpg">Large rock with Key.jpg</a></td></tr></tbody></table>

&#x20;

### Disabling your Master key

{% hint style="danger" %}
You will not be able to access your XRP Ledger account using your Master key after performing this procedure. Ony your regular key account will be able to sign and submit  transactions to the XRPL.
{% endhint %}

1\) Go to [XRPL.services](https://xrpl.services/)

2\) Press the ![](<../.gitbook/assets/image (1) (5).png>) button then press **Open in Xumm App** and sign in with the account the you would like to disable your Master key on.

<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>

5\) On the XRP Ledger Services page, select **Account Set.**

<figure><img src="../.gitbook/assets/XRPL Services - Dsiable Master Key - 1.png" alt=""><figcaption></figcaption></figure>

6\) Choose **Disable Master Key**, then press the **Send Account Settings to Xumm** button.

<figure><img src="../.gitbook/assets/XRPL Services - Dsiable Master Key - 2.png" alt=""><figcaption></figcaption></figure>

7\) Sign the transaction in Xumm and you're all done!&#x20;





&#x20;

**Notes**

We understand that you might have additional questions regarding this topic so you are welcome to contact us any time via the [<mark style="color:blue;">**Xumm Support xApp**</mark>](https://xumm.app/detect/xapp:xumm.support?ref=helpcenter) in Xumm or you can simply scan this QR code with Xumm and be directed there automatically.

<figure><img src="../.gitbook/assets/Support banner Xumm.png" alt=""><figcaption></figcaption></figure>
