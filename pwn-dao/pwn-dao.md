# PWN DAO

## 1. Introduction

PWN DAO is designed to manage and enhance the PWN Protocol, providing decentralized governance over advanced DeFi lending instruments such as non-custodial collateralized loans and contracts. This section outlines PWNDAO's governance model, tokenomics, and key features.

## 2. PWN Protocol Overview

PWN Protocol facilitates peer-to-peer, non-custodial, fixed-term loans. Key features include:

* Permissionless selection of credit and collateral assets.
* Fixed yield.
* Customizable loan terms.
* Oracle-less design.
* No price-based liquidations.
* Secondary transfer of lender rights via ERC721 LOAN tokens.

Additional features include multi-commitment proposals (strategies), elastic proposals, lean liquidity lending, and more to come.

## 3. Governance Model

### **3.1 Governance Structure**

PWNDAO operates under a **dual governance model**, balancing decentralized decision-making with fast execution for urgent proposals. The system is divided into two key governance mechanisms:

* **Community Governance:** All token holders who stake $PWN tokens can participate in governance. Proposals made under this system require a quorum of 20% of staked tokens and must achieve a 60% approval rate to pass.
* **Steward Governance:** Stewards, appointed by the community, have the authority to make decisions using a multi-signature mechanism. Steward proposals are automatically implemented unless vetoed by at least 10% of the total voting power.

This dual system ensures that the DAO remains efficient, while providing security and fairness through collective decision-making.

### **3.2 Roles and Responsibilities**

* **PWN Token Holders:** $PWN token holders play a vital role in governance by staking their tokens to participate in voting and propose changes. Staking grants them governance power in the form of voting weight represented by vePWN.
* **Stewards:** A group of community-appointed individuals who can submit optimistic proposals that can be vetoed by community. They act as operational leaders of the DAO, responsible for day-to-day governance actions.
* **Proposal Creators:** Any token holder with at least 1 voting power can submit a proposal. Alternatively, stewards can submit proposals directly.
* **Voters:** All stakers can participate in voting on proposals. Rewards are given to voters who actively participate in the decision-making process.
* **Veto Power:** Token holders can veto decisions made by stewards if they collectively hold at least 10% of the voting power.

### **3.3 Proposal Lifecycle**

1. **Proposal Submission:** Proposals are submitted by either stakers or stewards. Each proposal must be clearly outlined with a detailed description and execution steps.
2. **Discussion Period:** After submission, the proposal enters a public discussion phase where community members can debate the merits of the proposal. This stage encourages transparent and well-informed decision-making.
3. **Voting Phase:** Once the discussion period ends, the proposal moves to a vote. For collective governance, a quorum of 20% of voting power must be reached, and at least 60% approval is required for the proposal to pass. Steward proposals do not require a vote, but can be vetoed.
4. **Veto Period:** For steward proposals, there is a 3-day period during which token holders can veto the decision by collectively gathering at least 10% of voting power. If no veto occurs, the proposal passes.
5. **Execution:** Once approved or not vetoed, the proposal is executed. The execution can include changes to the protocol, treasury management, or other governance matters.

### **3.4 Voter Incentives**

To encourage participation and reduce voter apathy, PWNDAO offers a voter incentive system. Voters who support successful proposals can earn rewards in newly minted $PWN tokens, proportional to the voting power they used. On the other hand, non-participation in governance may lead to inflationary penalties or reduced voting rewards over time.

### **3.5 Staking and Voting Power**

$PWN token holders must stake their tokens to gain governance power. The voting power granted is determined by the amount and remaining lock up of the stake:

* The longer the remaining lock up period, the higher the multiplier (up to 3.5x for a 10-year commitment).

<table data-header-hidden><thead><tr><th width="138"></th><th></th><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td>Years</td><td><strong>1</strong></td><td><strong>2</strong></td><td><strong>3</strong></td><td><strong>4</strong></td><td><strong>5</strong></td><td><strong>10</strong></td></tr><tr><td>Multiplier</td><td>1</td><td>1.15</td><td>1.3</td><td>1.5</td><td>1.75</td><td>3.5</td></tr></tbody></table>

* Voting power decays as the staking commitment matures.

{% hint style="info" %}
Example: Alice locks up 100 $PWN for 3.5 years, gaining an initial voting power of 150 due to the 1.5x multiplier. After 0.5 years, her voting power decreases to 130 as the lockup period progresses. After 1 year, her power reduces further to 115, and in the final year, it reaches 100—matching her original staked amount. Once the lockup period ends, she has no voting power left and must re-stake her tokens to regain governance power.
{% endhint %}

Voting power is recalculated at the start of each **4-week epoch**, and all staking actions—such as locking tokens or unstaking—only take effect in the following epoch, not the current one.

## 4. PWN Token(s) and Treasury

### **4.1 Tokens**

* **$PWN Token (PWN):** The native governance token of the DAO.
* **StakedPWN (stPWN):** An NFT representing staked $PWN tokens. These tokens are non-transferable unless governance enables their transferability.
* **VoteEscrowedPWN (vePWN):** A non-transferable token that represents the voting power of staked $PWN, determined by the duration of the stake.

### **4.2 Treasury and Fee Management**

PWNDAO’s treasury is funded by protocol fees collected from loans. Initially, loan fees are set to 0%, but the DAO can adjust these fees over time based on market conditions.

Treasury funds are managed and allocated through governance decisions, including protocol upgrades, ecosystem development, or community rewards.

## 5. DAO Infrastructure

PWNDAO utilizes the [**Aragon OSx**](https://aragon.org/aragonosx) framework to implement decentralized governance. PWNDAO is initially deployed on Ethereum, with plans for multi-chain governance supported by a bridge timelock mechanism to ensure secure cross-chain voting and execution.
