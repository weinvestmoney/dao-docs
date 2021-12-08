# Protocol Design

The governance is designed on the Aragon optimistic governance protocol.

`Aragon Govern is software for creating and governing organizations such as DeFi projects, open source projects, gaming guilds, cooperatives, nonprofits, clubs, companies, and any other type of organization you can imagine. It's Aragon's implementation of ERC-3000, the standard for binding off-chain voting.`

View the complete source code on-chain. This is the govern executor address

{% embed url="https://etherscan.io/address/0x42a13915CB662AdE335Ba434d228df62AedE734A#code" %}

### Optimistic by design

Govern builds on the "Optimistic" concept, in which we assume actors are acting rationally and with good intentions, until proven otherwise. Actors with permissions in the DAO can submit actions, which can get executed after a defined time window. These can also be disputed with the chosen mechanism for resolving these challenge/response games, most likely a [subjective oracle](https://aragon.org/blog/snapshot), such as Aragon Protocol. These actions can also be vetoed by an actor with the corresponding permissions as long as they haven't been executed.

[https://docs.aragon.org/govern/docs/guides/core-concepts#optimistic-by-design](https://docs.aragon.org/govern/docs/guides/core-concepts#optimistic-by-design)
