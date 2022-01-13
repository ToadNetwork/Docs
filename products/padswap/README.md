---
cover: ../../.gitbook/assets/PADSwap_New.png
coverY: 0
---

# 🍄 PADSwap

{% embed url="https://padswap.exchange/#/swap" %}
Use PADSwap to swap tokens
{% endembed %}

## What is PADSwap?

[PADSwap](https://dapps.padswap.exchange) is a decentralized exchange (or DEX, for short). PADSwap is also multi-chain, currently on BSC, Moonriver and Moonbeam with more to come.

{% hint style="info" %}
Docs in progress
{% endhint %}

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

{% hint style="info" %}
Docs in progress
{% endhint %}

With liquidity that is supplied by other users. This means that new projects can easily connect to their desired markets as long as some entity is willing to provide the liquidity.

## How does PADSwap compare to other decentralized exchanges?

{% hint style="info" %}
Docs in progress
{% endhint %}

|                                          |                       PancakeSwap                      |                               SushiSwap                              |                        PADSwap                       |
| ---------------------------------------- | :----------------------------------------------------: | :------------------------------------------------------------------: | :--------------------------------------------------: |
| Swap fee distribution                    | <p>0.17% to LP providers<br>0.03% to devs' pockets</p> |        <p>0.25% to LP providers<br>0.05% to SUSHI holders</p>        | <p>0.25% to LP providers<br>0.05% to PAD backing</p> |
| Reward token tokenomics                  |                    Infinitely minted                   |                             Capped supply                            |                     Capped supply                    |
| Reward token backing                     |                          None                          |                                 None                                 |     Backed by the Vault of accumulated swap fees     |
| Multi-chain?                             |                        BSC only                        |                              Multi-chain                             |                      Multi-chain                     |
| Regular farms (earn native reward token) |                           Yes                          |                                  Yes                                 |                          Yes                         |
| Partner farms (earn other tokens)        |        <p>Partially<br>(you must stake CAKE)</p>       | <p>Partially<br>(earning half in SUSHI and half in other tokens)</p> |                          Yes                         |
| LP farms (stake LP, get more LP)         |                           No                           |                                  No                                  |                          Yes                         |
| Own cross-chain bridge                   |                           No                           |                                  No                                  |                          Yes                         |
| Own token launchpad                      |                           No                           |                                  No                                  |                          Yes                         |

## Contracts

{% tabs %}
{% tab title="BSC (BEP-20)" %}
* Router: [0x76437234D29f84D9A12820A137c6c6A719138C24](https://bscscan.com/address/0x76437234d29f84d9a12820a137c6c6a719138c24#code)
* Factory: [0xB836017ACf10b8A7c6c6C9e99eFE0f5B0250FC45](https://bscscan.com/address/0xb836017acf10b8a7c6c6c9e99efe0f5b0250fc45)
{% endtab %}

{% tab title="MOVR" %}
* Router: [0x790d4b443edB9ce9A8d1aEC585edd89E51132D2c](https://moonriver.moonscan.io/address/0x790d4b443edb9ce9a8d1aec585edd89e51132d2c)
* Factory: [0x760d2Bdb232027aB3b1594405077F9a1b91C04c1](https://moonriver.moonscan.io/address/0x760d2bdb232027ab3b1594405077f9a1b91c04c1)
{% endtab %}

{% tab title="GLMR" %}
* Router: [0x40F1fEF0Fe68Fd10ff904070ee00a7769EE7fe34](https://blockscout.moonbeam.network/address/0x40F1fEF0Fe68Fd10ff904070ee00a7769EE7fe34)
* Factory: [0x663a07a2648296f1A3C02EE86A126fE1407888E5](https://blockscout.moonbeam.network/address/0x663a07a2648296f1A3C02EE86A126fE1407888E5)
{% endtab %}
{% endtabs %}
