# ERC20 Token Project Summary

## Project Overview
This repository contains a Foundry-based Ethereum project that implements a simple ERC20 token called "OurToken" (OT). The project demonstrates basic ERC20 token functionality using OpenZeppelin's battle-tested ERC20 implementation.

Cyfrin Updraft Soldity course: https://updraft.cyfrin.io/courses/solidity

## Network Compatibility

The deployment script is configured to work with:
- **Anvil/Local Network** (Chain ID: 31337): Uses hardcoded test private key
- **Live Networks**: Requires `PRIVATE_KEY` environment variable

## Foundry Documentation

https://book.getfoundry.sh/

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
