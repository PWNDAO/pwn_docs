# FAQ

### What's PWN?&#x20;

PWN is a permissionless, peer-to-peer lending protocol. In other words, it lets borrowers and lenders agree on loan terms, backed by any collateral. PWN doesn't whitelist the assets used on the protocol;  as long as they conform to the ERC-20, 721, or 1155 standards, they can be PWNed.

PWN is oracle-less, which means that borrowers aren't exposed to asset price fluctuation and auto-liquidations. As long as you repay your loan plus interest on time, your collateral is returned to you.&#x20;

PWN also keeps costly on-chain interactions to the minimum. Users can post gas-less loan requests and offers off-chain. You pay gas only when a deal is finalized or when you cancel a loan request/offer.&#x20;

### What's the interest in borrowing vs. selling and buying?

By borrowing, you stay exposed to your asset. If it's a yield-bearing token (vault token or LST/LRT), you can collect interest that will offset the interest paid on your loan. Borrowing can unlock leverage strategies and the capital you need to seize profitable DeFi opportunities.\
\
Depending on your country and jurisdiction, selling assets may be a taxable event, whereas borrowing may not be. Please refer to a local tax professional for tax advice.&#x20;

### Why is a P2P Lending Architecture Better?

* **Flexibility in Asset Handling**: P2P lending platforms can support a broader range of assets, including those that require Know Your Customer (KYC) compliance. This flexibility allows for the inclusion of both traditional and digital assets, accommodating a wide array of borrower needs and investment opportunities.
* **Customized Loan Agreements**: P2P lending enables borrowers and lenders to select their counterparts based on individual criteria and preferences. This flexibility ensures more tailored loan agreements, enhancing satisfaction and trust between parties.
* **Enhanced User Experience without Systemic Risks**: P2P lending platforms can offer a user experience that matches pooled solutions while avoiding the systemic risks associated with pooling. This approach ensures a seamless and secure experience for users, promoting trust and long-term engagement.
* **Flexible Loan Terms**: Without reliance on oracles, P2P lending platforms can offer greater flexibility in setting loan terms. This independence allows for more customized and adaptable loan conditions, catering to the specific needs of borrowers and lenders.
* **Enhanced Composability in DeFi**: A fully permissionless P2P lending platform enhances composability within the DeFi ecosystem. By accommodating a wide range of assets and enabling seamless integration with other DeFi protocols, the platform supports innovation and expansion within the DeFi space.
* **Improved Compliance** : Yield in P2P lending comes from a single borrower address.This transparency ensures that the origin of returns is clear, fostering confidence and facilitating compliance with regulatory requirements.

### What makes PWN different from other lending protocols?

PWN lets you use **any asset or bundle of assets as collatera**l (ERC-20s, NFTs) and choose your loan terms (interest, duration, LTV, borrowed asset, etc.). PWN guarantees total predictability for the whole loan duration: what you sign for will always be what you get, regardless of asset price fluctuations.

Being oracle-less, PWN also protects you from price-based liquidation. The only way to lose your collateral is by not repaying your principal and interest by the time the loan expires.

### **On which chains is PWN deployed?**

PWN is deployed on Ethereum, Polygon, Arbitrum, Optimism, Base , Binance Smart Chain, and Cronos.

### How can I use PWN as a borrower?&#x20;

Simply create a loan request by selecting the token (or bundle of tokens) you'd like to use as collateral, the asset and amount you'd like to borrow, as well as the loan terms that fit your strategy (APR, LTV, duration, etc.). Posting a borrowing proposal on PWN doesn't cost gas.&#x20;

Lenders can create loan offers for an NFT collection or a specific token. If you own that specific asset, you're free to accept the loan offer if the terms seem fair to you.&#x20;

For a detailed step-by-step, [check out our guide](guides/borrowing-on-pwn/).

### How can I use PWN as a lender?&#x20;

You can browse the posted borrowing proposals and pick one(s) you'd like to fund. You can also post counter-offers, adjusting the loan parameters as you wish (interest, asset borrowed, loan duration). If a borrower accepts your offer, you're in business.&#x20;

You can also go for a more proactive approach by posting lending proposals on collateral you'd feel comfortable lending against (tokens, NFT collections).

In the event of a default, you can simply claim the collateral previously locked in PWN's escrow contract. \
\
For a detailed step-by-step, [check out our guide](guides/lending-on-pwn/).

### How should I choose my borrowing terms?

This decision is entirely yours, but there are few rules of thumb to keep in mind:

* Don't push the LTV too high, especially if your collateral is relatively illiquid or volatile
* Offer a competitive interest rate; if the lender can find better rates elsewhere, the odds of being funded are lower.

### What does the PWN Bundler do?

The PWN Bundler is one of PWN's unique feature. It lets you combine multiple assets (NFTs and ERC-20s) into one to use as collateral on the platform. Your bundle's appraisal is be the sum of all the underlying assets.

### Does PWN charge any fees? How much gas do I need to pay?&#x20;

PWN does not currently charge any fees, but we plan to do so in the future.&#x20;

You only pay gas when accepting an offer as a borrower, cancelling an offer as a lender, or approving assets to be used as collateral. Repaying a loan and claiming repayment or defaulted collateral also require an on-chain transaction.

### Is there a PWN token?&#x20;

Learn more about PWN token in the [DAO Whitepaper](https://pwn.xyz/dao-whitepaper.pdf) and [PWN DAO](https://docs.pwn.xyz/pwn-dao/pwn-dao) section.

### Is PWN audited?

Yes, PWN has been audited twice. You can find the reports [here](https://dev-docs.pwn.xyz/more-documentation/audits/pwn-v1-audits).
