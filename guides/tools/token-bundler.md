---
description: Why not take all the loans at once?
---

# Token bundler

Token Bundler is a tool intended to make borrowing on PWN even easier. Instead of taking multiple loans against multiple assets, you can bundle assets together and simply create one loan!

This tutorial will get you through the bundling of different assets into a single bundle that you can then use as collateral. We’ll also provide instructions on unpacking these bundles. For technical reference regarding Token Bundler, please see PWN’s [developer documentation](https://app.gitbook.com/o/qU5BYc7llstaew78WOHt/s/vO9gnlV7gm6NLYDU5X6P/).&#x20;

### Bundling during the loan request process&#x20;

You can select more than one asset as collateral during the loan request process. In case you're feeling unsure about any part of the loan request process, check out the video tutorial we made for this very purpose:

{% embed url="https://www.youtube.com/watch?v=jA1HKpfps_4" %}

After you've selected each of the assets that you’d like to use as collateral, you’ll first need to approve them in order for the smart contract to interact with them. Once you’ve done so, you can proceed to creating your bundle by selecting the _Bundle Collateral_ button.

Please be sure that you're bundling the correct assets! Once you're sure that you’re ready to continue, select the _Bundle_ button to make an on-chain transaction bundling the assets. You can continue with your off-chain loan request creation once the blockchain has confirmed the transaction.

After you bundle your tokens, a single NFT that represents the bundle will be created.

### Token Bundler used as an independent tool&#x20;

If you want to create a bundle, head to the _Tools_ selection and select _Bundler_. There, you'll be able to bundle assets together and unpack existing bundles. Since we want to bundle assets and create a new bundle, select _Bundle Assets_.

Here, you can select all the assets you want to bundle. Please make sure you've selected the right assets. After that, click _Continue_.

Double-check your selected assets and, when you’re ready, make the necessary approvals of the assets to the Token Bundler contract. After you approve each of the assets, you can create the bundle by making one final transaction.

And now, you're finished!

{% hint style="info" %}
Just to make it extra clear: Using PWN, it’s possible to use your bundled NFT everywhere else in the ecosystem!
{% endhint %}

### Unbundling

This part’s super straightforward: To unpack a bundle that you’ve created or received, select _Bundler_ in the _Tools_ section and select _Unpack Bundle_.

Choose the bundle that you want to unpack and select _Continue_. (Remember to double-check that you've selected the correct one.)

Unpacking the bundle is as easy as selecting the _Unpack_ button and making one transaction in your wallet needed to unpack the bundle. The bundle will be unpacked as soon as the transaction gets confirmed on the blockchain.
