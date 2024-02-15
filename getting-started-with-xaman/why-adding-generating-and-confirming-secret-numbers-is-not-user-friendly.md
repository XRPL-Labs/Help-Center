---
description: Why adding / generating & confirming "Secret Numbers" is not user friendly
---

# Why adding / generating & confirming "Secret Numbers" is not user friendly

#### Confirming your secret numbers is time consuming and hard. Why?

When importing or generating your account, you may have to enter (or confirm) your Secret Numbers. This is a time consuming and hard process. Annoying. We agree. And to make it even worse, when you go back and forth, a whole new set of numbers is generated. **WHY!?**

&#x20;

We created the Secret Numbers to replace the existing secrets like mnemonic words and the family seed (s... code), because it's equally secure and a lot less prone to errors.&#x20;

&#x20;

The common formats for XRPL account secrets are (at the time of writing this, July 2019):

&#x20;

* Family Seed, eg. sh1HiK7SwjS1VxFdXi7qeMHRedrYX
* Mnemonic, eg. car banana apple road ...

These formats are prone to typos and not that user friendly. Using numbers means it's language (spoken, written) agnostic as well. They may be especially intimidating for the public that's relatively new to cryptocurrencies / blockchain technology.

&#x20;

This library encodes the entropy to generate accounts into 8 chunks of 6 digits, of which 5 digits are 1/8th of the entropy, and a 6th digit contains a checksum allowing real-time typo detection.

&#x20;

### A secret now looks like: <a href="#h_be422ab2cf" id="h_be422ab2cf"></a>

```
554872 394230 209376 323698
140250 387423 652803 258676
```

For compatibility with existing clients, this library supports exporting the family seed for a generated / entered "Secret Number"-set as well.

&#x20;

## Entering Secret Numbers <a href="#h_72f721ce4a" id="h_72f721ce4a"></a>

**When entering Secret Numbers, XUMM starts with a random digit, each time, forcing you to go to the right digit with a Plus and Minus key, then to go to the next field.**

&#x20;

**We do this so:**

&#x20;

1. **A compromised keyboard cannot "sniff" the numbers you are entering**
2. **Someone looking over your shoulder can't follow it based on the position of your finger when tapping**

It's just way more secure. We think the one time annoying entering is a good trade-off for a lot more security.

&#x20;

This leaves an open question.

If Xumm is the only app that uses Secret Numbers how are accounts created in Xumm migrated to other apps?

There is a tool to convert Xumm Secret Numbers into a standard XRP seed that is [explained here](https://support.xumm.app/hc/en-us/articles/360018136180).
