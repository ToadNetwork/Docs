---
cover: ../../.gitbook/assets/Yield_Farming_NEW.png
coverY: 0
---

# ♾ DPLP Farms

{% embed url="https://dapps.padswap.exchange/lpfarms" %}
Farm LP in our DPLP Farms on PADSwap
{% endembed %}

## DPLP

TOAD.Network invented the Decentralized Perpetual Liquidity Protocol (DPLP) as a mechanism which ensures that there is always an incentive for users to provide liquidity. This user provided liquidity is a big benefit for projects using the DPLP like TOAD, PAD or projects launched on the [launchpad.md](../launchpad.md "mention").

{% hint style="info" %}
This page focuses on the "incentive" aspect of DPLP, namely the DPLP farms. See [dplp.md](../../concepts/dplp.md "mention") for more details on the underlying concept.
{% endhint %}

## Rewards and Distribution

![Stake, unstake and reward distribution in DPLP farms](../../.gitbook/assets/dplp-farm.svg)

### Where do rewards come from?

Why should I care, you may ask. High APY is better, right? Not necessarily! See our notes on [#high-vs.-stable-apy](./#high-vs.-stable-apy "mention").

The rewards (APY) you see on the DPLP farms is coming from staking and unstaking fees. This ensures a continuous inflow of new rewards to the reward pool.

This works through the following two mechanics:

1. The APY is a natural free market incentive for people to stake and reinvest their LP tokens on the DPLP farms, thereby increasing the reward pool.
2. Should the APY decrease or even dry up, people will naturally want to move their funds to other more promising farms. The inevitable withdrawal of funds (unstaking) will in turn increase the reward pool again. This increase in APY will trigger 1. again.

The interplay between 1. and 2. is a perpetual motion, always ensuring high APY.

Getting this perpetual motion going requires some initial reward pool funds. These are usually donated by the project owners (e.g. projects launched on [launchpad.md](../launchpad.md "mention")). For TOAD and PAD DPLP farms, Snake and KT donated around $200k to the initial reward pool funds. By a drip of 1% per day, the donated rewards are mostly depleted after 1 year (3% left).

### How are rewards distributed?

The DPLP farm distributes 1% of the reward pool per day to all stakers relative to their pool share. The 1% per day are distributed in one second intervals.

{% hint style="info" %}
Rewards are not actively distributed and instead stay in the pool until they are claimed. The UI just calculates and shows your claimable rewards.
{% endhint %}

## Fees

When you stake, reinvest or unstake your LP tokens in a DPLP farm, you will have to pay a 10% fee. Of these 10% LP tokens, 7.5% LP tokens are returned into the reward pool and 2.5% LP token are sent [the-vault.md](../../concepts/the-vault.md "mention") as backing for [pad.md](../../tokens/pad.md "mention"). Harvesting your LP tokens does not incur a fee (except transaction fees).

The unstake fees functions as a form of soft locking. It incentivizes to keep the LP tokens staked and therefore the liquidity locked. But you are always free to withdraw you funds. See also our notes on [#no-vesting-less-risk](./#no-vesting-less-risk "mention").
