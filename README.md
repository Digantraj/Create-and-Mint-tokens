# MyToken Smart Contract

`MyToken` is an ERC20-compatible token smart contract implemented in Solidity. It utilizes OpenZeppelin's libraries to provide standard token functionalities, including minting and burning, as well as ownership management.

## Overview

The `MyToken` smart contract offers essential ERC20 token features, such as transferring tokens, minting new tokens, and burning existing tokens. It uses OpenZeppelin's `Ownable` module to manage access control, ensuring only the owner can mint tokens.

## Features

- **ERC20 Standard Compliance**: Implements all standard ERC20 functions.
- **Minting**: The contract owner can mint new tokens to any address.
- **Burning**: Any user can burn their own tokens.
- **Ownership**: The `Ownable` module ensures that certain actions are restricted to the owner.

## Prerequisites

To interact with this contract, you will need:

- [Remix IDE](https://remix.ethereum.org/) for contract deployment and interaction.

## Deployment

To deploy the `MyToken` contract using Remix IDE:

1. **Open Remix IDE**: Visit [Remix IDE](https://remix.ethereum.org/).

2. **Create a New File**: In Remix IDE, create a new file and paste the smart contract code into this file.

3. **Compile the Contract**:
   - Ensure the compiler version is set to `0.8.24` or a compatible version.
   - Click on the "Solidity Compiler" tab and then click "Compile" to compile the contract.

4. **Deploy the Contract**:
   - Go to the "Deploy & Run Transactions" tab.
   - Select the "Remix VM (Cancun)" environment for local testing or use the default environment settings if deploying to a live network.
   - Choose the contract from the dropdown and click "Deploy".
   - Confirm the deployment through the Remix interface.

5. **Interact with the Contract**: Once deployed, you can interact with the contract directly from Remix's "Deploy & Run Transactions" tab.



## Authors

- **Digant Raj**  
  GitHub: [@Digant](https://github.com/Digantraj)

## License

This project is licensed under the MIT License.
