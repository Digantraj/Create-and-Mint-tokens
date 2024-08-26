# MyToken

MyToken is a simple ERC20 token implementation using OpenZeppelin's standard contracts. It allows the owner to mint new tokens and any holder to burn and transfer tokens. This smart contract is built using Solidity and is compatible with the Ethereum blockchain.

## Features

- **ERC20 Standard**: Implements the ERC20 token standard for fungible tokens.
- **Mintable**: The contract owner can mint new tokens to any address.
- **Burnable**: Any token holder can burn their own tokens, reducing the total supply.
- **Transferable**: Token holders can transfer tokens to other addresses.


## Functions

### `mint(address to, uint256 amount)`

Allows the owner to mint new tokens to a specified address.

- `to`: The address that will receive the minted tokens.
- `amount`: The number of tokens to mint.

### `burn(uint256 amount)`

Allows any token holder to burn a specified amount of their tokens.

- `amount`: The number of tokens to burn from the caller's balance.

### `transfer(address recipient, uint256 amount)`

Allows token holders to transfer tokens to another address.

- `recipient`: The address to transfer tokens to.
- `amount`: The number of tokens to transfer.

## Testing

To run tests, use HardHat's testing framework.

```bash
npx hardhat test
