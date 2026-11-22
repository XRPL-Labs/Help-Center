---
description: How to Send XRP from eToro to Xaman (deposit)
---

# How to Send XRP from eToro

Transferring XRP from eToro to an external XRP Ledger (XRPL) account is a **two-phase process**. eToro does not permit direct withdrawals to an external wallet address straight from its main trading platform; you **must** first move the position to their "eToro Money" crypto wallet app.

### Before you start

* A fully verified eToro account
* The eToro Money app downloaded and linked to your eToro account
* Your external XRPL **r-address** (starts with `r...`)
* New, unactivated XRPL accounts require an activation reserve of **1 XRP** to exist on-chain

### Phase 1: Transfer XRP from eToro to eToro Money

1.  Log into the main eToro trading app or web platform and go to the **Portfolio** tab.

    !\[eToro Portfolio — XRP position]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-12b7a5f3-d7d6-4cda-afb4-86007c93d891.jpg =300x)
2. Click on **Ripple (XRP)** to view your open positions.
3.  Click on the specific open XRP position you wish to move. In the **Edit Trade** window, select **Transfer to Wallet**.

    !\[Edit Trade — Transfer to Wallet]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-33dd35e2-1ed0-446d-adaf-527792bd9d4b.jpg =300x)
4. Review the transfer details. eToro charges a transfer fee (typically 2% of the transaction, minimum $1, maximum $100).
5.  Click **Transfer to eToro Crypto Wallet**. The position will show as **Pending Transfer** until eToro processes and approves the request. Processing times can range from a few hours up to several business days.

    !\[Transfer confirmation]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-c5db498a-f3d7-4cf8-be7a-a6bcac88c0b1.jpg =300x)

> **Note:** Moving XRP from your eToro portfolio to eToro Money is generally irreversible as a trading position. The asset transitions into standard crypto ownership. eToro has rolled out wallet-to-portfolio returns for select assets, but this is not guaranteed for all.

### Phase 2: Send XRP from eToro Money to your XRPL account

1.  Open the **eToro Money** app and log in. Go to the **Wallet** tab, find **XRP**, and tap **Send**.

    !\[eToro Money Wallet — XRP Send]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-656a8736-ba31-47e8-8f43-c23eb3b23c0e.jpg =300x)
2. Enter the **amount** of XRP you wish to send.
3. Paste your external XRPL **r-address** into the **Address** field.
4.  Enter a value in the **Destination Tag (dt)** field. If you are sending to a self-custody wallet (Xaman, Ledger, Trezor), enter **123456**. If you are sending to a centralized exchange, enter the destination tag provided by that exchange.

    !\[Address and Destination Tag]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-5bbb447a-984b-4126-957b-b21483505c80.jpg =300x)

    > **Why a Destination Tag?** eToro's address validation may reject a plain r-address with an _"Address does not match chain"_ error. Entering a Destination Tag resolves this. For self-custody wallets the tag is not used by the receiving wallet, so any non-zero value (such as 123456) is safe.
5. Tap **Send**.
6.  eToro will ask for more information. Select **Self hosted wallet** (if sending to Xaman, Ledger, Trezor, etc.) or **A centralized exchange** (if sending to Coinbase, Kraken, etc.), then tap **Continue**.

    !\[Self hosted wallet selection]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-9c685557-4d1c-4a7b-a016-722fe8564d74.jpg =300x)
7. Under **Verify the recipient**, confirm the destination address is correct, then select **Self-Declaration** under the Wallet section.
8. Under **Recipient**, select **Myself** and tap **Continue**.
9.  Enter the **SMS verification code** sent to your phone to authorise the transaction.

    !\[SMS verification]\(https://support-cdn.xumm.pro/cdn-cgi/image/quality=75/image-7e328084-f4e5-4228-9ea2-712d7a209dba.jpg =300x)

Your XRP will arrive in your XRPL account shortly.

### Things to keep in mind

* **Fees:** eToro Money charges 0% wallet operator fee for XRP sends. The only cost is the network fee (typically 0.000045 XRP). The Phase 1 portfolio-to-wallet transfer carries a separate 2% eToro fee.
* **Maximum per transaction:** Approximately $50,000 (33,297 XRP at current rates). Additional limits may apply.
* **eToro's initial balance reserve:** eToro Money keeps a small amount of XRP in the wallet to maintain the XRPL account reserve. This amount is not available to send.
* **Irreversible:** Once confirmed, the on-chain transfer cannot be reversed. Double-check the address before tapping Send.
