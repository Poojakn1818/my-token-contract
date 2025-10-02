## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

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
# SimpleToken (STK) - ERC20 Token

A basic ERC20 token deployed on Ethereum Sepolia testnet using Foundry.

## Deployment Information
- **Contract Address:** 0x63d42afE4CECF3BF2009a8c1296bc67521Bd956C
- **Network:** Sepolia Testnet
- **Token Name:** SimpleToken
- **Symbol:** STK
- **Initial Supply:** 1,000,000 STK

## Quick Start
1. Clone repository
2. Install Foundry: `curl -L https://foundry.paradigm.xyz | bash`
3. Install dependencies: `forge install`
4. Run tests: `forge test`

## Links
- [Contract on Etherscan](https://sepolia.etherscan.io/address/0x63d42afE4CECF3BF2009a8c1296bc67521Bd956C)
- [Deployment Transaction](https://sepolia.etherscan.io/tx/0x91fb6ec6fe5520ba989007aba4fbb2c131be88afbebbaef4630f653f7017da71)
- [Transfer Transaction](https://sepolia.etherscan.io/tx/0x792ce44191a1bf27bdc5baa7250c02a9b844baa6be360f2a2e740e424ef7e8c0)
