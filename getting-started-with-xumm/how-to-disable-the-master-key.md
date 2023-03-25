---
description: Disabling the Master key on an XRPL account
cover: ../.gitbook/assets/Large rock with Lock.jpg
coverY: 168
---

# How to disable the Master key

{% hint style="info" %}
This article is under construction...
{% endhint %}

## Make sure you have configured a Regular Key Pair <a href="#h_d534a6dc19" id="h_d534a6dc19"></a>

Before you can disable the master key of an XRP Ledger account, you must have configured a regular key pair pointing another XRPL account. For example, if you have a Primary account, and you wish to disable the master key for it, you must have configured a Signing account in order to proceed.

This article explains how to do this:

<table data-view="cards"><thead><tr><th align="center"></th><th data-hidden></th><th data-hidden></th><th data-hidden data-card-target data-type="content-ref"></th><th data-hidden data-card-cover data-type="files"></th></tr></thead><tbody><tr><td align="center">How to rekey your account</td><td></td><td></td><td><a href="how-to-disable-the-master-key.md">how-to-disable-the-master-key.md</a></td><td><a href="../.gitbook/assets/Large rock with Key.jpg">Large rock with Key.jpg</a></td></tr></tbody></table>

You should have already tested that the regular keys works properly by doing several transactions to confirm that you can sign transactions on the Primary account with the regular key account (aka. SIgning account)&#x20;

Once you are sure it works, you can procced to the next step..



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
