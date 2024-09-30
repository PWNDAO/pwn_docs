# Advanced Lending Features

#### &#x20;**Multi-Asset Commitment (stablecoins)**

This feature allows lenders to offer multiple credit assets against a single collateral (the feature is limited to major stablecoins at the moment). Borrowers can then choose the asset that best suits their needs. This feature is currently limited to stablecoins.

Important Notes:

Once a proposal is accepted, the other ones are no longer acceptable.\
\
If part of one credit asset is moved or spent while a multi-asset proposal is active, that particular asset will no longer be available for borrowing, but the other assets in the proposal will remain unaffected.

_Example_:

_Mark is willing to lend $1,000 at a 10% APR and 50% Loan-to-Value (LTV) ratio against ETH. He holds the equivalent amount in USDC, USDT, and DAI. Using the multi-asset commitment feature, he can create a lending proposal that includes all three stablecoins._

_Any borrower interested in Mark’s terms can choose which stablecoin to borrow. Once a borrower accepts USDC, the DAI and USDT options will no longer be available, and only the active USDC loan will appear in the lender's dashboard._

#### **Elastic Proposals**

Elastic proposals allow lenders to create flexible offers that can be accepted by multiple borrowers. Think of it as your personal pool that multiple borrowers can draw from until liquidity dries out.\
\
To avoid being split between too many active loans, lenders are free to set a miniumum borrowed amount for their elastic proposals.

Important Note:

If part of the credit asset is removed during an active elastic proposal, it may invalidate the proposal if a borrower is trying to borrow more than the remaining balance. However, loans already accepted will not be affected.

_Example:_

_Mark creates an elastic lending proposal offering 1,000 DAI, with ETH as collateral at a 50% LTV ratio._ &#x20;

_- User 1 borrows 500 DAI._ &#x20;

_- User 2 borrows 200 DAI._ &#x20;

_- User 3 borrows 300 DAI._

_As a result, Mark now has three open loans, all stemming from the same proposal._
