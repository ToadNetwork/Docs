---
cover: broken-reference
coverY: 0
---

# 🍄 PADSwap

{% embed url="https://padswap.exchange/#/swap" %}
Use PADSwap to swap tokens
{% endembed %}

## What is PADSwap?

[PADSwap](https://dapps.padswap.exchange) is a decentralized exchange (or DEX, for short). PADSwap is also multi-chain, currently on BSC, Moonriver and Moonbeam with more to come.

![System Overview Written in a Fever Dream](<../../.gitbook/assets/TOAD PAD ECOSYSTEM MAP.jpg>)

## How does PADSwap compare to centralized exchanges?

Centralized exchanges (CEXs) like Binance, Coinbase, Kraken or Crypto.com offer a one-stop-shop solution with wallet, exchange, fiat conversion and other features tightly integrated into a single multiplatform application. Newcomer therefore often start trading crypto on these platforms.

Compared to these old centralized exchanges, PADSwap offers benefits like being non-custodial, permissionless and using an Automated Market Maker (AMM) over an order book.

### Non-custodial

Custodial exchanges like centralized exchanges are like banks. They hold and handle your tokens. You need to trust them to not withhold your tokens.

PADSwap is non-custodial, which means that—unlike centralized exchanges—PADSwap does not need to possess your tokens in order for you to be able to trade them. Instead, PADSwap allows users to trade tokens from their wallet like [MetaMask](https://metamask.io) or [Trust Wallet](https://trustwallet.com/de/) via [liquidity-pools.md](liquidity-pools.md "mention").

### Permissionless

Centralized exchanges restrict their services to certain geographies and to selected people e.g. only of certain age.

On PADSwap anyone can use our swap, provide liquidity or stake in our farms. TOAD.Networks products are open for public use without restrictions for anyone.

### Automated Market Maker (AMM)

Centralized exchanges usually use an [#order-book](../../fundamentals/glossary.md#order-book "mention") to facilitate trades. Buyers and sellers announce their interest in a trade and if bids and asks match, the trade is performed. The middle between buyers and sellers defines the price.

PADSwap uses a so called Automated Market Maker (AMM) to facilitate trades. At its core are the [liquidity-pools.md](liquidity-pools.md "mention") which replace the order book. Buyers and sellers no longer trade with each other but instead directly trade their assets with the pool. You can think of a liquidity pool as a vending machine which holds two items, e.g. apples and oranges. To get apples, you put oranges in and to get oranges you put apples in, trading one against the other. The ratio between two assets in a liquidity pool defines the exchange ratio (commonly referred to as price). If you take out apples, they become more scares. For you to get even more apples, you would need to supply more oranges per apples than you did before. The recalculation of the ratio takes place for every single asset leaving or entering the liquidity pool. Thus, for large trades (relative to the liquidity in the pool), the change in exchange ratio will also effect your trade, this is known as [#price-impact](../../fundamentals/glossary.md#price-impact "mention"). If the trades of others have a negative impact on your trade, this is referred to as [#slippage](../../fundamentals/glossary.md#slippage "mention"). Since the exchange ratio is defined by the pool, there are no buyers and sellers in the traditional sense. Given the vending machine example, you can probably see why the action of trading with a liquidity pool is referred to as swapping.&#x20;

As long as there is liquidity in the pool, you can trade at any point in time. With the [dplp.md](../../fundamentals/dplp.md "mention"), PADSwap ensures that there is always an incentive for users to provide liquidity. This means that new projects can easily connect to their desired markets by using our [launchpad](../launchpad/ "mention") which provides them with a [DPLP farm](../farms/dplp-farms.md).

## How does PADSwap compare to other decentralized exchanges?

### On BSC

|                                   |                        PADSwap                       |                       PancakeSwap                      |                               SushiSwap                              |
| --------------------------------- | :--------------------------------------------------: | :----------------------------------------------------: | :------------------------------------------------------------------: |
| Swap fee distribution             | <p>0.25% to LP providers<br>0.05% to PAD backing</p> | <p>0.17% to LP providers<br>0.03% to devs' pockets</p> |        <p>0.25% to LP providers<br>0.05% to SUSHI holders</p>        |
| Reward token tokenomics           |                     Capped supply                    |                    Infinitely minted                   |                             Capped supply                            |
| Reward token backing              |     Backed by the Vault of accumulated swap fees     |                          None                          |                                 None                                 |
| Multi-chain                       |               BSC, Moonriver, Moonbeam               |                        BSC only                        |                              Multi-chain                             |
| In-house cross-chain bridge       |                          Yes                         |                           No                           |                                  No                                  |
| Launchpad                         |                          Yes                         |                           No                           |                                  No                                  |
| Partner farms (earn other tokens) |                          Yes                         |        <p>Partially<br>(you must stake CAKE)</p>       | <p>Partially<br>(earning half in SUSHI and half in other tokens)</p> |
| LP as staking reward              |                          Yes                         |                           No                           |                                  No                                  |

### On Moonbeam

|                             |                        PADSwap                       |                     SOLARFLARE                    |                    StellaSwap                    |  Dusty Dunes  |                      Thorus                      |                     Zenlink                    |                    Beamswap                    |    LunarDEX   |
| --------------------------- | :--------------------------------------------------: | :-----------------------------------------------: | :----------------------------------------------: | :-----------: | :----------------------------------------------: | :--------------------------------------------: | :--------------------------------------------: | :-----------: |
| Swap fee distribution       | <p>0.25% to LP providers<br>0.05% to PAD backing</p> | <p>0.20% to LP providers<br>0.05% to Treasury</p> | <p>0.25% to LP providers<br>0.05% to B.Vault</p> |               | <p>0.03% to LP providers<br>0.07% to Reserve</p> | <p>0.15% to LP providers<br>0.15% to Misc.</p> | <p>0.17% to LP providers<br>0.13% to Misc.</p> |               |
| Reward token tokenomics     |                     Capped supply                    |                   Capped supply                   |                   Capped supply                  | Capped supply |                   Capped supply                  |                  Capped supply                 |                  Capped supply                 | Capped supply |
| Reward token backing        |     Backed by the Vault of accumulated swap fees     |                                                   |                                                  |               |                  $STATIK > $0.99                 |                                                |                                                |               |
| Multi-chain                 |               BSC, Moonriver, Moonbeam               |                Moonriver, Moonbeam                |                        No                        |       No      |                Moonbeam, Avalanche               |               Moonriver, Moonbeam              |                       No                       |       No      |
| In-house cross-chain bridge |                          Yes                         |                        Yes                        |                        Yes                       |               |                                                  |                       Yes                      |                       Yes                      |               |
| Faucet                      |                          Yes                         |               "3% Fee" gas-less swap              |                        Yes                       |               |                                                  |                                                |                       Yes                      |               |
| Launchpad                   |                          Yes                         |                                                   |               TBD Targeting Jun 22               |               |                        TBD                       |                                                |                       TBD                      |               |
| LP as staking reward        |                          Yes                         |                                                   |                                                  |               |                                                  |                                                |                                                |               |
| Solo Staking $GLMR          |                          Yes                         |                        Yes                        |                        Yes                       |      Yes      |                                                  |                       Yes                      |                       Yes                      |               |

## PADSwap Router and Factory Contracts

{% tabs %}
{% tab title="BSC (BEP-20)" %}
* Router: 0x76437234D29f84D9A12820A137c6c6A719138C24 [(view explorer)](https://bscscan.com/address/0x76437234d29f84d9a12820a137c6c6a719138c24)
* Factory: 0xB836017ACf10b8A7c6c6C9e99eFE0f5B0250FC45 [(view explorer)](https://bscscan.com/address/0xb836017acf10b8a7c6c6c9e99efe0f5b0250fc45)
{% endtab %}

{% tab title="Moonriver" %}
* Router: 0x790d4b443edB9ce9A8d1aEC585edd89E51132D2c [(view explorer)](https://moonriver.moonscan.io/address/0x790d4b443edb9ce9a8d1aec585edd89e51132d2c)
* Factory: 0x760d2Bdb232027aB3b1594405077F9a1b91C04c1 [(view explorer)](https://moonriver.moonscan.io/address/0x760d2bdb232027ab3b1594405077f9a1b91c04c1)
{% endtab %}

{% tab title="Moonbeam" %}
* Router: 0x40F1fEF0Fe68Fd10ff904070ee00a7769EE7fe34 [(view explorer)](https://blockscout.moonbeam.network/address/0x40F1fEF0Fe68Fd10ff904070ee00a7769EE7fe34)
* Factory: 0x663a07a2648296f1A3C02EE86A126fE1407888E5 [(view explorer)](https://blockscout.moonbeam.network/address/0x663a07a2648296f1A3C02EE86A126fE1407888E5)
{% endtab %}
{% endtabs %}
