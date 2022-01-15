---
cover: ../../.gitbook/assets/Yield_Farming_NEW.png
coverY: 0
---

# 🌱 PAD Farms

{% embed url="https://dapps.padswap.exchange/farms" %}
Farm PAD in our PAD Farms on PADSwap
{% endembed %}

## Rewards and Distribution

In PAD farms you can earn PAD tokens. This section describes, where these PAD tokens come from and how they are distributed.

### Where do rewards come from?

Why should I care, you may ask. High APY is better, right? Not necessarily! See our notes on [#high-vs.-stable-apy](./#high-vs.-stable-apy "mention").

The rewards (APY) you see on the PAD farms come from a PAD distribution pool. The distribution pool is filled with freshly minted $PAD. Note, that $PAD is not an [#inflationary-token](../../fundamentals/glossary.md#inflationary-token "mention"), in fact, it has a max supply and burn functionality which makes it a [#deflationary-token](../../fundamentals/glossary.md#deflationary-token "mention").

Read all about $PADs tokenomics and how the minting / PAD drip works on our

{% hint style="info" %}
For all the details about $PADs tokenomics and how the minting / PAD drip works, see: [pad.md](../../fundamentals/tokens/pad.md "mention").
{% endhint %}

### How are rewards distributed?

The PAD farm distributes 10% of the distribution pool per day to all PAD farms and their stakers relative to their pool share. The 10% per day is distributed in one second intervals.

The distribution between PAD farms is currently uniform (all PAD farms get the same share). The distribution between PAD farms is set by the team and adjusted when new farms are added.

{% hint style="info" %}
Rewards are not actively distributed and instead stay in the pool until they are claimed. The UI just calculates and shows your claimable rewards.
{% endhint %}

## Fees

When you stake, reinvest or unstake your LP tokens in a PAD farm, you pay a 1% fee. Harvesting your PAD tokens does not incur a fee (except transaction fees). There are two types of PAD farms, the PAD pair farms where you need LP tokens to stake or the PAD solo farms where you can stake a single token directly. The LP tokens of the 1% fee on PAD pair farm are sent to [the-vault.md](../../fundamentals/the-vault.md "mention") as backing for [pad.md](../../fundamentals/tokens/pad.md "mention"). The single tokens of the 1% fee on PAD solo farms are burned.

The 'unstake' fee functions as a form of soft locking. It incentivizes you to keep your LP tokens staked for longer periods of time and therefore locking liquidity. But you are always free to withdraw your funds. See also our notes on [#no-vesting-less-risk](./#no-vesting-less-risk "mention").
