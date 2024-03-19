# ShoeToken

**ShoeToken** is an ERC20-compatible token smart contract implemented in Solidity. It enables users to interact with a token representing ownership of virtual shoes. These shoes can be redeemed using the token balance, and their prices are determined based on different brands.

## Features

- **Minting**: The contract owner can mint new ShoeTokens and distribute them to specific addresses.
- **Burning**: Users can burn their ShoeTokens, reducing the total supply of tokens.
- **Redeeming Shoes**: Users can redeem virtual shoes of specific brands by spending ShoeTokens.
- **Transferring Tokens**: Users can transfer their ShoeTokens to other addresses.

## Token Details

- **Name**: ShoeToken
- **Symbol**: SHOE
- **Decimals**: 18

## Shoe Brands and Prices

- **Nike**: 200 SHOE
- **Adidas**: 150 SHOE
- **Puma**: 120 SHOE

## Functions

- **`mint(address recipient, uint256 amount)`:** Mint new ShoeTokens and send them to the specified recipient.
- **`burnTokens(uint256 amount)`:** Burn a specified amount of ShoeTokens.
- **`redeemShoes(string memory brand)`:** Redeem virtual shoes of a specific brand by spending ShoeTokens.
- **`transferTokens(address recipient, uint256 amount)`:** Transfer ShoeTokens to another address.

## Deployment

The contract should be deployed using a suitable Ethereum development environment such as Hardhat or Remix.

## Usage

1. **Minting Tokens**: The contract owner can mint new tokens and distribute them to users.
2. **Burning Tokens**: Users can burn their tokens if they no longer wish to hold them.
3. **Redeeming Shoes**: Users can redeem virtual shoes by spending their ShoeTokens.
4. **Transferring Tokens**: Users can transfer their ShoeTokens to other addresses.
