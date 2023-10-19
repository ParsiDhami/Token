# MyToken

MyToken is a simple Ethereum-based token contract that allows for minting and burning tokens.

## Overview

MyToken is a basic smart contract that provides the following functionality:

1. **Token Information**: Public variables to store the details about the coin, including the Token Name, Token Abbreviation, and Total Supply.

2. **Token Balances**: A mapping of addresses to token balances (address => uint) to keep track of the token holdings of different addresses.

3. **Mint Function**: A minting function that increases the total supply and adds tokens to the balance of a specified address.

4. **Burn Function**: A burning function that decreases the total supply and subtracts tokens from the balance of a specified address. This function includes conditionals to ensure that the balance of the address is sufficient to burn the specified amount.

## Token Details

- **Token Name**: META
- **Token Abbreviation**: MTA
- **Total Supply**: 0

## Usage

### Mint Tokens

To mint tokens, use the `mint` function. Provide the recipient's address and the number of tokens to mint.

## Burn Tokens
To burn tokens, use the burn function. Provide the recipient's address and the number of tokens to burn.

# example - 
myTokenInstance.burn(addressToBurnTokensFrom, 50);

Copy code
function burn(address _address, uint _value) public

```solidity
function mint(address _address, uint _value) public
