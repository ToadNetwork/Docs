---
description: >-
  Details on security measures, access control, timelocks and flash loan
  attacks.
---

# Security

{% hint style="warning" %}
There are no guarantees of security! The cryptospace and DeFi is still inherently vulnerable and volatile.
{% endhint %}

## Bug Bounty Program

The DeFi space is constantly moving and new vulnerabilities are discovered and exploited by the minute.

If you find any vulnerabilities in Toads/PADSwaps smart contracts, please privately contact [contact@toad.network](mailto:contact@toad.network) or [@toad\_guy](https://t.me/toad\_guy) to disclose the vulnerability.

## Access Control

{% hint style="info" %}
This section is about the control on smart contracts. Governance of Toad.Network is done by the [toadao.md](../project/toadao.md "mention").
{% endhint %}

### PADSwap Factory and Router

There are no admin controls in PADSwaps factory and router contracts.

The only role in this PADSwap Factory and Router is OnlyOwner.\
All contracts are deployed by the same address 0xF4210B747e44592035da0126f70C48Cb04634Eac.

The keys to this address are held by DEVS Team.

None of the deployed contracts can be upgraded.\
OnlyOwner does not have the ability to change any aspects of the contracts.

### $PAD Minter

There are no admin controls to change the $PAD minters drip after deployment.

### $PAD Drip Distribution to PAD Farms

The $PAD minter drips to all PAD farms. The contract owners (KT and Snake) have the ability to change the percentage of the drip each farm gets. There is **no** control to actively mint or to increase the drip! The control is only on the the distribution of the drip. This allows the TOADao and ultimately the [team.md](../project/team.md "mention") to manage the PAD farm incentives. It is also possible to add or remove farms from the PAD drip distribution e.g. if a new farm is created or an old one is phased out.

### DPLP Rewards Drip

There are no admin controls to change the DPLP reward drip after deployment.

### Token Factory and LaunchPad

{% hint style="info" %}
The token factory and launch pad are still in the initial roll out face. The final amount of admin control on these is still to be defined.
{% endhint %}

## Multisigs

### The Vault "Buffer"

Token send towards the Vault are first send to a buffer from which they are periodically send to the Vault. Some are converted to whitelisted tokens in the process. For Moonriver and Moonbeam this buffer is already managed via a smart contract but on BSC this is done through a Gnosis Safe for the meantime until the same smart contract is also deployed to BSC. This Safe is a multisig wallet requiring 2/3 signatures to perform transactions. The signatures are held by KT and Snake from the [team.md](../project/team.md "mention") and one by SpadeTech (who performed the audit on BSC).

### Community Marketing Funds

Marketing initiatives are partly financed through community contributions. These contributions can be send towards a [Gnosis Safe](https://padswap.exchange/donate) on Moonbeam. This Safe is a multisig wallet requiring 2/3 signatures to perform transactions. The signatures are held by TOADao community members.

## Timelock

Toad.Network currently does not use [timelocks](../fundamentals/glossary.md#timelock) for smart contract changes but considers them a good practice and will consider using them in the future.

## Pause

Toad.Network's smart contracts do not provide any option to pause smart contracts. While a pause functionality can theoretically be used to prevent harm from smart contract users in case of an exploit, it can also be used in many ways contrary to user interests. In fact, we mainly see it used in the later way and are therefore against this practice.&#x20;

## Flash Loan Attacks

PADSwap itself does not offer any [flash loans](../fundamentals/glossary.md#flash-loan) and is therefore not vulnerable from the perspective of a flash loan provider. But [flash loan attacks](../fundamentals/glossary.md#flash-loan-attack) can be executed against any smart contract using the funds of a flash loan provided by a third party. Toad.Network's smart contracts do not have any explicit flash loan protection. If you see any flash loan attack vulnerability, please refer to our [#bug-bounty-program](control.md#bug-bounty-program "mention").
