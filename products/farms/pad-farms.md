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

## PAD Farm Contracts

{% tabs %}
{% tab title="BSC (BEP-20)" %}
* PAD: 0x30024473EFd45ef9bFD7781Db5438E1A58664ED1 [(view explorer)](https://bscscan.com/address/0x30024473EFd45ef9bFD7781Db5438E1A58664ED1)
* TOAD: 0x4992df071416370fe780627eDFDD8CbC694Ed08b [(view explorer)](https://bscscan.com/address/0x4992df071416370fe780627eDFDD8CbC694Ed08b)
* BNB-BUSD:	0x9eC11e716d029142a206614AA1628B5aE3c07646 [(view explorer)](https://bscscan.com/address/0x9eC11e716d029142a206614AA1628B5aE3c07646)
* BUSD-USDT:	0x317De8C509D9a87C9E20c8dF1e1ef960cc9dc534 [(view explorer)](https://bscscan.com/address/0x317De8C509D9a87C9E20c8dF1e1ef960cc9dc534)
* PAD-ADA:	0x5459A5CD736c09e8A7fc3aCA1cF6A184Bed8a567 [(view explorer)](https://bscscan.com/address/0x5459A5CD736c09e8A7fc3aCA1cF6A184Bed8a567)
* PAD-BNB:	0xA13CB324Af6A9B31332756464c089D3511436345 [(view explorer)](https://bscscan.com/address/0xA13CB324Af6A9B31332756464c089D3511436345)
* PAD-BTC:	0x5A86157Ea673A3b6608fc2D99f4D3E624631B53d [(view explorer)](https://bscscan.com/address/0x5A86157Ea673A3b6608fc2D99f4D3E624631B53d)
* PAD-BUSD:	0xF189bd30bCe093fca7E688A2dE28BB14aFF47A35 [(view explorer)](https://bscscan.com/address/0xF189bd30bCe093fca7E688A2dE28BB14aFF47A35)
* PAD-DOGE:	0xc27192bd78e60393725F4c4515f6358c65F8BeFa [(view explorer)](https://bscscan.com/address/0xc27192bd78e60393725F4c4515f6358c65F8BeFa)
* PAD-ETH:	0xaF56Ae5De49Fb6F94309E00Bf9C9368B0dd0fC96 [(view explorer)](https://bscscan.com/address/0xaF56Ae5De49Fb6F94309E00Bf9C9368B0dd0fC96)
* PAD-HOGE:	0x662425AaB93bA95b3bF3cBF9A909b9B1bC93E834 [(view explorer)](https://bscscan.com/address/0x662425AaB93bA95b3bF3cBF9A909b9B1bC93E834)
* PAD-PR:	0xf6E5A88EC5eBa2c8A22845bdf5f1f5167119b270 [(view explorer)](https://bscscan.com/address/0xf6E5A88EC5eBa2c8A22845bdf5f1f5167119b270)
* PAD-TOAD:	0x39205195afb9c79a5eB1D9575091B5a6A19DB7EA [(view explorer)](https://bscscan.com/address/0x39205195afb9c79a5eB1D9575091B5a6A19DB7EA)
* TOAD-BNB:	0xB69829f8e0F5D920F1B53D5685B76af723Fd5007 [(view explorer)](https://bscscan.com/address/0xB69829f8e0F5D920F1B53D5685B76af723Fd5007)
* TOAD-BUSD:	0x6555c387c721b02E157B723B43c5AAe3f1becd40 [(view explorer)](https://bscscan.com/address/0x6555c387c721b02E157B723B43c5AAe3f1becd40)
* TOAD-DOT:	0xB6D1631E82cE3c5D29F0AF066BD6B1B0e77CdE2E [(view explorer)](https://bscscan.com/address/0xB6D1631E82cE3c5D29F0AF066BD6B1B0e77CdE2E)
* TOAD-HOGE:	0xA9F4eaA4e55Be6EB54018BAE0698b644BB36B47C [(view explorer)](https://bscscan.com/address/0xA9F4eaA4e55Be6EB54018BAE0698b644BB36B47C)
{% endtab %}

{% tab title="Moonriver" %}
* PAD: 0xac7793401ED049c899AC863E71Afc9bfDE464411 [(view explorer)](https://moonriver.moonscan.io/address/0xac7793401ED049c899AC863E71Afc9bfDE464411)
* BNB-BUSD: 0x35E1F3A0D25ff0e4c0eF22ab4cd27106711cC644 [(view explorer)](https://moonriver.moonscan.io/address/0x35E1F3A0D25ff0e4c0eF22ab4cd27106711cC644)
* MOVR-USDC: 0x54Cd3A30257760e4959cFcBaF387A27C92E73aFB [(view explorer)](https://moonriver.moonscan.io/address/0x54Cd3A30257760e4959cFcBaF387A27C92E73aFB)
* PAD-BUSD: 0x86bE1D18dBf8602e15d8553e5aAE9694C5cE86dB [(view explorer)](https://moonriver.moonscan.io/address/0x86bE1D18dBf8602e15d8553e5aAE9694C5cE86dB)
* PAD-MOVR: 0x8a5dC54F537FFd91E6c6616915D71124431Aa6bd [(view explorer)](https://moonriver.moonscan.io/address/0x8a5dC54F537FFd91E6c6616915D71124431Aa6bd)
* PAD-USDC: 0xE6d0d9c4b77E3A1a2Ce8563bBC8928d6ccC4a98b [(view explorer)](https://moonriver.moonscan.io/address/0xE6d0d9c4b77E3A1a2Ce8563bBC8928d6ccC4a98b)
* RDOGE-MOVR:	0xeB8627a924A5ddB8f866e37D9537a27d9C590e11 [(view explorer)](https://moonriver.moonscan.io/address/0xeB8627a924A5ddB8f866e37D9537a27d9C590e11)
* TOAD-BNB: 0xE52c059830cEA7ef9Ca1D1D27A9c48d51cc3a16F [(view explorer)](https://moonriver.moonscan.io/address/0xE52c059830cEA7ef9Ca1D1D27A9c48d51cc3a16F)
* TOAD-MOVR: 0xE85cA657DA9546c9ECE8fB0A7Bc2277006770393 [(view explorer)](https://moonriver.moonscan.io/address/0xE85cA657DA9546c9ECE8fB0A7Bc2277006770393)
* TOAD-PAD: 0xcB592dddBd7cF748ef1A23C33e363d5B52d8bE2F [(view explorer)](https://moonriver.moonscan.io/address/0xcB592dddBd7cF748ef1A23C33e363d5B52d8bE2F)
* TOAD-USDC: 0x9f043fd683CcAE26249dC0c04e3Fd0deEe7c753A [(view explorer)](https://moonriver.moonscan.io/address/0x9f043fd683CcAE26249dC0c04e3Fd0deEe7c753A)
* USDC-BUSD: 0xf403dAf66558ef3Dbac9FfaC18B5AFB3B723Cf25 [(view explorer)](https://moonriver.moonscan.io/address/0xf403dAf66558ef3Dbac9FfaC18B5AFB3B723Cf25)
* USDC-DAI: 0xB04afC3210f8BFE998Fa8beFC4C5B9011bBde4Cb [(view explorer)](https://moonriver.moonscan.io/address/0xB04afC3210f8BFE998Fa8beFC4C5B9011bBde4Cb)
* USDC-USDT: 0x9F10eFeE960bD80Ad0BE4DF8F63afFBdDb06fA21 [(view explorer)](https://moonriver.moonscan.io/address/0x9F10eFeE960bD80Ad0BE4DF8F63afFBdDb06fA21)
{% endtab %}

{% tab title="Moonbeam" %}
* Pad: 0x8597caE71536655B2B2bed008C5Ee1B8D412E3eC [(view explorer)](https://moonscan.io/address/0x8597caE71536655B2B2bed008C5Ee1B8D412E3eC)
* Toad: 0x2AfFDf2dCf47a9D16155A87992Ba79b88e6AA770 [(view explorer)](https://moonscan.io/address/0x2AfFDf2dCf47a9D16155A87992Ba79b88e6AA770)
* WGLMR 0x3ec74Cf5F69efa0778c1aB98AeA31BC54d579518 [(view explorer)](https://moonscan.io/address/0x3ec74Cf5F69efa0778c1aB98AeA31BC54d579518)
* AVAX-WGLMR: 0xf34574cC8C60db71e9b57aFD1B03503a060E4c85 [(view explorer)](https://moonscan.io/address/0xf34574cC8C60db71e9b57aFD1B03503a060E4c85)
* BUSD-BNB 0xC13cF29b7d07471527dEf097b31f4ccFAb1de18C [(view explorer)](https://moonscan.io/address/0xC13cF29b7d07471527dEf097b31f4ccFAb1de18C)
* BUSD-TOAD: 0xdc8aFfc2B45Ff86b17ab430a90eaa8053AFEC79d [(view explorer)](https://moonscan.io/address/0xdc8aFfc2B45Ff86b17ab430a90eaa8053AFEC79d)
* BUSD-WGLMR: 0xf617c077D1C47429366f08f3E99a6dc6448F1047 [(view explorer)](https://moonscan.io/address/0xf617c077D1C47429366f08f3E99a6dc6448F1047)
* PAD-TOAD: 0x4f738bE7f861645d1B001E152796E4508781225E [(view explorer)](https://moonscan.io/address/0x4f738bE7f861645d1B001E152796E4508781225E)
* PAD-USDC: 0x4d86dae4E6b2cce94c1C2Cb371529B4B98443c7e [(view explorer)](https://moonscan.io/address/0x4d86dae4E6b2cce94c1C2Cb371529B4B98443c7e)
* PAD-USDT: 0x7a06dbaE8666e7DbdCf26A37be020dfedC782176 [(view explorer)](https://moonscan.io/address/0x7a06dbaE8666e7DbdCf26A37be020dfedC782176)
* PAD-WGLMR: 0xb54229144504FC3FC916820eBd69Efc5BB897188 [(view explorer)](https://moonscan.io/address/0xb54229144504FC3FC916820eBd69Efc5BB897188)
* USDC-BUSD: 0xB695FDACF48d3038AAAe419DF597Fa8089cc2939 [(view explorer)](https://moonscan.io/address/0xB695FDACF48d3038AAAe419DF597Fa8089cc2939)
* USDC-TOAD: 0x7E24C2785a76086D3bC1e8E2878a55e0B3Fc3b57 [(view explorer)](https://moonscan.io/address/0x7E24C2785a76086D3bC1e8E2878a55e0B3Fc3b57)
* USDC-WGLMR: 0xc2092b6dF7fc766D6A4C7bBFaEE14695B2e0fbDa [(view explorer)](https://moonscan.io/address/0xc2092b6dF7fc766D6A4C7bBFaEE14695B2e0fbDa)
* USDT-USDC: 0x45488C50184Ce2092756ba7CdF85731fD17e6f3d [(view explorer)](https://moonscan.io/address/0x45488C50184Ce2092756ba7CdF85731fD17e6f3d)
* USDT-WGLMR: 0x603b8a9E84e7E2c715f423CBd488125647C8022b [(view explorer)](https://moonscan.io/address/0x603b8a9E84e7E2c715f423CBd488125647C8022b)
* WGLMR-ETH: 0x7D17A9a892Ad5ED16214805678F2581D88a58Ba1 [(view explorer)](https://moonscan.io/address/0x7D17A9a892Ad5ED16214805678F2581D88a58Ba1)
* WGLMR-TOAD: 0xeee6BA4189E33D4339e99b12913c581Ec99ec665 [(view explorer)](https://moonscan.io/address/0xeee6BA4189E33D4339e99b12913c581Ec99ec665)
{% endtab %}
{% endtabs %}
