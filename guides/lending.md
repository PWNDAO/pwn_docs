---
description: How to lend tokens on PWN?
---

# Lending

**This guide will walk you through the process of lending using the** [**PWN platform**](https://app.pwn.xyz/).

Let's define a few terms before we start:

* **PWN protocol** - Decentralised and permissionless layer of PWN
* **PWN platform** - Web application we will be using in this guide

{% hint style="info" %}
This tutorial assumes you are logged in PWN platform with your web3 wallet like metamask. If you have any problems doing that, don't hesitate to contact us on our [discord](https://discord.gg/8WHnTj9HPn).
{% endhint %}

This guide is divided into three parts:

* Making an offer
* Revoking an offer
* Claiming repaid amount or defaulted collateral

### Making an offer

Assuming you found a suitable loan request on the PWN platform, you have to create an offer which the borrower can accept. To create an offer, scroll down to the bottom of the page or click the _Create offer_ button.&#x20;

First of all, fill out the _Credit offered_ field. You may offer any ERC-20 token which you hold in your wallet.&#x20;

Second, you will have to tell the borrower how much you want him to pay back. You can either specify the _Repayment_ amount or specify the _Interest rate,_ and the PWN platform will calculate the _Repayment_ amount for you.&#x20;

Now specify the _Duration_ of the loan and set the _Offer expiration_. Note that you can revoke the offer anytime before the _Offer expiration_ date.

The only thing left before making the offer is to _Approve_ the offered tokens to the PWN Vault smart contract. You may not have to do this if you've ever made an offer with the same token before.&#x20;

After approving the offered asset, you will be prompted by your web3 wallet to sign the final offer.&#x20;

### Revoking an offer

If you wish to revoke your offer, go to the page of the loan request you've made your offer to. In the _Offers_ section, find your offer and click _cancel offer_. You will be prompted by your web3 wallet to make an on-chain transaction which will revoke your offer.

{% hint style="info" %}
You can find offers you've made on the _My Dashboard_ page.&#x20;
{% endhint %}

### Claiming repaid amount or defaulted collateral

When the borrower repays his loan, you can claim the repaid amount on the _My Dashboard_ page or on the loan page by clicking the _Claim repayment_ button. You will be prompted by your web3 wallet to make an on-chain transaction which will claim the repaid tokens.&#x20;

In case of a default, the process is exactly the same. Just click the _Claim collateral_ button and confirm the on-chain claim transaction in your web3 wallet.&#x20;
