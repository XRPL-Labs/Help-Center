---
description: Set / Add a regular key pai to your XRPL account
---

# How to rekey your account

The XRP Ledger allows an account to authorize a secondary key pair, called a [_regular key pair_](https://xrpl.org/cryptographic-keys.html), to sign future transactions.&#x20;

A regular key pair is often used to protect your account, which can sign transactions for your account instead of using the master key.

### Concept and implementation

A good example of how this works would be to look at the recommended configuration of a pair of [Xumm (Tangem) cards](../xumm-tangem-cards/xumm-tangem-cards.md).

In this case, you have a Primary account on one card and you have a Signing account on another card. When you run the [Tangem Backup xApp](../all-about-xapps/xumm-xapps/tangem-backup.md), it creates a "link" between the two accounts which is called a regular key pair. It connects the Primary account to the Signing account which allows you to sign transactions on the Primary account **using the Signing account**.

The following steps explain how to manually configure a regular key pair between two XRP Ledger accounts.

### Step 1: Make sure you have a Primary account <a href="#h_46e6d7f417" id="h_46e6d7f417"></a>

The Primary account must be imported into Xumm with **Full access**. (You must be able to sign transactions on this account.)

This is the account that will have your XRP, your Trust Lines, Escrows, DEX transactions, etc.

If you are new to Xumm and don't have an XRP Ledger account yet, you can create one by following the instructions in this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">How to Create an XRP Ledger account</td><td></td><td></td><td><a href="../.gitbook/assets/Creating in forest.png">Creating in forest.png</a></td><td><a href="your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md">how-to-create-an-xrpl-account.md</a></td></tr></tbody></table>

### Step 2: Make sure you have a Signing account <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

The Signing account must be imported into Xumm with **Full access**. (You must be able to sign transactions on this account.)

This account does not need to contain XRP and does not even need to be activated. As long as you have full access to the account and it is imported with Full access, it can be used to sign transactions on the Primary account.

If you don't have signing account yet, you can create one by following the instructions in this article:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-cover data-type="files"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center">How to Create an XRP Ledger account</td><td></td><td></td><td><a href="../.gitbook/assets/Creating in forest.png">Creating in forest.png</a></td><td><a href="your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md">how-to-create-an-xrpl-account.md</a></td></tr></tbody></table>



### Step 3: How to set a Regular Key Pair <a href="#h_daeec8d8c2" id="h_daeec8d8c2"></a>

Once you have completed the following steps, you will be able to sign transactions on your Primary account using **both** your Primary account **and** your Signing account.

1\) Launch Xumm and switch accounts to your Signing account.

<figure><img src="../.gitbook/assets/regular keys -2 (1).png" alt=""><figcaption></figcaption></figure>

2\) Press the **Request** button then press the **Copy** button.

<figure><img src="../.gitbook/assets/regular keys -3.png" alt=""><figcaption></figcaption></figure>

3\) Now, switch accounts to your **Primary** account in Xumm and press <mark style="color:blue;">**here**</mark> to go to [**XRP Ledger Services**](https://xrpl.services/)**.**

4\)&#x20;



<figure><img src="../.gitbook/assets/Sign into Xumm.png" alt=""><figcaption></figcaption></figure>



On the XRP Ledger Services page, select **Set Regular Key**

<figure><img src="../.gitbook/assets/XRPL Services - Reg Key - 1.png" alt=""><figcaption></figcaption></figure>

&#x20;

Be sure when submitting your regular key to your account to use the right account for this. After scanning the QR code, signing & submitting you should see this in the Xumm app:

![](https://downloads.intercomcdn.com/i/o/231461350/c510dbed9f8364587b4bdd83/Done+submitting.png)

Now you can sign using your newly generated account and is now a regular key. Now under your new account there is a button like this.

![](https://downloads.intercomcdn.com/i/o/229411704/3f1926600a0a39af91f2feaf/IMG\_34FE7BFE2A75-1.jpeg)

The next step is a verification if the account is properly set up and if you can sign using your newly generated key pair.

&#x20;

If you configured a "Regular Key" as a [**back up** account](https://support.xumm.app/hc/en-us/articles/360019049920), you should **stop** following this tutorial **right here**.

If you want to **re-key** your account because you **believe** your [**keys** may be **compromised**](https://support.xumm.app/hc/en-us/articles/360020672759), please **continue** following this tutorial.

&#x20;

## Step 3: Verify the Regular Key Pair <a href="#h_d534a6dc19" id="h_d534a6dc19"></a>

A very important step especially before disabling your master key on the account. Check if the regular key pair works. But you don't have to disable your master key that is up to you.

&#x20;

To check if the account can sign using your new key you can now change your account access level to read only.

&#x20;

You can change this in settings → accounts → click on the account you want your master key to be removed from the app. Now you should see this screen and can change the access level to read only.

![](https://downloads.intercomcdn.com/i/o/231463605/a5930079a15c05eebb16892e/IMG\_6C951E5DB3BB-1.jpg)

For the actual check use the tools tab on the [xrpl.services](https://xumm.community/) website and go to Raw JSON Transactions. Select the account set template and delete everything except the first two lines. The important part is that the account is correctly set, it should be the account which you just changed the access level of to read only. Just like this.

&#x20;

![](https://downloads.intercomcdn.com/i/o/229435940/78e1ad65f8be3d3a300e7249/Schermafbeelding+2020-07-22+om+16.20.39.png)

Now you can sign and submit the transaction. If it shows that it was successful you're set to continue to disable your master key. Or to leave it as is.

&#x20;

![](https://downloads.intercomcdn.com/i/o/231464089/fb48afa992e64a07d984e30e/success+acc+set+tx.png)

## Optional Step 4: Disable your master key ⚠️ <a href="#h_a7c3b8f5aa" id="h_a7c3b8f5aa"></a>

This is an additional step which will disable your master key.

⚠️ Warning ⚠️: You will not be able to access the XRP account using your master key hereafter. Only your regular key pair will be able to sign.

&#x20;

The only way to disable your master key is to import your master key again, just by upgrading the account from read only to full access read/write.

![](https://downloads.intercomcdn.com/i/o/231464654/28341805c635e28b2aae300a/Change+access.png)

&#x20;

After this step go to the [xrpl.services](https://xumm.community/) for the last step.

Under the option for Account Set there is a checkbox Disable Master Key, check it and then you are good to go to sign that transaction using the account you have just re-keyed and you want to delete the account with. It will look like this:

![](https://downloads.intercomcdn.com/i/o/231263470/1f1aa4814561f48863ee2c1d/Schermafbeelding+2020-07-28+om+20.54.19.png)

When you have signed the transaction your account is now fully re-keyed and is not able to sign using its own master key anymore.

If, for whatever reason, your regular key gets compromised and the master key is not, you can set a new regular key using a tool like [xrpl.services](https://xumm.community/) to regain control of your account.

&#x20;If you already have a regular key pair with an XRP account you can just import your XRP account as a read-only account and the regular key pair as a full read/write account and you're set to go!

&#x20;&#x20;

Fully sign now with the regular key pair that you've just created 🎉