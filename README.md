# nomikai 飲み会
> `SushiNomikai is the coolest party in town. You come in with some Sushi and stake (xSushi) to vote on party matters, like what food gets served. You can leave anytime with your fair share of party food.`

![sushimol](https://i.imgur.com/Y8zntuS.png)

[Moloch DAO v2](https://github.com/MolochVentures/moloch) is a minimal voting smart contract with the ability to `ragequit()` and exit membership with a fair share of pooled capital.

`SushiNomikai` is a fork of this org. code with the following extensions & optimizations:

* Sushi holders can stake and get Moloch shares equal to `xSushi` equivalent (which is wrapped into guild bank).
* Similarly, `xSushi` can stake directly into Moloch shares.
* DAO proposal functions are optimized for gas efficiency. 
* DAO can call any other contract using an embedded  [`Minion`](https://github.com/raid-guild/moloch-minion), like pre-approved `Aave` contracts for `aXSUSHI` deposits.
