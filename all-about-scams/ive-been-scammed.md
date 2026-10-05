---
description: What to do if you've been hacked or scammed
---

# I've been scammed!

If you are the victim of a crime, report it to your local police department as soon as possible. This article walks through the steps in order: contacting the police, what to include in the report, securing your account, and how to reduce the chance of it happening again.

### Were your funds sent or taken?

* If **you sent funds to a scammer** (an investment opportunity, an airdrop, a fake offer), your account is most likely still intact. Your priority is reporting — to the police, and to any exchange the funds passed through.
* If **someone took funds from your account without your permission**, or you may have shared your account secret, your account is compromised. Secure the account (re-key or move to a new account) first or in parallel with reporting.

### Why should I contact the police?

Reporting a scam to the police does not, on its own, guarantee the recovery of your funds, but it is often the key that unlocks every other recovery route:

* **It creates an official record.** Exchanges, banks, and insurance providers often require a police report number before they will act on a fraud claim — freezing an account, holding funds, or processing a compensation request.
* **Speed matters.** Funds on the XRP Ledger can be moved or cashed out within minutes. A police report allows law enforcement to pursue tracing and freezing requests while the trail is still warm.
* **Single reports become investigations.** Local police stations often handle the paperwork and escalate your case to specialized cybercrime or financial crime units, which have the technical tools and legal authority to track blockchain transactions and flag stolen assets on exchanges. Aggregated reports also expose patterns — repeat offenders, mule accounts, shared infrastructure — that no individual can trace alone.
* **It may be required for compensation.** Some insurance policies and exchange compensation programs require a filed police report as a precondition.
* **It may help protect you from a second scam.** After a scam, many victims are contacted by "recovery agents" who promise to retrieve their funds for a fee. Those are almost always a second scam. A police contact is a safe way to hear that warning directly.
* **It is free and parallel.** Filing a report does not delay anything else you can do — it only adds a channel.

Some countries have a special "cyber crime" or "financial crime" reporting body you can report to as well. Your local police can point you to the right channel.

### What to include in your police report

Before you file the report, preserve the evidence:

* Take screenshots of every conversation with the scammer (chat, DMs, email, SMS).
* Save the scammer's r-address(es) and the transaction hash / ID of every payment you made.
* Do not delete the chat history or the app conversation before you file the report — the police may need access to your phone and internet records.

When you file, give them the precise technical details. You can copy and paste the following directly into your report:

* Date/time of incident:
* Your XRP Ledger address (r-address):
* The scammer's address (r-address):
* Transaction hash / ID:
* Amount lost:

If you are not sure where to find a transaction hash, contact [Xaman Support](https://xumm.app/detect/xapp:xumm.support) and we will help you pull it from the ledger.

### Securing your account

If your account was compromised (someone accessed it without your permission), act now to stop further losses:

* **Re-key your account** and disable the master key for the compromised account. This prevents the scammers from accessing your account again.
  * [How to re-key your XRPL account](../learning-more-about-xaman/how-to-rekey-your-account.md)
  * [How to disable the master key on an account](../learning-more-about-xaman/how-to-disable-the-master-key.md)
* If re-keying looks too complicated, **create a new account**, move your remaining funds to the new account, then delete the compromised account.
  * [How to create a new XRP Ledger account using Xaman](../getting-started-with-xaman/your-first-xrp-ledger-account/how-to-create-an-xrpl-account.md)
  * [How to delete your XRP Ledger account](../learning-more-about-xumm/deleting-an-xrpl-account.md)
  * Note: Trust lines will have to be duplicated (temporarily) in the new account until they can be removed from the old one, requiring enough XRP to cover reserves until the move is complete.

### Work out how your account secret was leaked

If your account was compromised, try to figure out how the scammers got your account secret:

* Have you ever shared your account secret with anyone?
* Was it stored in a cloud account or somewhere else online?
* Was it stored on your PC or mobile device?
* Have you ever entered it into a Google form, another crypto wallet service, or a website?
* Has your phone ever been in for servicing or repairs?
* Do you use public Wi-Fi?

If none of these apply, there is a good chance your mobile device has been compromised. We strongly recommend wiping your phone and reinstalling applications one at a time. **Do not restore from a backup** — without knowing how the phone was compromised, restoring could re-introduce the problem.

### Watch out for a second scam

The most common follow-up to a scam is a **recovery scam**: someone contacts you — often posing as a "recovery agent," a "blockchain tracker," or even "Xaman support" — and promises to get your funds back for a fee. These are almost always a second scam.

* Xaman support will **never** ask you for your account secret. Anyone who does is a scammer.
* Do not pay anyone who promises to recover stolen funds.
* If you are unsure whether a message or person is legitimate, contact [Xaman Support](https://xumm.app/detect/xapp:xumm.support).

### Frequently asked questions

#### Can Xaman conduct its own investigation?

Xaman is not part of any governmental law enforcement agency, and we do not have the legal authority to conduct a criminal investigation. We are also not permitted to interfere in police investigations. If the police require our assistance, they will contact us.

#### My police department doesn't know anything about crypto scams

Investigating criminal matters, which now includes crypto and blockchain crimes, is one of the primary responsibilities of law enforcement. Local police departments are getting better at investigating cyber crimes — blockchain has been around for over 15 years now. Local stations typically handle the paperwork and escalate to specialized units. If there is any chance of recovering your funds, the police will need to be involved.

#### Why can't Xaman just reverse the transactions and get my funds back?

Transactions on the XRP Ledger cannot be reversed, blocked, or "undone." The XRPL has no administrative functions built into it, so there is no way for Xaman or anyone else to modify or change a completed transaction. All transactions on the XRPL are permanent.

#### Why can't I just change my 6-digit passcode or my signing password?

The 6-digit passcode is used to access the Xaman app and, in some cases, sign transactions in Xaman. It is not used to access your XRPL account (that's what your account secret is for). Changing your passcode has no effect on your account secret.

The same applies to your signing password. Both the passcode and the signing password are local security measures that protect your account secret on your phone. They do not prevent someone from accessing your account if they already have your account secret.

### What we are doing about scams

The XRP Ledger is a decentralized, public network. There are no "network police," no central authority that can reverse a transaction, block an address at the protocol level, or remove a scammer from the ledger. Every address is public, and anyone can send XRP, a token, an escrow, or an NFT to any other address. You are responsible for your own funds, and the strongest defence is recognizing a scam before you act on it.

What we do, every day:

* **Blacklist.** Xaman maintains a blacklist of thousands of known scam and spam accounts, updated daily from multiple sources: Ripple's own flags, the xrpl.to scam database, OFAC sanctions, and our internal monitoring. When you try to send to a blacklisted address, the app shows a warning before you sign.
* **Pre-sign warnings.** Before you confirm any transaction, Xaman checks the destination against the blacklist and other threat feeds. Known-bad addresses are flagged so you see the warning before you tap sign.
* **Memo suppression.** Memos from blacklisted or known-spam accounts are hidden by default, so a phishing link does not sit in your transaction history looking like a legitimate message.
* **Scam website takedowns.** We actively report and pursue takedown of websites that impersonate Xaman or the XRP Ledger.
* **Social media enforcement.** We report scam accounts on X and other platforms for removal.
* **Support-led forensics.** When you report a suspicious transaction, our team pulls the full ledger history, checks every involved address against the blacklist, and identifies the attack pattern. This is how new scam accounts get flagged and added.
* **NFT offer blocking.** You can turn off incoming NFT offers in your account settings so unsolicited buy offers stop appearing in your app.

What we cannot do:

* Reverse or delete a completed transaction.
* Stop an unsolicited incoming payment, escrow, or NFT at the protocol level.
* Control what a third-party website asks you to sign.
* Guarantee that a brand-new scam account has already been flagged.

The single best way to keep your assets safe in the future is[ **to contact us**](https://xumm.app/detect/xapp:xumm.support) if you are ever unsure about something. We live and breathe the XRP Ledger. We are constantly searching for new scams and are always here to help you verify whether an offer, airdrop, or transaction is safe before you "Slide to send."

It is very important that you **never sign a transaction you did not start yourself**. If something looks unexpected, contact [**Xaman Support**](https://xumm.app/detect/xapp:xumm.support) before you act. We will check it for you.

### Moving forward

We take security very seriously. If you have found yourself in this situation, consider the following:

* **Xaman (Tangem) cards** — an excellent way to take the security of your XRPL account to the next level. See: [How safe are Xaman (Tangem) cards?](../xumm-tangem-cards/how-safe-is-a-card.md)
* **Review:** [How secure is Xaman?](../security-and-xumm/all-about-security/how-secure-is-xumm.md)
* **Preparing for future scams.** There will always be bad actors trying to exploit users for their funds. The single best protection is to [**Contact us**](https://xumm.app/detect/xapp:xumm.support) if you are ever unsure about something. We live and breathe the XRP Ledger, we are constantly tracking new scams, and we are always here to help you verify whether an offer, an airdrop, or a transaction is safe before you "Slide to send."

### Summary

* Contact your local police immediately if you are the victim of a crime, and include the technical details (r-addresses, transaction hash, amount) in your report.
* If your account was compromised: either re-key it, or create a new account and move your assets over.
* Never share your account secret with anyone, and be wary of "recovery" offers after a scam.
