---
title: Terminology
description: Terminology specific to Ocean Protocol.
---

## Ocean Network

Any EVM-compatible network where all[^1] the Ocean Protocol smart contracts ([keeper contracts](https://github.com/oceanprotocol/keeper-contracts)) are deployed. There can be many Ocean networks and you can use the Ocean Protocol in several EVM-compatible networks, including:

- the Ethereum Mainnet (also called the Main Ethereum Network)
- the Ocean [Pacific Main Network](/concepts/pacific-network/)
- various Ocean [test networks](/concepts/testnets/)

## Asset or Data Asset

Anything that can be registered with and made available via an Ocean Network. Examples include data sets, trained model parameters, pipelines, and data-cleaning services.

## Data Owner or Data Service Provider

Someone who has assets that they want to sell (or give away freely). An example is an almond distributor with 30 years of data about almond sales.

> Initially, most data owners or data service providers will also be the publishers of their own assets.

## Publisher

A service which mediates access to assets on behalf of data owners or data service providers.

> Initially, most publishers will also be the owners of the assets they publish.

## Consumer

Someone who wants assets. An example is a data scientist working at an economic think tank.

## Marketplace

A service where publishers can list what assets they have, and consumers can see what's available then buy it (or get it for free). Every marketplace has a database where they store metadata about the assets they know about (but not the assets themselves). An Ocean network can support many marketplaces.

## Verifier

A person or a software service that checks some steps in transactions. For example, a verifier might check to see if a cryptographic signature is valid and then get rewarded for doing so.

## Service Execution Agreement (SEA) or Service Agreement

A contract-like agreement between a publisher, a consumer, and a verifier, specifying what assets are to be delivered (from publisher to consumer), the conditions that must be met, and the rewards for fulfilling the conditions.

We published a blog post that explains SEAs in more detail:

- [Blog: Exploring the SEA: Service Execution Agreements](https://blog.oceanprotocol.com/exploring-the-sea-service-execution-agreements-65f7523d85e2)

## More Terminology

- See the page about Ocean's [Software Components](/concepts/components/).
- See the page about [wallets (and other Ethereum terminology)](/concepts/wallets/).

[^1]: The _Dispenser_ smart contract should only be deployed to testnets.
