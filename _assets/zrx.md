---
title: ZRX Token
category: asset
sidebar:
  nav: "0x"
---

The Ethereum utility token for the [Øx protocol]({{ "asset/0x" | absolute_url }}).

## Utility of ZRX

The Øx protocol supports two kinds of exchanges:
+ point-to-point, between two users who know eachother
+ broadcast, between a market Maker and anyone who wants to fill the order

Both types of exchange are made possible by an Ethereum smart contract, deployed to the blockchain.  To create or fill either type of order, the only fees are the gas costs of interacting with the smart contracts.

A **relay** is a service provider that aggregates and organizes Øx broadcast transactions.  The relay connectors Makers (order-creators) with Takers (order-fillers) and provides a convenient interface for trading.  In exchange for these services, the Øx protocol enables relays to charge a fee in ZRX.

Initially, this will mean that relay users will need to buy and hold some ZRX in their wallet in order to trade on the platform.  Eventually, the relays will handle procurement of ZRX for the users "in the background" and the user won't have to manage ZRX tokens manually.

It is also mentioned in the [Øx Whitepaper][0x-whitepaper] that ZRX will have a function as a proof-of-stake governance token for voting on changes to the network.

[0x-whitepaper]: https://0xproject.com/pdfs/0x_white_paper.pdf
