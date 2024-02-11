# MyToken Smart Contract

## Overview

This repository contains the source code for the `MyToken` smart contract, which is an ERC20-compliant token deployed on the Ethereum blockchain. This token is named "Gaming Token" with the symbol "GT". The contract inherits functionalities from the OpenZeppelin ERC20 implementation and also includes an `Ownable` contract to manage ownership.

## Features

The `MyToken` contract provides the following features:

1. **Token Initialization**: Upon deployment, 500 tokens with 0 decimal places are minted and assigned to the contract deployer.

2. **Mint Tokens**: The contract owner (deployer) can mint additional tokens for a specified address using the `mintTokens` function.

3. **Burn Tokens**: Token holders can burn a specified amount of their tokens using the `burnTokens` function.

4. **Transfer Tokens**: Token holders can transfer tokens to another address using the `transferTokens` function.

5. **View Total Supply**: The `getTotalSupply` function allows anyone to view the total token supply.

6. **View Token Decimals**: The `getTokenDecimals` function enables users to view the number of decimal places used by the token.

## Usage

To use this contract, deploy it to an Ethereum-compatible blockchain network. After deployment:

- You can interact with the contract using any Ethereum wallet or by calling its functions from another smart contract.
- The contract owner can mint additional tokens, burn tokens, and transfer tokens as needed.
- Token holders can transfer tokens to other addresses or burn their own tokens.


## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

