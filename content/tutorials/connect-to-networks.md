---
title: Connect to Ocean-Related Networks
description: Learn how to connect to the Pacific network, Nile testnet and other Ocean-related networks in your browser with MetaMask.
---

## Connect to the Pacific Network

Here are the parameters you might need to connect to the [Pacific Network](/concepts/pacific-network/):

| Parameter          | Value                                                      |
| ------------------ | ---------------------------------------------------------- |
| RPC URL (required) | `https://pacific.oceanprotocol.com`                        |
| ChainID            | `846353` (decimal for MetaMask) or `0xcea11` (hexadecimal) |
| Symbol             | Whatever you like, e.g. `PACIFIC ETH`                      |
| Nickname           | Whatever you like, e.g. `Pacific`                          |

In MetaMask, click on the network name then click on `Custom RPC` in the drop-down list. Scroll down to the `New Network` section. Enter the above RPC URL. You don't need to add a port number to the end of the RPC URL. Enter the ChainID, Symbol and Nickname if you like. See the [MetaMask docs about how it uses the ChainID](https://metamask.github.io/metamask-docs/Main_Concepts/Sending_Transactions).

If you're using [Barge](https://github.com/oceanprotocol/barge) to run a local Pacific node, you can connect to that local Pacific node at RPC URL [http://localhost:8545](http://localhost:8545) (called "Localhost 8545" in MetaMask). You can configure that local Pacific node by editing the files in the `barge/networks/pacific/config/` directory.

## Connect to the Nile Testnet

Here are the parameters you might need to connect to the [Nile Testnet](/concepts/testnets/#the-nile-testnet):

| Parameter          | Value                                                   |
| ------------------ | ------------------------------------------------------- |
| RPC URL (required) | `https://nile.dev-ocean.com`                            |
| ChainID            | `8995` (decimal for MetaMask) or `0x2323` (hexadecimal) |
| Symbol             | Whatever you like, e.g. `NILE ETH`                      |
| Nickname           | Whatever you like, e.g. `Nile Testnet`                  |

In MetaMask, click on the network name then click on `Custom RPC` in the drop-down list. Scroll down to the `New Network` section. Enter the above RPC URL. You don't need to add a port number to the end of the RPC URL. Enter the ChainID, Symbol and Nickname if you like. See the [MetaMask docs about how it uses the ChainID](https://metamask.github.io/metamask-docs/Main_Concepts/Sending_Transactions).

If you're using [Barge](https://github.com/oceanprotocol/barge) to run a local Nile node, you can connect to that local Nile node at RPC URL [http://localhost:8545](http://localhost:8545) (called "Localhost 8545" in MetaMask). You can configure that local Nile node by editing the files in the `barge/networks/nile/config/` directory.

## Connect to a Local Spree Testnet or Ganache-Based Testnet

When using [Barge](https://github.com/oceanprotocol/barge) to run a purely-local testnet (Spree or Ganache-based), you can connect to a local node at RPC URL [http://localhost:8545](http://localhost:8545) (called _Localhost 8545_ in MetaMask).
