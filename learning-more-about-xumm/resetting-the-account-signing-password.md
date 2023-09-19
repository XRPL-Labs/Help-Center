---
description: How to reset the signing password on your account
---

# Resetting the (account) signing password

{% hint style="danger" %}
This article assumes that you have the account secret for your XRP Ledger account. You **must** know the account secret in order to proceed. You will not be able to access your XRPL account without it.
{% endhint %}

### **Background**

When Xumm is installed, you are presented with the option to select Standard security or Extra security.

<figure><img src="../.gitbook/assets/Install - Extra Security screen - 1.png" alt=""><figcaption></figcaption></figure>

The following table explains the differences.

| Option                                              | Explanation                                                                                                                                                         |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](<../.gitbook/assets/image (1) (2) (3).png>)     | Standard security is a great option your daily spending account. You can sign with your 6 digit passcode or enable biometrics and sign with your face/finger print. |
| ![](<../.gitbook/assets/image (3) (1) (2) (2).png>) | Extra security allows you to enter a separate signing password. This is the best option for your long term storage account.                                         |



If you selected **Extra security** you would have created a separate signing password. If you have forgotten that signing password, if it is not working, or you would like to change it, here are the instructions on how to do this.

### Step 1 - Remove the account from Xumm

1. Launch Xumm and press **Settings** -> **Accounts** -> then press the **Edit** button beside the account to be removed. (Note: This does not delete your account from the XRP Ledger, it simply removes your account from Xumm. )
2. Select **Remove from Xumm** then **Yes, I’m Sure**’ on the warning screen.

{% hint style="warning" %}
Note: This assumes that you have the passcode to remove the account. If you do not have the passcode (or your passcode does not work), you are going to need **uninstall** Xumm, then **reinstall** in Xumm then move on to Step 2 below.
{% endhint %}

### Step 2 - Import your account secret back into Xumm

1. Your account secret will come in the the form of a set of secret numbers / Family seed /Mnemonic. This article will guide you through importing your account with which ever one you have:\
   \
   [<mark style="color:blue;">**Importing your account into Xumm**</mark>](../getting-started-with-xumm/importing-your-account/)
