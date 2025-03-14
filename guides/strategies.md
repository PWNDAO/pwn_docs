---
coverY: 0
---

# Strategies

Strategy-Based Lending is a flexible, peer-to-peer (P2P) lending solution introduced by PWN. It allows lenders to create generalized lending commitments—referred to as [**Strategies**](https://app.pwn.xyz/#/strategies). These strategies streamline the lending process while enabling the use of diverse asset classes as collateral.

### 1. Context: Challenges of P2P Lending

P2P lending, while flexible for unique and complex assets, can be difficult to scale. Lending pools have become popular for liquid assets, but they constrain the types of collateral that can be used and rely heavily on liquidation mechanisms. In reaction, there’s growing demand for:

* **Fixed-rate loans without liquidations** (Lombard loans).
* **More complex collateral assets**, such as LP tokens, DeFi derivatives, and synthetic assets.

Strategy-Based Lending addresses these issues by simplifying the creation of lending offers while maintaining the advantages of P2P flexibility and composability.\
\
[Read more.](https://pwn.mirror.xyz/PT8V0Ctux_HmjyrcG3-Xwiy6JvBIp-j-pY3hq27wjUw)

### 2. The Strategy-Based Lending Model

#### 2.1 Overview

**Strategies** enable curators to set up predefined lending commitments across multiple collateral assets, allowing users to participate simply by deploying one or more of the chosen credit assets.&#x20;

This is akin to a “copy-lending” feature, allowing lenders to adopt successful strategies without manual configuration.

#### 2.2 How it Works

A **Lending Strategy** is created by a **Curator.** Curators set competitive market parameters that other lenders can subscribe to, simplifying the process for the broader user base:

* **Collateral assets**: The assets that borrowers can pledge, such as standard tokens, liquid-staking derivatives, LP positions or even NFTs.
* **Credit assets**: The funding sources (stablecoins, ETH...).
* **Loan Terms**: LTV ratio, APR, and duration.
* **Allocation**: The distribution of available credit across various collateral assets in a strategy.

_At the moment, strategy creation is permissioned, meaning only approved curators can create strategies._&#x20;

**Example Strategy:**

* "Lend against any ETH liquid staking derivative at 70-80% LTV with 4% APR for 60 days, using stablecoins on multiple chains."

#### 2.3 Key Benefits

* **Simplicity:** Lenders avoid the complexity of crafting individual offers, increasing efficiency.
* **Expertise:** Risk analysis and term-setting are delegated to experts, minimizing information asymmetry.
* **Flexibility:** Allows the use of complex and illiquid assets that traditional pools cannot handle.
* **Composability:** Integrates a broad range of DeFi assets into the P2P lending framework.

### 3. Lending Via Strategies

#### Click on Strategies in the header:

<figure><img src="../.gitbook/assets/Screenshot 2025-03-14 at 15.02.36.png" alt=""><figcaption></figcaption></figure>

Hover over a strategy you're interested in and click to show more information

<figure><img src="../.gitbook/assets/Screenshot 2025-03-14 at 15.07.00 (1).png" alt=""><figcaption></figcaption></figure>

Each strategy page will display a comprehensive view of lending terms, along with a complete list of eligible collateral and credit assets.&#x20;

Once you've found the right strategy, simply click **"Borrow"** or **"Supply"** button.

<figure><img src="../.gitbook/assets/Screenshot 2025-03-14 at 15.09.57.png" alt=""><figcaption></figcaption></figure>

**Supply**

In the modal, select the assets and amounts you wish to Supply, then click "**Confirm**." Note that you're free to commit a single asset or multiple assets.

_NB: The asset(s) you've committed will be used to generate offers for each collateral in the strategy, following the pre-set allocation._

<figure><img src="../.gitbook/assets/Screenshot 2025-03-14 at 15.18.05.png" alt=""><figcaption></figcaption></figure>

**Borrow**

In the modal, adjust the amounts you wish to Borrow, then click the "**Borrow**" button.&#x20;

<figure><img src="../.gitbook/assets/screencapture-strategies-2025-03-14-15_18_53.png" alt=""><figcaption></figcaption></figure>



**Approve in your wallet of choice and you're done!**

Borrowers will now see your offers that match the strategy you've committed to. They can use the collateral assets they own to accept these offers.&#x20;

To view and manage all your active offers, go to your [Dashboard](https://app.pwn.xyz/#/dashboard).\
\
All offers pushed via Strategies will be accessible in the [Market](https://app.pwn.xyz/offers/borrow) section of PWN app.

