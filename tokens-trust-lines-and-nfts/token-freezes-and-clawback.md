---
description: What it means when a token's issuer can freeze your tokens or take them back
---

# Token freezes and clawback

### Background

Tokens on the XRP Ledger (XRPL) work differently from XRP. XRP is the native coin of the XRP Ledger, and no one can freeze it or take it back once it is in your account. Tokens are created by issuers, and some issuers keep the power to freeze the tokens they issue, or even to take them back. This is called a freeze or a clawback.

These powers are not a sign that something is wrong. Many issuers, especially regulated ones like stablecoin issuers, need them to meet legal requirements. They do mean that when you hold a token, you are trusting its issuer as well as the XRP Ledger. This article explains what each power does, how to check whether an issuer has it, and what to do if it affects you.

This article covers tokens on the XRP Ledger. Xaman is a self-custody wallet, so we cannot freeze your tokens, and we cannot unfreeze them or return them either. Only the token's issuer can.

### What a freeze does

A freeze stops tokens from moving. The tokens stay in your account, and your balance still shows them, but you cannot send or trade them while the freeze lasts. An issuer can freeze tokens in three ways:

| Freeze                | What it affects                              | What you can still do                                     |
| --------------------- | -------------------------------------------- | --------------------------------------------------------- |
| **Individual freeze** | One holder's tokens from that issuer         | Receive more of the token, and send it back to the issuer |
| **Deep freeze**       | One holder's tokens, more strictly           | Send the token back to the issuer                         |
| **Global freeze**     | Every holder of every token from that issuer | Send the tokens back to the issuer                        |

Whichever kind of freeze applies, you can always send frozen tokens back to their issuer. That matters when an issuer offers to redeem its tokens, for example to exchange a stablecoin for money.

A freeze can be lifted. When the issuer ends it, your tokens can move again, with nothing for you to do.

#### No Freeze: an issuer's permanent promise

An issuer can turn on a setting called **No Freeze**. This permanently gives up its power to freeze individual holders, and it cannot be undone. An issuer with No Freeze can still start a global freeze, though it can never end one. That last part works like an emergency stop with no restart: it can halt everything, permanently.

### What a clawback does

A clawback goes further than a freeze. It lets the issuer take its tokens out of your account and back into its own. Issuers usually use it for legal reasons, such as recovering tokens sent to an account linked to a crime.

Clawback comes with firm limits, and those limits protect you:

* **An issuer must turn it on before it issues any tokens.** The XRP Ledger does not let an issuer add clawback later, so it cannot surprise holders who are already in.
* **Once it is on, it stays on.** The issuer cannot turn it off again.
* **An issuer cannot have both clawback and No Freeze.** The two settings rule each other out.
* **It only takes that issuer's tokens.** No one can claw back your XRP or another issuer's tokens.
* **It can take up to your full balance of the token,** including tokens you have added to an AMM pool.

Keeping your XRP balance low, or trying to remove the trust line, does not stop a clawback.

### How to check a token before you add it

The best time to think about these powers is before you add a trust line. Every token's issuer has an account on the XRP Ledger, and its settings are public. Any XRP Ledger explorer shows them when you look up the issuer's r-address. Look for settings named **Allow Trust Line Clawback**, **No Freeze**, and **Global Freeze**, or similar names, since explorers label them slightly differently. Every issuer can start a global freeze, so the **Global Freeze** setting only tells you whether one is in place right now.

A token's name proves nothing on its own. Any issuer can give a token any name, so always check that the issuer's r-address matches the official one published by the project. See [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning) for what to look at.

If an issuer can freeze or claw back its tokens, ask yourself whether you trust it to use that power fairly. For a regulated stablecoin issuer, the answer may well be yes. For an unknown issuer, those same powers are a reason for caution.

### If your tokens are frozen or clawed back

A freeze or a clawback can only come from the token's issuer, so the issuer is the one to ask. Xaman cannot see why it happened, and we cannot reverse it.

To find out what happened:

1. Look up the issuer's official website or social media accounts for an announcement.
2. Contact the issuer through those official channels, and ask why your tokens were frozen or taken.
3. If the issuer offers to redeem frozen tokens, send them back to the issuer's r-address only after you have confirmed the address on its official website.

Be careful of anyone who contacts you offering to unfreeze or recover your tokens for a fee. Only the issuer can do either, and no genuine issuer asks a stranger to collect a fee for it. See [Recovery scams](../scams-and-staying-safe/recovery-scams.md).

### Frequently asked questions

**Can my XRP be frozen or clawed back?**

No. Freezes and clawbacks only apply to tokens. XRP is the native coin of the XRP Ledger, and no one can freeze it or take it from your account.

**Can Xaman freeze or claw back my tokens?**

No. Only a token's issuer can freeze or claw back that token. Xaman is a self-custody wallet and has no control over your tokens, or over any issuer's settings.

**Can any token issuer freeze its tokens?**

Yes, with one exception. Every issuer can start a global freeze at any time, and it can freeze individual holders unless it has turned on No Freeze. The exception is an issuer whose account is blackholed, meaning no key can sign for it anymore. A blackholed issuer cannot start a freeze of any kind. See [What is a blackholed account?](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/what-is-a-blackholed-account)

**What is a deep freeze?**

A deep freeze is the strictest way an issuer can freeze one holder. A regular freeze stops you from sending the token, but you can still receive it. A deep freeze stops both: no one else can send you the token, you cannot send it to anyone except the issuer, and you cannot trade it. An issuer can only deep freeze a holder it has also frozen in the regular way, and an issuer with No Freeze cannot use it at all.

**If an issuer turns on No Freeze, can it still freeze its token?**

Only all at once, and only for good. No Freeze permanently removes the issuer's power to freeze individual holders. It can still start a global freeze, but it can never end one, so the token would stay frozen permanently. Even then, holders can still send the frozen tokens back to the issuer.

**My exchange froze my funds. Is that the same thing?**

No. An exchange holds your funds for you, so it can freeze them under its own rules, including XRP. That happens inside the exchange's systems, not on the XRP Ledger, and only the exchange can explain or lift it.

**Do Multi-Purpose Tokens (MPTs) work the same way?**

They work in a similar way. An MPT issuer can lock one holder or all holders, which stops the tokens from being sent or received. It can claw back tokens only if it turned that option on when it created the MPT. See [How Multi-Purpose Tokens (MPTs) work on the XRP Ledger](https://help.xaman.app/app/learning-more-about-xaman/how-multi-purpose-tokens-mpts-work-on-the-xrp-ledger).

**Does a frozen token still count toward my reserve?**

Yes. As long as the trust line exists, it keeps its reserve, even while the token is frozen. See [Reserves on the XRP Ledger](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/about-reserves).

Crypto assets can change in value. This article explains how the feature works and is not financial advice.

### See also

* [Trust Lines on the XRP Ledger](https://help.xaman.app/app/xrp-ledger-resources/xrp-ledger-concepts/trust-lines-on-the-xrp-ledger)
* [How issued tokens work on the XRP Ledger](https://help.xaman.app/app/learning-more-about-xaman/how-issued-tokens-work-on-the-xrp-ledger)
* [Token vetting and the token warning](https://help.xaman.app/app/learning-more-about-xaman/token-vetting-and-the-token-warning)
* [How to create a Trust Line](https://help.xaman.app/app/learning-more-about-xaman/how-to-create-a-trust-line)
* [How to remove a Trust Line](https://help.xaman.app/app/all-about-xapps/xrpl-services/token-trasher/how-to-remove-a-trust-line)
