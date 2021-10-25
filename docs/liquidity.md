## What is liquidity?
In order for a swap service like PADSwap to function, the system must have some funds to operate with. After all, when you swap one token for another, where are the tokens coming from?

These funds are added by ordinary users in exchange for **earning transaction fees** and **staking** their liquidity in a [wide variety of farms](farms.md).
The funds added to the swap are usually referred to as **liquidity**, which is a measure of how easily you can buy or sell an asset - or **how much** of it you can buy/sell.

Liquidity is always stored in **pairs**, such as TOAD-BNB or PAD-BTC, with each pair being held in a separate **liquidity pool**.
For example, when someone swaps BNB for TOAD, the user's BNB is added to the TOAD-BNB pool, and the equivalent amount of TOAD is taken from the pool and given to the user.

Generally, more liquidity is better, as it allows users to easily buy and sell large amounts of tokens without causing equally large price impacts.

## The benefits of providing liquidity
There are two main reasons to provide liquidity:
1. **0.25%** of every transaction on PADSwap goes to the liquidity pool rewards drip as a way to reward liquidity providers. Since the supply of LP tokens stays the same, the value of your LP tokens increases with every transaction on that liquidity pair.

2. While some tokens can be staked separately, most of our [farms](https://dapps.padswap.exchange/)  are using **LP tokens** and are much more lucrative. Keep in mind that while your LP tokens are staked, you are **also earning LP fees** mentioned above!

## Providing liquidity on PadSwap

Liquidity can be added and removed by any user [on the liquidity tab on PadSwap](https://padswap.exchange/#/pool).
Since liquidity is always added in pairs, you will have to choose two tokens and add them *in equal parts* (e.g. $50 worth of token A and $50 worth of token B).
We encourage you to [take a look at our farms](https://dapps.padswap.exchange/) before deciding which token pair you wish to provide.

After adding liquidity, you will receive **LP tokens** that you can now stake in corresponding farms.
If at any point you wish to take out your liquidity and exchange it for the original tokens, you can do it on the same liquidity tab. 

**In case you don't see your liquidity on the liquidity tab:**
1. Make sure that you've unstaked your LP tokens from the farms
2. On the liquidity page, click "Import it" and select your liquidity pair.


## Impermanent loss

As you might know, the price of a token is directly related to the ratio between tokens in the pool.
For example, if 1 TOAD is worth 100 BUSD, it means that the TOAD-BUSD pool has 100 BUSD tokens for every TOAD token.

When the price of a token changes, so does the ratio of tokens in the pool.
The **total value** of the pool remains constant, and you are still entitled to the exact same **percentage** of the pool - however, you will receive **more** of token A and **less** of token B when withdrawing your liquidity, which is **slightly less value than if you held the tokens separately**.

Usually, the **LP rewards** combined with **farming** are more than enough to counter the effects of impermanent loss, but it could be problematic in case of extreme price fluctuations.

To see an example of how price fluctuations can cause impermanent loss, you can use [our impermanent loss calculator in TOAD Toolbox](https://toad.academy/toolbox/)

