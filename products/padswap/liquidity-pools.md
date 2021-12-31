---
cover: ../../.gitbook/assets/Untitled_Artwork 3.png
coverY: 245.39877300613497
---

# 🌊 Liquidity Pools

{% embed url="https://padswap.exchange/#/pool" %}
Link to PADSwap Liquidity Pools
{% endembed %}

## What are liquidity pools?

Liquidity pools are a place to pool tokens (which we sometimes call liquidity) so that users can use them to make trades in a decentralized way. These pools are created by users and decentralized apps (or Dapps, for short) who want to profit from their usage. To pool liquidity, the amounts a user supplies must be equally divided between two coins: the primary token (sometimes called the quote token) and the base token (usually BNB, MOVR or a stable coin).

The existence of this pooled liquidity gives other traders access to the underlying tokens in exchange for a small fee, which is distributed proportionately to all the liquidity providers. In this sense, PADSwap is also an “automated market maker” (or AMM, for short).&#x20;

PADSwap's liquidity pools allow anyone to provide liquidity [here](https://padswap.exchange/#/pool).

Once a user provides liquidity, they will receive PADSwap liquidity provider (LP) tokens that represent their share of the pooled liquidity for that token pair. If a user deposited $TOAD and $BNB into a pool, they would receive TOAD-BNB LP tokens. These LP tokens represent a proportional share of the pooled assets, allowing a user to reclaim their provided liquidity at any point. Every time another user uses the pool to trade between $TOAD and $BNB, a 0.3% fee is taken on the trade. 0.25% of that trade goes back to the LP pool. .05% Is sent to the [**The Vault**](https://dapps.padswap.exchange/vault) as index backing for $PAD.\
\
The value of the LP tokens (which represent the shares of the total liquidity in each pool) is updated with each trade to add their value relative to the tokens the pool uses to trade. If previously there were 100 LP tokens representing 100 BNB and 100 TOAD, each token would be worth 1 BNB & 1 TOAD (note in this example, BNB and TOAD are the same relative value). If a user were then to trade 10 BNB for 10 TOAD in that pool, and another user were to trade 10 TOAD for 10 BNB, then there would now be 100.025 BNB and 100.025 TOAD. This means each LP token would be worth 1.0025 BNB and 1.00025 TOAD now when it is withdrawn.

### Instructions for adding liquidity

The following guide walks you through the process of providing liquidity:

[how-to-provide-liquidity.md](../../guides/how-to-provide-liquidity.md "mention")

### Adding liquidity to a new pool

If the pool you wish to provide liquidity to does not exist, you can create it! Simply provide the tokens, and off you go. As the first liquidity provider, you set the initial exchange ratio (price). This often quickly corrects itself through arbitrage and by more liquidity providers adding to the pool.&#x20;

{% hint style="info" %}
The arbitrage is to your disadvantage. We therefore recommend you to set the initial exchange ratio (price) according to the current market price.
{% endhint %}

{% hint style="info" %}
For the creation of the liquidity pool (contract) the gas price will be a bit higher.
{% endhint %}

### What is liquidity?

In order for a swap service like PADSwap to function, the system must have some funds to operate with. After all, when you swap one token for another, where are the tokens coming from?

These funds are added by ordinary users in exchange for **earning transaction fees** and **staking** their liquidity in a wide variety of farms. The funds added to the swap are usually referred to as **liquidity**, which is a measure of how easily you can buy or sell an asset — or **how much** of it you can buy/sell.

Liquidity is always stored in **pairs**, such as TOAD-BNB or PAD-BTC, with each pair being held in a separate **liquidity pool**. For example, when someone swaps BNB for TOAD, the user's BNB is added to the TOAD-BNB pool, and the equivalent amount of TOAD is taken from the pool and given to the user.

Generally, more liquidity is better, as it allows users to easily buy and sell large amounts of tokens without causing equally large price impacts.

### The benefits of providing liquidity

There are two main reasons to provide liquidity:

1. **0.25%** of every transaction on PADSwap goes to the liquidity pool rewards drip as a way to reward liquidity providers. Since the supply of LP tokens stays the same, the value of your LP tokens increases with every transaction on that liquidity pair.
2. While some tokens can be staked separately, most of our [farms](https://dapps.padswap.exchange) are using **LP tokens** and are much more lucrative. Keep in mind that while your LP tokens are staked, you are **also earning LP fees** mentioned above!

### Providing liquidity on PadSwap

Liquidity can be added and removed by any user [on the liquidity tab on PadSwap](https://padswap.exchange/#/pool). Since liquidity is always added in pairs, you will have to choose two tokens and add them _in equal parts_ (e.g. $50 worth of token A and $50 worth of token B). We encourage you to [take a look at our farms](https://dapps.padswap.exchange) before deciding which token pair you wish to provide.

After adding liquidity, you will receive **LP tokens** that you can now stake in corresponding farms. If at any point you wish to take out your liquidity and exchange it for the original tokens, you can do it on the same liquidity tab.

**In case you don't see your liquidity on the liquidity tab:**

1. Only LP tokens not staked in any farm are shown
2. On the liquidity page, click "Import it" and select your liquidity pair.

### Impermanent loss

As you might know, the price of a token is directly related to the ratio between tokens in the pool. For example, if 1 TOAD is worth 100 BUSD, it means that the TOAD-BUSD pool has 100 BUSD tokens for every TOAD token.

When the price of a token changes, so does the ratio of tokens in the pool. The **total value** of the pool remains constant, and you are still entitled to the exact same **percentage** of the pool - however, you will receive **more** of token A and **less** of token B when withdrawing your liquidity, which is **slightly less value than if you held the tokens separately**.

The adjustment of the token ratio conforms to the equation $$x * y = k$$, where $$x$$ and $$y$$ are the quantities of the two paired tokens, and $$k$$ is constant. This means that even though you supply equal parts of two tokens to the pool, the quantities you receive when you reclaim your liquidity will change relative to the difference in the change in price of the two tokens when you remove the liquidity. If the price of $$x$$ token goes up, and $$y$$ token goes down, you will have less of $$y$$ and more of $$y$$, and vice versa. If the price of both tokens goes up, or the price of both goes down, you will nonetheless have relative quantities of each token proportionately to the difference in the change of the price of x and y.

![Ratio adjustment between two tokens in a pool due to price changes](<../../.gitbook/assets/amm graph.png>)

Usually, the **LP rewards** combined with **farming** are more than enough to counter the effects of impermanent loss, but it could be problematic in case of extreme price fluctuations.

{% hint style="success" %}
To see an example of how price fluctuations can cause impermanent loss, you can use [our impermanent loss calculator in TOAD Toolbox](https://toad.academy/toolbox/)
{% endhint %}
