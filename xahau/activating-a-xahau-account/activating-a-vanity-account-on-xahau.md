---
description: How to activate a Vanity account on Xahau
---

# Activating a Vanity Account on Xahau

### Background

You might remember when you purchased your vanity account, we configured a regular key account to sign for your vanity address then we disabled the master keys for it.&#x20;

This meant that in order to sign transactions on your vanity address, you needed to have your regular key account imported into Xaman (formerly Xumm) with full access and you had to have your vanity address imported into Xaman in read only mode.

In Xaman, it would look something like this:

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You may have noticed that the Vanity Account says, 'Full access" rather than 'Read only". That is because Xaman recognizes that the regular key account is present and in 'Full access" so it updates the Vanity account from 'Read only' to 'Full access'.
{% endhint %}

### How it works

This processes will activate your vanity account on Xahau, activate it with 2 XAH and authorize Xaman to use the regular key account to sign for your vanity account on Xahau. It does this using an xApp called **Xahau Import** to create a _Setregularkey_ transaction on the XRP Ledger, then create an _Import_ transaction on the Xahau network. Signing both of these two transactions will duplicate your vanity account on Xahau, activate it with 2 XAH and authorize Xaman to use the regular key account to sign for your vanity account.&#x20;

### Getting started...&#x20;

The following process has two requirements:

* Your vanity account must imported into Xaman.
* The regular key account (for your vanity account) must be imported into Xaman with full access.

As long as both of these requirements are met, you can follow these instructions.

1\) Launch Xaman and switch to your vanity account.

<figure><img src="../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

2\) Tap the following link, then scan the QR with Xaman to get the [Xahau Import xApp](https://xumm.app/detect/xapp:nixer.xahauimport).

{% embed url="https://xumm.app/detect/xapp:nixer.xahauimport" %}

3\) Launch the Xahau Import xApp. You must accept the _Terms and Conditions_ and the _Privacy Policy_ before you can continue. Press the **Next** button when ready.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4\) Make sure your vanity account address is displayed. If not, press the _Change Account_ button and select your vanity account from the list. When ready, press the **Next** button to continue.

<figure><img src="../../.gitbook/assets/image (72).png" alt=""><figcaption></figcaption></figure>

5\) The xApp should detect that you have a Regular Key set for your vanity account. Press the **Excute SetRegularkey** button.

<figure><img src="../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

6\) Slide to accept.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

10\) Press the <img src="../../.gitbook/assets/image (5) (1).png" alt="" data-size="line">button. (Also known as the _Network Switch_ button.)

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

11\) Tap the **Xahau** network.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

10\) Press the **Import Account** button.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

11\) You have to sign this transaction with your regular key account.

<figure><img src="../../.gitbook/assets/image (73).png" alt=""><figcaption></figcaption></figure>

Press the **Close** button...and you're done! Congratulations!

### How to check if it worked

If it worked, you should see your **activated** account on the Xahau network.

<figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

As well, when you check your sign account, it should look like this:

<figure><img src="../../.gitbook/assets/image (75).png" alt=""><figcaption></figcaption></figure>

If it didn't work, you would see a screen like this for your vanity account.

<figure><img src="../../.gitbook/assets/image (76).png" alt=""><figcaption></figcaption></figure>

and this for your signing account.

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

