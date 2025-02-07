---
description: Learn how much rep you can earn by doing different actions on PWN.
---

# Reputation Points

## Borrow and Lend

The most straightforward way to earn reps is by borrowing from or lending on PWN. In essence, lenders earn 1 rep for every $100 lent and borrowers earn 1 rep for every $100 borrowed for 30 days. The longer the loan duration, the more rep you get.&#x20;

<table><thead><tr><th width="400">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Lend on PWN (awarded on loan repayment or default)</td><td>1 rep per $100 of credit</td></tr><tr><td>Borrow on PWN (awarded on loan repayment)</td><td>1 rep per $100 of credit and interest</td></tr><tr><td>Have a running loan</td><td>+10% Boost</td></tr></tbody></table>

However, to account for the actual duration of the loan before it ends (including early repayment), the final reward is calculated using the following formula:

$$
REP = \frac{V}{100}*\frac{12}{365}*D
$$

* **REP** – Calculated as 1 rep for every $100 lent or borrowed for 30 days
* **D** – The final loan duration in days
* **V** – The cumulative loan volume in $

{% hint style="info" %}
The dollar value of the credit is determined at the moment of loan creation, and reps are calculated based on this value.
{% endhint %}

| Scenario  | Result                                                                                                                                                                                                                                     |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Repayment | Both the lender and borrower earn rep points based on the loan principal, interest, and duration.                                                                                                                                          |
| Default   | <p></p><p>Here’s a refined version for clarity and consistency:</p><ul><li>The lender earns rep points based only on the principal and loan duration.</li><li>The borrower does not receive any rep points for a defaulted loan.</li></ul> |

### Example scenario

Mark wants to use $100,000 worth of $ABC as collateral to borrow 5,000 USDC for 30 days with a fixed 10% interest.\
James agrees to lend 5,000 USDC to Mark and accepts his proposal.

**Reward Accrual:**

* Mark earns rep points based on the 5,000 USDC loan amount and 500 USDC interest. He will receive **55 reps** upon full repayment.
* James earns rep points based on the 5,000 USDC he lent and will receive **50 reps** when funding the loan.

**Possible Outcomes:**

1. **Default:** If Mark fails to repay, James keeps his earned rewards and can claim the $ABC collateral.
2. **Early Repayment (14 Days):** If Mark repays the loan early after 14 days, final reps are calculated using the extended formula.
   * Mark earns **25.32 reps**
   * James earns **23.01 reps**
3. **Full-Term Repayment (30 Days):**
   * Mark earns **55 reps**
   * James earns **50 reps**

***

## Claimable Reputation

<table><thead><tr><th width="393">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Have a Basename</td><td>15 rep</td></tr><tr><td>Setup PUSH notifications</td><td>10 rep</td></tr><tr><td>Have a deposit in Aave</td><td>1 rep per $1,000 of deposit</td></tr></tbody></table>

***

## Protocol

<table><thead><tr><th width="442">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Make an Offer</td><td>15 rep</td></tr><tr><td>Have your Lending Offer accepted</td><td>20 rep</td></tr><tr><td>Have your Borrowing Offer accepted</td><td>20 rep</td></tr><tr><td>Accept a Lending Offer</td><td>20 rep</td></tr><tr><td>Accept a Borrowing Offer</td><td>20 rep</td></tr><tr><td>Repay your loan</td><td>10 rep</td></tr><tr><td>Claim loan repayment or collateral</td><td>10 rep</td></tr><tr><td>Revoke your Offer</td><td>10 rep</td></tr></tbody></table>

***

## Ecosystem

<table><thead><tr><th width="442">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Follow PWN on Farcaster</td><td>10 rep</td></tr><tr><td>Setup PUSH notifications</td><td>15 rep</td></tr><tr><td>Setup Discord notifications</td><td>15 rep</td></tr><tr><td>Setup Email notifications</td><td>15 rep</td></tr><tr><td>Have an ENS</td><td>+2.5% Boost</td></tr></tbody></table>

***

## PWN Bundler

<table><thead><tr><th width="442">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Create a PWN Bundle</td><td>15 rep</td></tr><tr><td>Unwrap a PWN Bundle</td><td>10 rep</td></tr><tr><td>Use PWN Bundle as a collateral</td><td>10 rep</td></tr></tbody></table>

***

## PWN Safe

<table><thead><tr><th width="442">Action</th><th>Rewards</th></tr></thead><tbody><tr><td>Deploy PWN Safe</td><td>10 rep</td></tr><tr><td>Mint an ATR Token</td><td>15 rep</td></tr><tr><td>Burn an ATR Token</td><td>10 rep</td></tr><tr><td>Use ATR Token as a collateral</td><td>10 rep</td></tr></tbody></table>
