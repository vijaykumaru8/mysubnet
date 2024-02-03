# Vault Contract

## Description
The Vault contract is designed to securely manage the deposit and withdrawal of ERC20 tokens within a decentralized system. It provides functionalities for users to deposit tokens, receive shares representing their ownership within the Vault, and withdraw tokens based on the shares they hold.

## Features
- Deposit tokens into the Vault in exchange for shares.
- Withdraw tokens from the Vault by burning shares.
- Efficiently calculates shares based on the deposited amount and total supply of shares.
- Implements ERC20 token interface to interact with tokens.
- Ensures security by using SafeMath for arithmetic operations.

## How to Use
1. **Deposit Tokens**: Call the `deposit` function by providing the amount of tokens you wish to deposit.
2. **Withdraw Tokens**: Call the `withdraw` function by providing the number of shares you wish to burn.

## Deployment
The Vault contract should be deployed on a compatible Ethereum Virtual Machine (EVM) such as Ethereum or a Subnet network.

## License
This contract is licensed under the MIT License.

---

# ERC20 Contract README

## Description
The ERC20 contract implements the ERC20 token standard, providing functionalities for managing and transferring tokens within a decentralized network. It serves as the base contract for creating and managing ERC20 tokens.

## Features
- Minting new tokens.
- Burning existing tokens.
- Transferring tokens between addresses.
- Approving and managing allowances for token spending.

## Properties
- **Name**: The name of the token contract.
- **Symbol**: The symbol or ticker of the token contract.
- **Decimals**: The number of decimal places used in token balances.

## How to Use
1. **Transfer Tokens**: Call the `transfer` function with the recipient address and the amount of tokens.
2. **Approve Spending**: Call the `approve` function to authorize a spender to withdraw tokens from your account.
3. **Transfer From**: Call the `transferFrom` function by an approved spender to transfer tokens on your behalf.
4. **Mint Tokens**: Call the `mint` function to create new tokens.
5. **Burn Tokens**: Call the `burn` function to remove existing tokens from circulation.

## Deployment
The ERC20 contract should be deployed on a compatible Ethereum Virtual Machine (EVM) such as Ethereum or a Subnet network.

## License
This contract is licensed under the MIT License.

## Author

vijaykumarvijaykumar48@gmail.com
