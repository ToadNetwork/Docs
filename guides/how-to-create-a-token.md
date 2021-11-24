---
description: >-
  This guide explains how you can create a token on PADSwap. Easy with view
  steps and zero coding involved!
cover: ../.gitbook/assets/toad-classroom.jpg
coverY: -188.6873920552677
---

# How to Create a Token?

{% hint style="success" %}
**TL;DR**

Head to the [token factory on PADSwap](https://padswap.exchange/tokenfactory), connect your wallet, follow the UI to deploy your token. The token creation will cost you 1 TOAD.
{% endhint %}

## Step 1: Navigate to the Token Factory on PADSwap

First you have to navigate to the token factory through the following link:

{% embed url="https://padswap.exchange/tokenfactory" %}
Deploy token contract via PADSwaps token factory.
{% endembed %}

## Step 2: Connect your Wallet

Connect your wallet to the site. In this guide we are using MetaMask.

{% hint style="info" %}
At the moment, Trust Wallet does not support the Moonriver and Moonbeam chains. If you plan on deploying your token on Moonriver or Moonbeam, then use MetaMask instead.
{% endhint %}

## Step 3: Select a Chain

As of writing this guide, the token factory supports the three chains BSC, Moonriver, and Moonbeam. You can decide on which chain you want to launch your token. There can be various decision factors, e.g.:

* Your community is already primarily on one chain.
* You personally believe in the future of a chain.
* You prefer lower transactions fees.

For this guide we will deploy a token on Moonbeam.

![Chain selection for token creation.](<../.gitbook/assets/image (8) (1).png>)

Check the lower left corner to confirm that the correct chain is selected. You might also need to switch to the respective chain in your wallet.

Press continue to confirm the selected chain.

## Step 4: Select a Token Type

The [token-factory.md](../products/launchpad/token-factory.md "mention") has a modular set of tokenomics you can choose for your token. This will be continuously extended in the future. If there are any tokenomics you are missing, feel free to bring it up in our [community.md](../project/community.md "mention").

Here you can choose between a Basic token or an Advanced token. The Basic token has standard tokenomics, no transaction fees and a capped supply. If you are planning on getting your token listed on CEXs, this is the more compatible option. If you want to have more advanced tokenomics, you can choose the second option. For this guide we will go with the second option.

![Select a general token type.](<../.gitbook/assets/image (3) (1).png>)

Check the lower right corner to confirm that the correct token type is selected.

Press continue to confirm the selected token type.

## Step 5: Specify Token Details and Tokenomics

For your token you will need to specify some details as well as the tokenomics.

For the token details you need to set a name, a symbol, the total supply and the number of decimals.

In this guide we will create a token called "How to Guide" with the symbol "HTG" and a total supply of 100k.

![Specify token details](<../.gitbook/assets/image (4) (1).png>)

You can choose a number of tokenomics. For this guide we will choose all currently available options, that is a 1% reflection, 0.5% burn, 1% liquidity and 0.5% dev share.

![Specify tokenomics](<../.gitbook/assets/image (5) (1).png>)

Pressing continue will show you a summary of your specified token details and tokenomics. Press continue again if everything is correct.

## Step 6: Create your Token

You are now ready to create your own token! To avoid scammers, we are charging a small fee of 1 TOAD for the token creation. Approve to spend TOAD for the creation fee.

![Approve TOAD for creation fee](<../.gitbook/assets/image (1) (1).png>)

Your wallet will ask you to confirm this approval. This will cost you a small fee but no TOAD will be deduced yet.

![Confirm spending of TOAD via wallet](<../.gitbook/assets/image (10).png>)

After the approval was confirmed, you can finally create your own token. Click create token to perform the token creation.

![Create your token](<../.gitbook/assets/image (2) (1).png>)

Your wallet will ask you to confirm the token contract creation. This will cost you a small fee and the 1 TOAD creation fee.

![Confirm spending for token creation via wallet](<../.gitbook/assets/image (7) (1).png>)

After the token contract creation was confirmed, you should see your tokens contract address.

![Created token contract address](<../.gitbook/assets/image (6) (1).png>)

You can view your token on the chains block explorer:

* BSC: [https://bscscan.com/](https://bscscan.com)
* Moonriver: [https://moonriver.moonscan.io/](https://moonriver.moonscan.io)
* Moonbeam: [https://moonscan.io/](https://moonscan.io)

For example, the token created in this guide: 0x0d1c2710647eca99bc0c68a39b0d0a1ce4a732df [(view explorer)](https://moonscan.io/token/0x0d1c2710647eca99bc0c68a39b0d0a1ce4a732df)

{% hint style="success" %}
Congrats! You have now created your own token. You can now launch a [presale on PADSwap](how-to-launch-a-token.md) so that your community can get your token and stake on your tokens [DPLP farm](../products/farms/dplp-farms.md).
{% endhint %}

{% hint style="info" %}
If the same token configuration was verified previously, your token contract will also show up as verified. If your tokens contract does not show as verified in the block explorer, please contact a member of the [core team](../project/team.md).
{% endhint %}