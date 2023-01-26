# Xumm v2.2.6

**Depending on your OS settings, your device may or may not auto-update. Check your App / Play store for the latest version.**

XUMM 2.2.6 contains new features, a number of improvements & important fixes.

#### **New in 2.2.6**

* The **Exchange** panel (tap a Trust Line, tap Exchange) now shows the **slippage tolerance (percentage)** allowed, the **exchange rate** calculated and the **minimum amount to receive** (worst case) trade results. If a better rate can be obtained, the XRP Ledger will. Worst case you will receive the lower value displayed. If the lower value displayed can’t be satisfied, the trade will be cancelled.
* Added support for the new **Tangem Note** and **Tangem Multi** Asset cards.
* Support added for all **XLS20** (NFT) transaction types through sign requests. **To add the XLS20 testnet, a special QR code needs to be scanned.**
* The sign request screen now shows the accounts (signers) when setting a Signer List (multi signing).
* The **Settings** menu now also shows a direct link (Questions & Support) to the XUMM Support xApp.
* Added resolving **FIO handles** in the manual Send flow.
* Support for the XRP Ledger **Devnet** (Mainnet & Testnet were already present, Devnet has now been added).

#### **Improved in 2.2.6**

* After running tests on required fees, the **medium** fee is low lower than before. The **low** and **high** fee are unchanged. **Fees are based on values advertised by XRP Ledger nodes. Transaction fees do not go to the creators of XUMM: they are burned by the XRP Ledger.**
* Token balance rounding has been improved (home screen). An amount of e.g. 7.9999 will now show 7.99 instead of 8.00.
* Trust Lines **without** balance and with a **zero** limit are now displayed if they are in **non default state**, meaning they still claim a reserve. This means they can they can be cleaned up easily by tapping the Trust Line and using the Remove button.
* When adding a TrustLine from the **Add** panel, XUMM will now show a warning if the selected TrustLine (token, issuer) is already present in your TrustLine list.
* Improved QR scanning results in faster scanning on iOS, and fixes QR scanning problems for some Android users.
* The ‘preflight’ checks on **Account Delete** transactions have been improved. This makes it less likely that one is allowed to proceed with an Account Delete when the XRP Ledger will most likely reject. This precents the XRP Ledger Account Delete fee to be burned for an unsuccessful delete.
* Better displaying of the amounts resulting in a **negative spendable account balance** in the **Explain** panel (next to your balance, on the XUMM home screen).
* The **Return payment** button (Event details screen) will now no longer show for tokens one doesn’t own anymore.
* Asynchronously exuted Decentralized Exchange trades on your **limit order** will now no longer show the **From** field on the Event detail page: the **From** field used to display the initiator of the trade (counterparty). As this is usually an unknown other XRP Ledger account, this was confusing.
* Transactions failing with a **tef**\* (fatal) error code will now result in the transaction error screen straight away, instead of waiting for a while to see if the transaction ended up in newly closed ledgers.

#### **Fixed in 2.2.6**

* Signing a transaction sometimes resulted in a **LastLedgerSequence** error. This happened when more than 40 seconds were spent between viewing a sign request and actually signing the transaction. We significantly increased this time-out time.
* When sending a token you issued yourself, the Send flow will no longer show the **No liquidity** message, as liquidity is irrelevant if you are the issuer.
* When exchanging tokens using the **Exchange** feature (after tapping a Trust Line) an error message could appear (referring to the Session Logs). This would happen for low value tokens, due to a rounding (decimal precision) error.
* An account would be displayed as **Blackholed** if a regular key was set to a known Blackhole account address. If the master key of that account wasn’t disabled, the account technically wasn’t blackholed. XUMM now checks for **both** a known Blackhole account address & a disabled master key to show an account as Blackholed.
* When using the **backspace** button on **Android** in an **amount field**, the cursor position could behave weirdly.
