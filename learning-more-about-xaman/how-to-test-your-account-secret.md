---
description: How to test/verify your Account Secret
---

# How to Test or Veriy your Account Secret

You may need to uninstall Xaman and reinstall it.

Before you do, make sure the Account Secret on your paper backup actually unlocks the account you are about to remove. Sometimes the Account Secret a person has on paper does not access the account they think it accesses. If that is true for you and you uninstall anyway, you can lose access to your account.

This test takes about two minutes. It shows you the r-address that your Account Secret belongs to, so you can compare it to your account in Xaman.

{% hint style="info" %}
**Security first!** \
When you handle your Account Secret, make sure you are in a private location. Never enter your Account Secret while screen recording, while sharing your screen, or in view of security cameras.
{% endhint %}

### How the test works

You run the test by starting the account import process. Xaman checks the Account Secret and shows you the matching r-address. You stop there. You do not finish the import. For this test, you only need the r-address that Xaman shows.

### Step-by-step instructions

1. Open the account you would like to check in Xaman. Copy its r-address to a safe place. This is the r-address you will compare against.
2. Launch Xaman. Press the **Settings** button, choose **Accounts**, then press **+ Add account**.
3. Press **Import an existing account**. You see the access mode screen. Choose **Full access**, then press **Next**.
4. Choose the Account Secret type that matches what you have (Secret Numbers, Family Seed, or Mnemonic). Press **Next**.
5. Carefully enter the Account Secret from your paper backup. Press **Next**.

Xaman now shows you one of two screens. Both screens show an r-address.

#### Result A: The account is already in your wallet

Xaman tells you that this Account Secret belongs to the r-address shown and that the account has already been imported to your wallet.

Look at the r-address on the screen. Does it match the r-address of the account you are about to lose?

* **Yes, it matches.** Your paper Account Secret is for this account. It is safe to uninstall.
* **No, it does not match.** Stop. Do not uninstall yet. This Account Secret belongs to a different account. Find the correct Account Secret before you proceed.

#### Result B: The account is not in your wallet

Xaman shows the r-address that the Account Secret belongs to. Compare it to the r-address of the account you are about to lose.

* **Yes, it matches.** Your paper Account Secret is for this account. It is safe to uninstall.
* **No, it does not match.** Stop. Do not uninstall yet. This Account Secret belongs to a different account. Find the correct Account Secret before you proceed.

If you only wanted to read the r-address and you are sure, press the back button. Do not press Confirm. The account is added to your wallet only after you press Confirm and finish the setup steps.

### If the r-addresses do not match

This means the Account Secret on your paper backup is not for the account you thought. Do not uninstall. Do not delete your current Xaman setup. First, find the correct Account Secret for that account. If you cannot find it, contact Xaman Support before you uninstall.

### Additional reading

* [I've lost my account secret!](https://help.xaman.app/app/learning-more-about-xaman/ive-lost-my-account-secret)
* [Can I view/export my account secret?](https://help.xaman.app/app/learning-more-about-xaman/can-i-view-export-my-account-secret)
* [How to import your Secret Numbers](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-secret-numbers)
* [How to import your Family Seed](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-a-family-seed)
* [How to import your Mnemonic](https://help.xaman.app/app/getting-started-with-xaman/importing-your-account/...with-a-mnemonic)
