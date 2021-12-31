---
cover: ../.gitbook/assets/PAD.png
coverY: -28.333333333333357
---

# 🌺 $PAD

* **Name:** Lily Pad

**Symbol/Ticker:** ![](<../.gitbook/assets/image (3).png>) PAD

* **Max Supply:** 200 billion
* **Pre-mint:** 10 billion
* **Liquidity (PERMANENTLY LOCKED):** **400,000 BUSD** at start; **200,000 BUSD** in pre-minted PAD, **200,000 BUSD in TOAD donated by Snake and KingToad**
* **No Presale**
* **Fair Launch** (Devs only get 10% of the 0.13% drip per day, **NO TEAM TOKENS AT LAUNCH**)

The BEP-20 token PAD is a standard BEP-20 token with mint and burn functions, the mint function can only be used by the minter contract.

The minter mints new tokens(0.13% of the remaining supply there is to mint) and distributes them to the farms. All the remaining 180 billion tokens are going to be minted and distributed by the Minter contract. The minter contract will mint 0.13% of the remaining supply a day, by the second, and distribute those rewards to the farms and dev contract.

The dev contract will get 10% of those rewards, the remaining 90% are going to be distributed to the farms. The only address that is allowed to mint new tokens is the minter contract. The only parameters the developers can change in the minter contract are the % each farm gets from the daily mint and add/remove new farms. Developers have no incentive to alter the % they get from the minter, as this would be quickly spotted by the community and since the Minter contract will only mint 0.13% a day, they would lose more from the devaluation (due to lost of trust) of the pad and toad that they hold than that 0.13% is worth.

## Continuous Minter Formula / PAD drip

Let $$p$$ be the drip pool supply, $$d$$ the duration in seconds and $$r$$ the drip per second (0.13% per day and 86400 seconds per day), then the exponential decay of the drip pool is given by the function $$M$$:

$$
r = \dfrac{0.0013}{86400}
$$

$$
M(p, d) = p * (1 - r) ^ d
$$

The function $$M$$ calculates the remaining drip pool supply after $$d$$ seconds. PAD has a max supply of 200B tokens. There was an initial mint of 10B tokens, so $$P = 190\text{B}$$.

For example, if we want to calculate the remaining PAD in the drip pool after 1 year (31,536,000 seconds), we can solve $$M(190\text{B}, 31536000)$$, which gives us 118B PAD remaining in the drip pool after a year.

![Plot of minted PAD over time (ignores the 10B initial mint)](<../.gitbook/assets/image (2) (1).png>)

[The **Vault**](the-vault.md) stores pad backing, developers can add support for a new token to it, if a user wants to redeem the backing of PAD, the vault will burn that amount of PAD. Lowering PAD supply forever.

##
