---
description: How to borrow on PWN?
---

# Taking out a loan

Taking out a loan is one of the most common interactions with PWN. Throughout this guide, **we will guide you through the process of taking out a loan using the PWN platform**.

Let's define a few terms before we start:

* **PWN protocol** - Decentralised and permissionless layer of PWN
* **PWN platform** - Web application we will be using in this guide

{% hint style="info" %}
This tutorial assumes you are logged in PWN platform with your web3 wallet like metamask. If you have any problems doing that, don't hesitate to contact us on our [discord](https://discord.gg/8WHnTj9HPn).
{% endhint %}

This guide will is divided into three parts:

* Signalling a desire to take out a loan
* Accepting an offer from a lender
* Cancelling your signal

### Signalling a desire to take out a loan

First, you need to tell lenders you want a loan. We call this process signalling a desire to take a loan.&#x20;

Let's start by going to the _Borrow_ page. Assuming you want to take out a loan, click _Start borrowing_.&#x20;

Now you need to specify an asset which you want to borrow. You have the option to choose any token which is compatible with the ERC-20 standard. Note that lenders have the option to offer you a different asset than your desired one.&#x20;

After choosing your prefered asset, specify the amount you want to borrow and the desired loan duration, then click _Confirm loan terms_.

The second step is choosing an asset you want to use as collateral for your loan. This asset can be an NFT conference ticket, a small-cap token or any other token which follows ERC-721, ERC-1155 or ERC-20 standards. If you don't specify the amount of the asset, the maximum amount will be used. Now click _Continue_.

The last step is to check everything. Be sure to double-check you're interacting with a genuine asset and to read the _terms and conditions_. If everything checks out, you can _Submit Loan Request_.

### Accepting an offer from a lender

After requesting a loan, lenders can make you offers. You can see these offers in the _Offers_ section on the loan page.&#x20;

{% hint style="info" %}
You can find all your loans on the _My Dashboard_ page.&#x20;
{% endhint %}

If you like an offer, you can accept it. Click the _accept_ button.&#x20;

Before making the final transaction and accepting the offer, you will be prompted by your web3 wallet to approve your collateral to the PWN Vault smart contract. This approval will give PWN Vault permission to transfer your collateral, which is needed to create the loan.&#x20;

{% hint style="success" %}
Note that this process is entirely trustless, and PWN AG (the company) can't move your assets.
{% endhint %}

If you make all the approvals needed, you can now accept the offer you choose by clicking the _Accept offer_ button and signing the final transaction.&#x20;

### Cancelling your signal

In case you want to cancel your loan request, just click the _Revoke Loan_ button on the loan page, and you're done.&#x20;
