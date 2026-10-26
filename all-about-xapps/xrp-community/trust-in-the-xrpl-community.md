---
description: How to figure out who to trust in the XRPL community
---

# Trust in the XRPL Community

The XRPL community is a large network of users, developers, businesses and investors. It has been around for over a decade and it continues to grow and prosper. Even so, it is important to make sure you are vetting the businesses and applications you use. This article gives you suggestions and answers to frequently asked questions. They should help you get going in the right direction.

### How can I trust anyone?

To start, if you own XRP, you already trust the XRP Ledger community. The XRPL is a decentralized blockchain. In any community, it can be very difficult to actually trust someone. In the case of a developer, you might trust their code or you might trust their intentions, but when it comes to software there are so many variables and unknown factors. (ie. issues with dependencies or 3rd party libraries.) The same applies to business and token issuers. They might have a great business plan and a wonderful marketing strategy, but that is no guarantee of success.

### Is Xaman Trustworthy?

When handling digital assets, you shouldn't have to rely on blind faith. We designed Xaman with a "verify, don't trust" philosophy. You can trust our application because of our architecture, not just our words:

* **True Self-Custody:** Xaman is entirely non-custodial. We never see, store, or have access to your account secret. Your funds remain under your exclusive control on the XRP Ledger.
* **Your Keys, Your Sovereignty:** All signing happens strictly on your local device. Only you have custody over your funds.
* **Decentralized Independence:** Xaman connects directly to the XRP Ledger. Transactions settle on-chain and your funds remain secure and accessible even if our backend servers go offline.
* **Proven Security Standards**: Operating since 2018 out of the Netherlands, our code has undergone an independent audit (Cossack Labs, August 2021). To date, Xaman has maintained a clean record with no known protocol breaches.
* **Hardware-Grade Security:** For maximum protection, Xaman integrates directly with our Xaman NFC cards, allowing you to sign transactions using an audited hardware secure element.
* **Public Accountability:** We operate with a fully doxxed, public-facing team. You can monitor our network reliability in real-time via our [Infrastructure Status page](https://status.xrpl-labs.com/)
* **Ecosystem Commitment:** Beyond building an application, we develop open-source SDKs, and maintain open-source developer tooling.
*   **Foundational Infrastructure & Network Governance**

    XRPL Labs doesn't just build client-facing apps. We are a core infrastructure backbone for the entire XRP Ledger:

    * **Trusted Network Validator:** We operate a primary XRPL validator node (`validator.xrpl-labs.com`) that is officially included on the default Unique Node List (dUNL) by the XRPL Foundation and Ripple. This means our servers actively vote on ledger consensus, protocol amendments, and the integrity of every transaction on the network.
    * **Powering Ecosystem Traffic (XRPLcluster)**: We built and maintain XRPLcluster, the globally distributed node network that routes billions of public API requests and ledger queries for thousands of developers, businesses, and wallets across the globe every day.
    * **Vested in Ledger Health:** We contribute directly to network consensus and public routing so our commitment is aligned with the long-term health, decentralization, and uptime of the entire ledger, not just our own bottom line.

### Is Xaman safe to use?

It definitely is. Keeping your XRPL/Xaman accounts safe is what we do. We actually have an article dedicated to this topic:

{% content-ref url="../../security-and-xumm/all-about-security/how-secure-is-xumm.md" %}
[how-secure-is-xumm.md](../../security-and-xumm/all-about-security/how-secure-is-xumm.md)
{% endcontent-ref %}

### What is an xApp?

There are two kinds of xApps in Xaman:

* Verified - The xApp was either created by the XRPL Labs team or it has been vetted by XRPL Labs.
* Unverified - The xApp was created by a community developer or business that has not been vetted by XRPL Labs.

### Are unverified xApps safe to use?

The process of creating an xApp has been [**streamlined**](https://docs.xumm.dev/) so making an xApp is easier than ever before, but just because it is easy, does not make it unsafe. We have incorporated several checks and balances into each step to ensure that all xApps meet our high standards of quality and useability. Having said that, we do recommend that you do your own research when it comes to choosing which xApps to use. Things like:

* **Visit the developers website.** Does it look professional? Is it up to date?
* **Read the description of the xApp.** Is it clear as to what it does? Does it make sense?
* **Is the developer easy to get a hold of?** How quickly do they respond to messages?
* Does the developer offer customer support?
* Is the developer active in the XRP Ledger community?

{% hint style="danger" %}
Keep in mind, many xApps have the ability to send you transaction requests or payment requests. It is absolutely imperative that you review all transactions **before you sign** them in Xaman.
{% endhint %}

Even when using an unverified xApp, Xaman will never hand over your account secret to the developer. The xApp must request a transaction, and Xaman will explicitly show you exactly what will happen to your account (e.g., how much XRP will be spent) before you authorize it with a biometric sign or password.

### Can an xApp access my XRPL / Xahau accounts?

An xApp is a web application that runs inside Xaman. It does not access your account directly. The first time an xApp wants to display your public address, Xaman shows an authorization prompt. You can approve or deny.

If you approve, the xApp gets exactly two permissions:

* **See your public r-address.** Your address is already public on the XRPL. Approving the xApp does not expose it to anyone new.
* **Send push notifications through Xaman.** The xApp can send you notifications, but only through Xaman's notification system.

An xApp cannot:

* Access your account secret
* Sign transactions on your behalf
* Receive your balance from Xaman
* Access your camera, microphone, location, or any other device sensor

Your keys never leave your device. An xApp can create a transaction and ask you to review and sign it. You will see the full transaction details before you sign. You can decline. Nothing is signed or sent without your explicit approval and vault authentication (passcode, biometrics, or Tangem).

You can review and revoke any authorized xApp at any time. See What is the Third Party Apps section?

### How do I vet a token issuer before creating a Trust Line?

There is no foolproof way of ensuring a token is not a scam. It all comes down to trusting the issuer.

As a minimum, before you even consider setting up any Trust Line, we recommend that you do the following:

1. Visit their website.
2. Read their business plan. (Goals, execution, timeline, tokenomics, etc.)
3. Review their marketing plan.
4. Research their staff (CEO, developers, support, etc.)
5. Research their funding.
6. Have they gone through the KYC process?
7. Have you tried to contact them? How long did it take for them to reply?

For tokenized real-world assets (for example, tokens that claim to represent shares in a company), add one more check. Confirm the issuer address through the program's own official website or announcement. A token name alone does not prove what the token represents. Anyone can create a token with any name.

Remember, when you create a Trust Line you are basically saying: "I trust you and your token. I have reviewed your business plan, which included your marketing strategy, your goals, your timelines and your tokenomics. It is well organized, realistic and viable. I have researched your staff including your CEO, your developers and your support personnel and they are all world class, highly motivated and honest people who have well documented employment histories. I trust your funding sources and I believe you did not simply create a token to try to scam people. I trust your KYC information is legitimate. I trust that you will provide excellent customer support and that you will be easy to contact and reply to my inquiries. I trust you will not abandon your project. Finally, I trust that you and your staff have the necessary skills and experience to launch and maintain a token on the XRPL."

