---
description: How to rekey a Xahau account
---

# How to Rekey a Xahau account

### Concept and Implementation

The XRP Ledger allows an account to authorize a secondary key pair, called a [_regular key pair_](https://xrpl.org/cryptographic-keys.html), to sign transactions on  behalf of another account.&#x20;

It is often used to protect an account by securing the master key and using the regular key in its place. This has multiple advantages;

1. The primary account is safer because the master key does not need to be generally available
2. The regular key account does not need to be activated so has no value in and of itself
3. The regular key can be removed or swapped out as needed

### Example

A good example of how this works would be to look at the recommended configuration of a pair of [Xaman (Tangem) cards](../xumm-tangem-cards/xumm-tangem-cards.md).

In this case, you have a Primary account on one card and you have a Signing account on another card.

When you run the [Tangem Backup xApp](/broken/pages/Ypotp0jrufYxwEF2ciFO), it creates a "link" between the two accounts which is called a 'regular key pair'. It connects the Primary account to the Signing account which allows you to sign transactions on the Primary account **using the Signing account**.

The following steps explain how to manually configure a regular key pair between two Xahau accounts.

### Step 1: Make sure you have a Primary account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

The Primary account must be imported into Xaman (formerly Xumm) with **Full access**. (You must be able to sign transactions on this account.)

This is the account that will have your XAH.

### Step 2: Make sure you have a Signing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

The Signing account must be imported into Xaman with **Full access**. (You must be able to sign transactions on this account.)

This account does not need to contain XAH and does not even need to be activated. As long as you have full access to the account, it can be used to sign transactions on the Primary account.

### Step 3: How to set a Regular Key Pair <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Once you have completed the following steps, you will be able to sign transactions on your Primary account using **both** your Primary account **and** your Signing account.

1\) Launch Xaman and switch networks to ensure you are connected to Xahau.<br>

<figure><img src="../.gitbook/assets/Xahau - Switch Networks.png" alt=""><figcaption></figcaption></figure>

2\) Switch accounts to your Signing account.

<figure><img src="../.gitbook/assets/Xahau - Rekey article - 1.png" alt=""><figcaption></figcaption></figure>

3\) Press the **Request** button then press the **Copy** button.

<figure><img src="../.gitbook/assets/Xahau - Rekey article - 2.png" alt=""><figcaption></figcaption></figure>

4\) Switch accounts to your **Primary** account and go to [**Xahau Services**](https://xahau.services/)**.**

5\) Press the ![](https://help.xaman.app/~gitbook/image?url=https%3A%2F%2F3221812686-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FMiHAzvIPISVuuzt0AeOR%252Fuploads%252FpWxtCQGbLekH3czjbro6%252Fimage.png%3Falt%3Dmedia%26token%3Db8d31395-8d20-473f-8741-bbaf668d71f4\&width=300\&dpr=4\&quality=100\&sign=ada60351\&sv=1) button then sign in.

6\) On the Xahau Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/Xahau - Rekey article - 3.png" alt=""><figcaption></figcaption></figure>

7\) In the field below, paste the r-address for the Signing account, then press the **Send Set Regular Key to Xaman** button.

<figure><img src="../.gitbook/assets/Xahau - Rekey article - 4.png" alt=""><figcaption></figcaption></figure>

8\) Sign the transaction in Xaman and you're all done!

