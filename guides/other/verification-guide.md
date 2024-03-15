---
description: How to verify assets?
---

# Verification Guide

Welcome to the PWN Verification Guide! This document will show you how to identify legitimate assets and spot scams.

Before we get to the guide, we must make something clear: The fact that an asset is verified doesn’t mean that it’s valuable. Yes, you might be interacting with a genuine asset, but that doesn’t say anything about its underlying value. Keep that in mind before accepting any offer.&#x20;

### Verifying token contract addresses

We must ensure that a token’s contract address is correct. This verification is especially important, as even official sources can be hacked, and the people you trust can have their accounts compromised. That’s why you should never solely rely on one source.

### NFTs

When it comes to verifying NFTs, first take a look for the official sources – be it Twitter, the project’s website, or its official Discord server.

You should be able to find a link to the token on NFT marketplaces like OpenSea, LooksRare or Foundation. You can see the collection’s contract address on these marketplaces in the asset details section.

<figure><img src="https://lh4.googleusercontent.com/yTGHWptwqnO_1vnPRLCCYeN-exK1h9fn_nHRYMXgBfrchV1xyig7brcAZnIFhUxlivicMMMrz8ozMnpLZOwKX-f6tOPtZd4yBzUVwrke2kZDJtMiynXSvuxJG99Z7hO__jzyq-wpl7FCOWYe1RRePDaJJPI5Pgmr2d6iMkKg1veXc5ftCEQ9HOIF" alt=""><figcaption></figcaption></figure>

Clicking on the address in the detail section will redirect you to the Etherscan website. The same thing will happen when you click on the address shown in the detail section of the PWN asset page. On Etherscan, you can quickly compare the addresses and see if they match.

### Fungible tokens

There’s a website called [tokensniffer.com](https://tokensniffer.com/) which can help you analyze an ERC-20 token in detail. You can copy the token address from the PWN asset page and search for that address on Token Sniffer, which will analyze the token and generate a security report for you. If the token you’re dealing with is a scam, Token Sniffer will be able to tell you.

<figure><img src="https://lh6.googleusercontent.com/Apu2RAjflzqmosYoWqR8AIcrTppPX2e_4JQO_gv0UAv_UTVVzwyvPFNtlQCR5iiRIoGJ_I6pfjZY9hsOEMZAQpjuHDGQTe35aQcKSQOtLU1sVVN2nk9RTmfa5_qbH_17bLDjKR240nSCcm67o1qcCwhogZ6US1ypUSx89o-EbNK6hf5Z_iSF51Do" alt=""><figcaption></figcaption></figure>

It’s important to be aware of the fact that even if the warning notification shown above isn’t present, it doesn’t necessarily mean that you’re dealing with a genuine token. Another critical thing to check here is the token’s liquidity. Genuine tokens will usually have at least a few ethers in liquidity or, ideally, much more than that.

### Etherscan comments

Etherscan provides a convenient comments feature. Using it, it’s possible for anyone to write comments to specific addresses that may help identify a scam contract. When you click on the contract address on the PWN asset page, you will be redirected to that contract’s Etherscan page.

<figure><img src="https://lh6.googleusercontent.com/0h2jgUdMozeID_9kdG-wVuFpL1rm3DEchaUKvusw5RNcaTddbU5MyHxZL3DFMFBTL0HpMnKju9HbI1PTQYOxEToeV1cv5QO0t_frSUoy4kRgkzS8s1jo1KTggoHoRE8ZMB3UCGjOB3htYcdjZq1M_vXP1FiVApfgE2EbJjglsG-fcJZJ_jGRs5yX" alt=""><figcaption></figcaption></figure>

Navigate to the comments section and check to see whether there are any comments. You should pay close attention to any comments warning against a scam, fraud, or similar. See the example below.

<figure><img src="https://lh3.googleusercontent.com/KnEub9kcDWQXQt-iM0I1XhQomD65Ili-fWRwbZVudF0t9MyNMKOM7-kz8JJCdPwsNkQJv2l1iKCvyADDNPGdp4cj_tPogsk-V_IbrvRipP1RXuohFreC7IUe9OKvDk0Nx0v7E2gYupBQp-I7Gr67QPuk2C_hSm9k57a0HJhINPBZl9RDARHoaiMJ" alt=""><figcaption></figcaption></figure>

### Contract creation time and transaction count

Another thing we can easily check in a contract is its creation time. First, we need to find the transaction in which the contract that we’re checking was created. We can easily do so using Etherscan within the ‘Transactions’ tab. Simply click on the three dots on the right-hand side of the page and select ‘Contract Creation’. This will show you the details – including the age – of the transaction in question.

<figure><img src="https://lh6.googleusercontent.com/jNeSasWZYlj4w1gnK4f__UteL6bent2hVn_7HyHuWe7KUY10emm-shQ4sRSatUhfOoGvagyF8mMUgRrsBWPt9L7xWpiD8iErWoF-mwJRAbwhNRojq7nxg6uIGF9syKfCIDF4ZPjRG4PZWKvJFDuXL82kK6hpkrmbbGVH05cFK50jcjAfiv0_757S" alt=""><figcaption></figcaption></figure>

You can now check the official sources that you’ve gathered for the launch date of the token or NFT. In most cases, these details should be readily available through content on a project’s social media channels (it’s something that most projects are proud to announce!). The contract should have been deployed before the date of the launch. A contract younger than a launch should be seen as a red flag.

This being said, let’s not discard the asset just yet. There’s the possibility that the project may have found a vulnerability in its original contract and, as a result, deployed a new one. Also, the project could have updated the contracts, which would have required a new contract deployment. If available, try to search for these updates on social media or the project’s official website/blog.

Another good indicator of contract legitimacy is its transaction count. Usually, contracts of popular projects will have thousands of transactions. Keep in mind that this depends on the specific project, and in the case of very small or new projects, just a handful of transactions may be enough for it to be considered legitimate (always be sure to verify this). You can see the total number of transactions in the transaction tab on Etherscan.

<figure><img src="https://lh3.googleusercontent.com/ViuQ92y5j07R7b4zu7UIWuEohVweq-zX70qmsyz1lffY2VfWBHsjc76XBrs3vggy2reQzryuRZko85UtsNzGUvlvae6pZWwsY8nhUXh0fTaDZ9LykExuH0wci016olMfu-P1S5Jy6PJbyEMuDkYs3zaceizyocbpF9y4Q206TyyOjbkth6S5ycqG" alt=""><figcaption></figcaption></figure>

### Closing thoughts

We’ve taken a look at a number of steps that you can take to ensure a token’s legitimacy. If you’ve checked everything according to this guide, it’s reasonable to assume that you’re dealing with a genuine token.

As we said in the beginning, even if a particular token is genuine, it doesn’t mean that it’s valuable! If you’re still unsure about token legitimacy, feel free to get in touch with PWN on our [Discord server](https://discord.gg/aWghBQSdHv). After all, it’s always better to ask questions than to get scammed, which can be a costly lesson.
