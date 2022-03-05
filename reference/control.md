# Admin Control

{% hint style="info" %}
This section is about the control on smart contracts. Governance of Toad.Network is done by the TOADao.
{% endhint %}

## Controls

### PADSwap Factory and Router

There are no admin controls in PADSwaps factory and router contracts.

### $PAD Minter

There are no admin controls to change the $PAD minters drip after deployment.

### $PAD Drip Distribution to PAD Farms

The $PAD minter drips to all PAD farms. The contract owners (KT and Snake) have the ability to change the percentage of the drip each farm gets. 
There is **no** control to actively mint or to increase the drip!
The control is only on the the distribution of the drip.
This allows the TOADao and ultimately [team.md](../project/team.md "mention") to manage the PAD farm incentives.
It is also possible to add or remove farms from the PAD drip distribution e.g. if a new farm is created or an old one is phased out.

### DPLP Rewards Drip

There are no admin controls to change the DPLP reward drip after deployment.

### Token Factory and LaunchPad

{% hint style="info" %}
The token factory and launch pad are still in the initial roll out face. The final amount of admin control on these is still to be defined.
{% endhint %}

## Multisigs

### The Vault "Buffer"

Token send towards the Vault are first send to a buffer from which they are periodically send to the Vault. Some are converted to whitelisted tokens in the process. For Moonriver and Moonbeam this buffer is already managed via a smart contract but on BSC this is done through a Gnosis Safe for the meantime until the same smart contract is also deployed to BSC. This Safe is a multisig wallet requiring 2/3 signatures to perform transactions. The signatures are held by KT and Snake from [team.md](../project/team.md "mention") and one by SpadeTech (who performed the audit on BSC).

### Community Marketing Funds

Marketing initiatives are partly financed through community contributions. These contributions can be send towards a [Gnosis Safe](https://padswap.exchange/donate) on Moonbeam. This Safe is a multisig wallet requiring 2/3 signatures to perform transactions. The signatures are held by TOADao community members.

## Timelock

Toad.Network currently does not use timelocks for smart contract changes but considers them a good practice and will consider using them in the future.