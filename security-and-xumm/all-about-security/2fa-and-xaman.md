---
description: >-
  No. You cannot use traditional 2FA (such as SMS codes or Google Authenticator)
  on the XRP Ledger.
---

# Does Xaman support Two-Factor Authentication (2FA)?

Traditional 2FA is a strong security method for centralized platforms, such as email services, social media accounts, and crypto exchanges. Xaman is a decentralized, self-custodial wallet, so traditional 2FA does not work with it.

#### Why does 2FA not work on the XRP Ledger?

Traditional 2FA relies on a **shared secret**. When a centralized service asks you for a 6-digit code, you and the service each hold a secret that generates and verifies that code.

The XRP Ledger is a public, decentralized network. No central authority, company, or server exists to store the shared secret or verify your login. To add traditional 2FA, the network would need a third-party server to control access. A centralized gatekeeper does not work on a decentralized blockchain. Even 2FA on centralized platforms can fail. For example, if your code arrives by SMS, an attacker who takes over your phone number receives your code.

#### How Xaman keeps your account secure without 2FA

Xaman is a self-custody wallet. Security relies on device-level protection, not on a server. To send funds from Xaman, an attacker must pass these security layers:

1. **Physical access:** The attacker must steal your phone.
2. **Device unlock:** The attacker must bypass your phone's biometric security (Face ID or fingerprint) or the phone's PIN.
3. **App passcode:** The attacker must guess your 6-digit Xaman passcode. A 6-digit code has 1,000,000 possible combinations. Xaman prevents brute-force guessing. After 5 incorrect attempts, Xaman adds a time delay. After the 9th incorrect attempt, Xaman requires a 2-hour wait before the next attempt. At that rate, it takes over 228 years to try every combination.
4. **Signing password (optional):** If you set a signing password, the attacker must also guess this password to move funds. Xaman allows very long signing passwords. A long, complex password is extremely hard to guess. See [Resetting the (account) signing password](https://help.xaman.app/app/learning-more-about-xaman/resetting-the-account-signing-password).

If you use an Xaman (Tangem) card, the attacker must also have the card itself, because the account secret lives on the card, not on the phone.

#### For the highest level of security: Xaman (Tangem) cards

We recommend a hardware wallet over a software-only setup. We partnered with Tangem to create the **Xaman (Tangem) card**.

The card is the size of a credit card and fits in your physical wallet. It contains a security chip that offers bank-grade security and has been fully audited. When you tap the card to the back of your phone using NFC (Near Field Communication), the chip generates your account secret and stores it inside the chip. The chip powers itself from the NFC tap, so the card ships with no account secret on it.

The account secret is generated inside the chip. It is never exposed to your phone, the internet, or you. To sign a transaction, you must physically tap the card to your phone. This tap is a physical second factor.

**Learn more:** [All about Xaman (Tangem) cards](https://help.xaman.app/app/xaman-tangem-cards/xumm-tangem-cards)
