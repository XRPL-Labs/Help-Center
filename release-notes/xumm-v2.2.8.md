# Xumm v2.2.8

![https://support.xumm.app/hc/article\_attachments/5569498665362/mceclip0.png](https://support.xumm.app/hc/article\_attachments/5569498665362/mceclip0.png)

XUMM 2.2.8 mainly contains a few fixes on top of the [previously released 2.2.6 version](https://support.xumm.app/hc/en-us/articles/4415502008082).

#### **Improved in 2.2.8**

* The currency picker (token list) when sending a token (Send flow) now offers a more spacious view allowing tokens to be filtered & selected.
* When XUMM couldn’t load the encrypted data store (e.g. because of a timing bug on some older Android smart phones) XUMM will now show an error instead of resetting the XUMM data store.

#### **Fixed in 2.2.8**

* Fixed an error for OfferCreate transactions using Tickets.
* Fixed a bug causing NFTokenMint transactions to show the same TokenID for the all transactions related to the token.
* Fixed a bug that caused XUMM to randomly crash on startup on a small number of Android devices.
* The **Exchange** feature (tap a Trust Line then tap the Exchange button) shows a confirmation dialog before exchanging. The confirmation dialog inverted the from/to currency.
* Fixed XUMM rejecting a sign request when using Tickets in combination with an OfferCreate transaction.

#### **For Developers in 2.2.8**

* Assets (CSS, JS, images, etc.) are no longer cached in xApps: they are always fetched live when the xApp starts.
