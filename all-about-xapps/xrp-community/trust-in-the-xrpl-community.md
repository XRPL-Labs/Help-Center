---
description: How to figure out who to trust in community
---

# Trust in the XRPL Community

The XRPL community is a large network of users, developers, businesses and investors. It has been around for over a decade and it continues to grow and prosper. Even so, it is important to make sure you are vetting the businesses and applications you use. This article gives you suggestions and answers to frequently asked questions. They should help you get going in the right direction.

### How can I trust anyone?

To start, if you own XRP, you already trust the XRP Ledger community. The XRPL is a decentralized blockchain. In any community, it can be very difficult to actually trust someone. In the case of a developer, you might trust their code or you might trust their intentions, but when it comes to software there are so many variables and unknown factors. (ie. issues with dependencies or 3rd party libraries.) The same applies to business and token issuers. They might have a great business plan and a wonderful marketing strategy, but that is no guarantee of success.

### Is Xaman Trust Worthy?

When handling digital assets, you shouldn't have to rely on blind faith. We designed Xaman with a "verify, don't trust" philosophy:

* Your Keys, Your Sovereignty: Xaman is non-custodial. All signing happens strictly on your local device. We never see, hold, or store your private credentials, meaning only you have custody over your funds.
* Decentralized Independence: Xaman connects directly to the XRP Ledger. Because transactions settle on-chain, your funds remain secure and accessible even if our backend servers go offline.
* Proven Security Standards: Operating since 2018 out of the Netherlands, our code has undergone rigorous independent audits. To date, Xaman has maintained a clean record with zero protocol breaches.
* Ecosystem Commitment: Beyond building an application, XRPL Labs maintains validator nodes, develops open-source SDKs, and runs public infrastructure monitoring to bolster the resilience of the wider XRP Ledger ecosystem.

### Is Xaman safe to use?

It definitely is. Keeping your XRPL/Xaman accounts safe is what we do. We actually have an article dedicated to this topic:

{% content-ref url="../../security-and-xumm/all-about-security/how-secure-is-xumm.md" %}
[how-secure-is-xumm.md](../../security-and-xumm/all-about-security/how-secure-is-xumm.md)
{% endcontent-ref %}

#### What is an xApp?

There are two kinds of xApps in Xaman:

* Verified - The xApp was either created by the XRPL Labs team or it has been vetted by XRPL Labs.
* Un-Verified - The xApp was created by a community developer or business that has not been vetted by XRPL Labs.

#### Are un-verified xApps safe to use?

The process of creating an xApp has been [**streamlined**](https://docs.xumm.dev/) so making an xApp is easier than ever before, but just because it is easy, does not make it unsafe. We have incorporated several checks and balances into each step to ensure that all xApps meet our high standards of quality and useability. Having said that, we do recommend that you do your own research when it comes to choosing which xApps to use. Things like:

* Visit the developers website. Does it look professional? Is it up to date?
* Read the description of the xApp? Is it clear as to what it does? Does it make sense?
* Is the developer easy to get a hold of? How quickly do they respond to messages?
* Does the developer offer customer support?
* Is the developer active in the XRP Ledger community?

{% hint style="danger" %}
Keep in mind, many xApps have the ability to send you transaction requests or payment requests. It is absolutely imperative that you review all transactions **before you sign** them in Xaman.
{% endhint %}

#### Can an xApp access my XRPL / Xahau accounts?

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

#### How do I vet a token issuer before creating a Trust Line?

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

Xaman also maintains a safety blacklist of known scam and spam issuers. See Spam on the XRP Ledger. If an issuer is on that list, Xaman blocks the trust line for you.
