# Simple ERC-20 Token (Foundry)

This repository contains a high-quality, audited-standard implementation of an ERC-20 token using the OpenZeppelin library. It is designed for developers looking to understand the core mechanics of Ethereum-based assets while following industry best practices.

## Features
* **Standard Compliant:** Fully compatible with the ERC-20 standard.
* **Security:** Utilizes OpenZeppelin's battle-tested `ERC20.sol` and `Ownable.sol`.
* **Foundry Powered:** Set up for rapid development, testing, and deployment.

## Prerequisites
* [Foundry](https://book.getfoundry.sh/getting-started/installation) installed.
* Basic understanding of Solidity.

## Usage
1. **Build:** `forge build`
2. **Test:** `forge test`
3. **Deploy:** `forge create --rpc-url <your_rpc_url> --private-key <your_private_key> MyToken.sol:MyToken`

## License
MIT
