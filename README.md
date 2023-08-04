# avax-mod-4
# DegenToken Smart Contract

This project contains a smart contract for DegenToken (DGN), an ERC20 token built with Solidity.

## Overview

The smart contract provides functionality for basic ERC20 operations with some additional features. Users can mint, transfer, and redeem DegenTokens. The contract also contains a store where users can redeem their tokens for items.

## Prerequisites

- Solidity 0.8.18
- Node.js
- npm
- Hardhat
- OpenZeppelin Contracts


## Usage

Once the smart contract is deployed (using Hardhat or Truffle), you can interact with it as follows:

mint(address recipient, uint256 amount): This function allows the contract owner to mint new DegenTokens.

transfer(address recipient, uint256 amount): This function allows a DegenToken holder to transfer a specified amount of their tokens to another address.

redeem(uint256 amount): This function allows a DegenToken holder to redeem (burn) a specified amount of their tokens.

checkBalance(address account): This function allows anyone to check the token balance of a specific account.

approve(address spender, uint256 amount): This function allows a DegenToken holder to approve another address to spend a specified amount of tokens on their behalf.

stationerystoreitems(): This function displays the items available for purchase in the store.

redeemTokens(uint8 _userSelection): This function allows users to redeem their tokens for specific items in the store.

# License

This project is licensed under the terms of the MIT license.






