---
description: Delete an NFT using XRPL.Services Raw JSO
---

# NFT Burn Process

```
// NOT Intended for general use 

```

> The `NFTokenBurn` transaction is used to remove a `NFToken` object from the `NFTokenPage` in which it is being held, effectively removing the token from the ledger (_burning_ it).



Reference: [https://xrpl.org/nftokenburn.html](https://xrpl.org/nftokenburn.html)

Resource: [https://xrpl.services/tools](https://xrpl.services/tools)

Requirements;

* Must be NFT Owner

Or

* if the `NFToken` has the `lsfBurnable` flag enabled
  * can be the issuer
  * or the issuer's authorized [`NFTokenMinter` ](https://xrpl.org/nftoken-authorized-minting.html)account instead

1. Sign in to XRPL.Services with the account that owns the NFT

![](<../../.gitbook/assets/image (7) (3).png>)

Navigate to _XRPL Tools > Raw JSON Transactions > NFTokenBurn Template_

Update the field values to match the requirements of your transaction as follows;

<table data-header-hidden><thead><tr><th width="131"></th><th></th></tr></thead><tbody><tr><td>Field</td><td>Description</td></tr><tr><td><code>Account</code></td><td><em>(Required)</em> The unique address of the <a href="https://xrpl.org/accounts.html">account</a> initiating the transaction.</td></tr><tr><td>Owner</td><td>Optional) The owner of the NFToken to burn. Only used if that owner is different than the account sending this transaction.</td></tr><tr><td>NFTokenID</td><td><em>(Required)</em> The NFToken to be removed by this transaction.</td></tr></tbody></table>

N.B. The "Sequence" and "Fee" fields are not present since XUMM will take care of this!

```json
{
  "TransactionType": "NFTokenBurn",
  "Account": "rNCFjv8Ek5oDrNiMJ3pw6eLLFtMjZLJnf2",
  "Owner": "rvYAfWj5gh67oV6fW32ZzP3Aw4Eubs59B", //Optional
  "NFTokenID": "000B013A95F14B0044F78A264E41713C64B5F89242540EE208C3098E00000D65"
}
```

Submit the transaction to Xumm via the button under the code

![](<../../.gitbook/assets/image (3) (6).png>)

Update the Memo if necessary and select Confirm

![](<../../.gitbook/assets/image (5) (2).png>)

A QR Code screen appears

![](<../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)

In Xumm, either respond to the notification or scan the QR code to bring up the transaction&#x20;

Slide to Accept

Sign the transaction

Success or;

### Error Cases <a href="#error-cases" id="error-cases"></a>

Besides errors that can occur for all transactions, NFTokenBurn transactions can result in the following [transaction result codes](https://xrpl.org/transaction-results.html):

| Error Code         | Description                                                                                                     |
| ------------------ | --------------------------------------------------------------------------------------------------------------- |
| `temDISABLED`      | The [NonFungibleTokensV1 amendment](https://xrpl.org/known-amendments.html#nonfungibletokensv1) is not enabled. |
| `tecNO_ENTRY`      | The specified `TokenID` was not found.                                                                          |
| `tecNO_PERMISSION` | The account does not have permission to burn the token.                                                         |
