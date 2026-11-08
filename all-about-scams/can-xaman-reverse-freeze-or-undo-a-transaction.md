# Can Xaman reverse, freeze or undo a transaction?

**All transactions on the XRP Ledger are final.** Once a transaction is confirmed, no one can change it or cancel it. This includes Xaman.&#x20;

#### Why can't Xaman just cancel or reverse it?

Xaman is a self-custody wallet, which means it acts like a remote control for the XRP Ledger. It allows you to view and interact with your account, but Xaman does not hold your funds and has no administrative control over the network.

**What about validators?**\
Even though Xaman operates a validator on the network, this does not give us special privileges. Decentralized networks don't have a "central boss" or customer support team that can override the rules. Validators simply confirm that transactions follow the math and rules of the network; they cannot rewrite history, freeze accounts, or undo mistakes.

#### So, what are my options?

Depending on your specific situation, here are the steps you can take:

**1. I sent funds to an exchange, and they didn't arrive**

This usually happens if you forgot to include the exchange's **Destination Tag**, or if you entered the wrong one.

* **What to do:** Contact the support team of the crypto exchange you sent the funds to. Provide them with the transaction hash (TxID). Most exchanges have a standard process to locate your funds and credit them to your account.

**2. I accidentally sent funds to the wrong address**

If you sent funds to a personal wallet address that you don't control, the only way to get them back is if the owner voluntarily returns them.

* **What to do:** You can try sending a tiny "micro-payment" (e.g., 0.000001 XRP) to that same address. In the **Memo** field of this tiny transaction, write a polite message explaining the mistake and asking them to return the funds. _(Note: There is no guarantee they will respond or comply)._

**3. My account was compromised, and my funds were stolen**

If you fell victim to a scam or someone gained access to your secret recovery numbers, Xaman cannot freeze the scammer's account or retrieve your assets.

* **What to do:** Treat this as a theft. File a report with your local law enforcement or cybercrime division. They are the only entities equipped to investigate stolen digital assets.

**4. I lost my secret backup or my account says "Read Only"**

Your options here depend entirely on whether your current Xaman app still has signing access:

* **If you have "Full Access" on your phone but lost your paper backup:** Create a brand-new XRPL account in Xaman (which gives you a new set of secret numbers), write the new backup down safely, and immediately send all your funds from the old account to the new one.
* **If your account says "Read Only":** Your phone no longer holds the keys to sign transactions. You **must** find your physical backup (secret numbers, family seed, or mnemonic phrase) to restore full access. Without it, the funds cannot be moved.
