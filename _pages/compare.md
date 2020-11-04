---
layout: page
title: Basic Feature Comparison
permalink: /compare/
---


| Node                  | Supported Hardware               | Electrum Server | Lightning | CoinJoin   | Block Explorer | Mempool Viewer | Dojo |
|-----------------------|----------------------------------|-----------------|-----------|------------|----------------|----------------|------|
| [Bitcoin Core](https://node.guide/core/)        | Any computer or laptop           | No              | No        | None       | No             | No             | No   |
| [myNode One](https://node.guide/plug-and-play/#mynode-one)            | RPi 4                            | Electrs         | LND       | Whirlpool  | Yes            | Yes            | Yes  |
| [myNode DIY Community](https://node.guide/do-it-yourself/#mynode)  | Rock64, RockPro 64, RPi 4 and VM | Electrs         | LND       | Whirlpool  | Yes            | No             | Yes  |
| [myNode DIY Premium](https://node.guide/do-it-yourself/#mynode)    | Rock64, RockPro 64, RPi 4 and VM | Elecrs          | LND       | Whirlpool  | Yes            | Yes            | Yes  |
| [Node One](https://node.guide/plug-and-play/#nodl-one)              | RockPi 4                         | Electrs         | LND       | Whirlpool  | Yes            | No             | Yes  | 
| [Nodl Dojo](https://node.guide/plug-and-play/#nodl-dojo)             | RockPi 4                         | Electrs         | LND       | Whirlpool  | Yes            | No             | Yes  |
| [RoninDojo](https://node.guide/do-it-yourself/#ronindojo)             | Odroid N2, RockPro 64 and RPi    | Electrs         | None      | Whirlpool  | Yes            | No             | Yes  |
| [RaspiBlitz](https://node.guide/plug-and-play/#raspiblitz)            | RPi 4                            | Electrs         | LND       | JoinMarket | Yes            | Yes            | No   |
| [RaspiBlitz DIY](https://node.guide/do-it-yourself/#raspiblitz)        | RPi 3 and RPi 4                  | Electrs         | LND       | JoinMarket | Yes            | Yes            | No   |
| [Start9 Labs Embassy](https://node.guide/plug-and-play/#start9-embassy)   | RPi 4                            | None            | None      | None       | Yes            | No             | No   |
| [Umbrel](https://node.guide/do-it-yourself/#umbrel)                | RPi 4 and VM                     | Electrs         | LND       | None       | Yes            | No             | No   |


### Glossary

[Electrum Server](https://github.com/romanz/electrs) indexes the entire Bitcoin blockchain, and the resulting index enables fast queries for any given user wallet, allowing the user to keep real-time track of balances and transaction histories. Since it runs on the user's own machine, there is no need for the wallet to communicate with external Electrum servers, thus preserving the privacy of the user's addresses and balances.

[Lightning](https://www.bitcoinqna.com/lightning) is scaling solution built on top of the Bitcoin protocol. It facilitates smaller, near instant payments between users at very low cost. It prevents the need for every transaction made to take place on the Bitcoin ‘base layer’ whilst still ensuring that the value being transacted abides by the core rules and values of the Bitcoin network.

[CoinJoin](https://www.bitcoinqna.com/coinjoin) is an on chain privacy solution for Bitcoin. It is designed to break the [common input ownership heuristic](https://en.bitcoin.it/wiki/Common-input-ownership_heuristic) which assumes that all inputs to a transaction belong to the same entity. Bitcoin addresses aren't directly tied to real identities but anyone with enough time and resources (like chain analysis firms) can start to make these links by watching Bitcoin's public ledger. Coinjoin helps prevent this.

A [Block Explorer](https://explorer.btc21.org/) is a website or application that allows you to find the details of any block on the blockchain. You can find data such as number of transactions in a block, sender address, recipient address, fees paid, amount sent, block height and block time. By using an explorer hosted on your own node you can query this data privately.

A [Mempool Viewer](https://mempool.space) is a website or application that allows you to see the current state of the Bitcoin mempool. Most will also allow you to enter transaction ID's to track its position. By using a mempool viewer hosted on your own node you can query this data privately.

[Dojo](https://samouraiwallet.com/dojo) is the backend server required to use the Samourai Wallet in the most private way. It provides simple wallet connection via a QR scan.

***
