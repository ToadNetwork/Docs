---
description: >-
  This page explains common terms and lingo used in the crypto space and in this
  documentation.
---

# 📚 Glossary

## Annual Percentage Yield (APY)

The rate of return earned on an investment, taking into account the effect of compounding interest. Compounding with respect to [farms](../products/farms/ "mention") means, that your rewards will increase when you reinvest your received rewards.

{% hint style="info" %}
You will only receive the shown APY if you always reinvest. The APY does not take transaction fees into account. You need to decide when to reinvest.
{% endhint %}

## Arbitrage

{% hint style="info" %}
Docs in progress
{% endhint %}

## ATH / ATL

The all time high (ATH) and all time low (ATL) is referring to the time points where a token had the highest or lowest recorded price.

## Automated Market Maker (AMM)

Please read the section [#automated-market-maker-amm](../products/padswap/#automated-market-maker-amm "mention").

## Backing

Guarantee, that an asset can be exchanged with a fixed amount of another asset(s).

See also [#pegging](glossary.md#pegging "mention"), which is a similar concept.

## Bridge

Please read the linked page to understand what a bridge is:

{% content-ref url="../products/toad-bridge/" %}
[toad-bridge](../products/toad-bridge/)
{% endcontent-ref %}

## Burn

Existing tokens which no one has any access to (and never will) are considered to be burned. Burning tokens is often done by sending tokens to an address which can not be accessed. For example, on BSC [0x000000000000000000000000000000000000dEaD](https://bscscan.com/address/0x000000000000000000000000000000000000dead) is such an address.

There are several reasons to burn tokens:

1. Demand and supply define a tokens price. Burning tokens reduces the supply and given existing demand will increase the price.
2. Liquidity providers get LP tokens as collateral for withdrawal of their share of the liquidity pool. Burning these LP tokens means that no one can withdraw the respective liquidity and therefore increases the security for users. See also [#rug-pulling](glossary.md#rug-pulling "mention").

## Circulating Supply

{% hint style="info" %}
Docs in progress
{% endhint %}

## Deflationary Token

Token with decreasing circulating supply.

{% hint style="info" %}
Docs in progress
{% endhint %}

## Decentralized Autonomous Organization (DAO)

{% hint style="info" %}
Docs in progress
{% endhint %}

## Dollar-Cost Averaging (DCA)

Dollar-Cost Averaging (DCA) — a common term in crypto, referring to an investment strategy.
Instead of trying to predict when/if the market is up or down and buying accordingly, the DCA strategy suggest to simply split your investment into smaller investments which you perform over time independent of the current market conditions.
By doing so, you will most likely not get the best price but you will get an average price.
With the volatility of crypto this can be a good strategy to reduce regret of having missed the ATL or having bought at an ATH.
If someone suggests you to DCA down, they mean that you should frequently buy smaller portions while the price of a token is on a downwards trend instead of gambling on hitting the lowest point.

## Dripping

{% hint style="info" %}
Docs in progress
{% endhint %}

## DYOR

Do your own research — a common term in crypto, prompting others to form their own view on a crypto project.

## Farming

Please read the linked page to understand what farming is:

{% content-ref url="../products/farms/" %}
[farms](../products/farms/)
{% endcontent-ref %}

## Faucet

{% hint style="info" %}
Docs in progress
{% endhint %}

## Index

Measures the combined value of a basket of assets.

## Index Backing

Guarantee, that an asset can be exchanged with a fixed amount of other assets.

## Inflationary Token

Token with increasing circulating supply without max supply.

{% hint style="info" %}
Docs in progress
{% endhint %}

## KYC

Know Your Customer — process of customer identity verification. This is a common process in finance and also in the crypto space to prevent illegal activities or to avoid liability for customer's activities.

## Liquidity Pool

Please read the linked page to understand what a liquidity pool is:

{% content-ref url="../products/padswap/liquidity-pools.md" %}
[liquidity-pools.md](../products/padswap/liquidity-pools.md)
{% endcontent-ref %}

## Locking

{% hint style="info" %}
Docs in progress
{% endhint %}

## Market Cap

{% hint style="info" %}
Docs in progress
{% endhint %}

## Max Supply

{% hint style="info" %}
Docs in progress
{% endhint %}

## Minting

Increasing the total supply of a token by releasing new tokens. If a token has a max supply, then the number of tokens which can be minted is limited by the max supply. If there is no max supply, the token can be minted infinitely and is therefore considered to be an inflationary token.

See also [#total-supply](glossary.md#total-supply "mention"), [#max-supply](glossary.md#max-supply "mention"), [#inflationary-token](glossary.md#inflationary-token "mention")

## Multisig

A multisig is generally a wallet which requires multiple signatures for transactions to be executed.
They increase the security by requiring multiple persons to confirm.

## Order Book

An order book records the interest of buyers and sellers. They respectively can announce for what price they are willig to trade a certain amount. If the interest between buyers and sellers matches, the order book facilitates a trade. The middle between bids (buyer) and asks (seller) defines the price of the asset.&#x20;

## Pegging

The price of one asset being bound to the price of another asset(s).

Stable coins like BUSD are one example of pegging. Since BUSD is pegged by USD, you expect 1 BUSD will always have the same value as 1 USD.

See also [#backing](glossary.md#backing "mention"), which is a similar concept.

## Price Impact

In an [#automated-market-maker-amm](../products/padswap/#automated-market-maker-amm "mention"), swapping assets changes the ratio in a liquidity pool which results in a change in the exchange rate. This recalculation of the exchange rate is done for every unit of the underlying assets. Price impact is when your effective exchange rate is increased by your own trade.

## Reflections

{% hint style="info" %}
Docs in progress
{% endhint %}

## Rug Pulling

If someone takes away important support of a project, this is known as rug pulling. This can make a token worthless due to a severe price reduction or by removing the ability to sell.

There are many forms of rug pulling, e.g.:

1. Removing large portions of a liquidity pool, which removes the ability to sell.
2. Selling high percentages of the circulating token supply in a short period, which drastically reduces the token price.

## Slippage

If a trade can only be executed with worse conditions than the trader expected, we are talking about slippage. In a classical [#order-book](glossary.md#order-book "mention") this can happen when another buyer is quicker in accepting a sell offer, leaving only worse sell offers to fulfill the trade. In an [#automated-market-maker-amm](glossary.md#automated-market-maker-amm "mention") this can happen when parallel swaps shift the ratio of tokens in the [#liquidity-pool](glossary.md#liquidity-pool "mention"), thereby changing the current exchange rate.

Slippage can be especially strong during events which result in one sided trades (mostly buys or sells) like a launch event or bad news. Setting a slippage during your trade means that your trade can be x% worse than for what you initiated it.

{% hint style="warning" %}
Be very careful with this parameter! You can lose a lot of your funds.

When trading fails, people are quick to suggest setting a high slippage. In most cases this is bad advise! There are many reasons why a trade can fail. One common example can be rounding issues which you can solve by setting a more even amount for the target asset like 3500000 instead of 3539838.
{% endhint %}

## Staking

If you put your tokens into a pool (e.g. a farm), then you effectively own a share of that pool. In other words, you have a stake in the pool. The process of you supplying your tokens to the pool is therefore called staking.

See also [#farming](glossary.md#farming "mention").

## Timelock

A timelock refers to how smart contract changes are enacted. For example, there can be a 48h period until contract changes take effect. This gives users the option to opt-out before an upcoming change if they disagree with the change.

This should not be confused with locking / vesting.

## Tokenomics

Tokenomics is a wordplay on token and economics. 
It usually refers to different properties and mechanics of a token.
Properties can things like a max supply.
Mechanics can be things like sell, buy or transaction taxes, reflections or minter functionalities.

## Total Supply

{% hint style="info" %}
Docs in progress
{% endhint %}

## Total Value Locked (TVL)

Is used to measure the overall health of a DeFi market. Tokens supplied as liquidity in [#liquidity-pool](glossary.md#liquidity-pool "mention")s can be removed at any time. Staking in yield farms gives an incentive to leave the tokens in the liquidity pool. This can be done by providing rewards and also by incurring yield farm exit fees. This is referred to as "locking" the liquidity. The total value locked (TVL) on a yield farm is the total value staked in this yield farm.

See also [#farming](glossary.md#farming "mention") and [#liquidity-pool](glossary.md#liquidity-pool "mention") to learn more.

## Vesting

{% hint style="info" %}
Docs in progress
{% endhint %}
