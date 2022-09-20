---
title: "Block Explorer"
icon: "https://raw.githubusercontent.com/mobilecoinofficial/awesome-mobilecoin/main/directory/0071_Block_Explorer/blockexplorer.png"
description: "Transaction search engine"
category: "Developer Tools"
developer: "MobileCoin"
developerSite: "https://block-explorer.mobilecoin.foundation/"
gitHub: "https://github.com/mobilecoinfoundation/mobilecoin/tree/2f90154a445c769594dfad881463a2d4a003d7d6/mobilecoind/clients/python/blockchain_explorer"
---
## What’s a block explorer? 
A block explorer is a blockchain search engine that allows you to search for a particular piece of information on the blockchain. The activities carried out on crypto blockchains are known as transactions, which occur when cryptocurrencies are sent to and from wallet addresses. Each transaction is recorded onto a digital ledger, known as a blockchain. Blocks on the blockchain are collections of transactions that were processed and approved by a group of third-parties known as validators.

A block explorer is an online tool to view all transactions that have taken place on the blockchain, the transaction growth, and the activity on blockchain addresses, among other useful information. You can think of it as a window into the blockchain world, giving you the opportunity to observe what’s happening on it.

## Why use a Block Explorer?
Anytime you buy, sell, send, or receive MobileCoin, you can utilize the block explorer to check on the status of your transactions. Once you initiate a transaction, you should receive an automatically-generated transaction hash and can use the hash to look up details of the payment and whether it was successful.

## Where is MobileCoin's block explorer?
Currently, the MobileCoin Foundation's [Block Explorer](https://block-explorer.mobilecoin.foundation/) is an open source block explorer providing detailed blockchain data across the MobileCoin Mainnet. This block explorer also supports Tor and is tracking-free.

# Why does it look like the Matrix?
Our block explorer is in it's first version. We are funding an effort to build a new block explorer, and we are openly inviting all software developers in to apply and work on this project. 

## Where can I apply?
You can apply to build the block explorer on our [Gitcoin bounty page](https://gitcoin.co/issue/mobilecoinofficial/developer-grants/1/100028771).

At a high level, the goal is to create a new block explorer which integration partners can run off of their full-service wallet, using the application of their private keys to query the block explorer for relevant data about transactions

Right now, the block explorer runs off of the [mobilecoind](https://github.com/mobilecoinfoundation/mobilecoin/tree/master/mobilecoind) wallet, but we are deprecating this, so partners do not want to run an entirely separate wallet to run the block explorer.

The asks are to reimplement the block explorer so that:

1.  It uses full-service as the backend and interfaces to the [Full Service JSONRPC API](https://developers.mobilecoin.com/guides/full-service-api)
2.  It supports new features that are necessary for integration partners (and we can get into this more specifically)
3.  It has a more modern and intuitive interface than the current implementation.

