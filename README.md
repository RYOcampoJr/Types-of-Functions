# ERC20-Token

This Solidity program defines a basic ERC-20-like token on the Ethereum blockchain. It demonstrates creating a smart contract for a cryptocurrency token, including functionalities for minting and burning tokens. This contract is a foundational piece for anyone looking to understand or develop their own tokens on Ethereum.

## Description

This program is a smart contract written in Solidity, designed for the Ethereum blockchain. It includes the following features:

- A token with a name, symbol, and total supply.
- A mapping of addresses to their respective balances.
- A `mint` function to increase the total supply and an address's balance.
- A `burn` function to decrease the total supply and an address's balance, with checks to ensure the address has enough balance to burn.

This contract serves as a basic example of a token contract, providing a clear starting point for more complex token implementations or other blockchain-based projects.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. Follow these steps:

1. Go to the Remix website at [https://remix.ethereum.org/](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a `.sol` extension (e.g., `MetaToken.sol`).
3. Copy and paste the provided Solidity code into the file.
4. To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to a compatible version (e.g., "0.8.18"), and then click on the "Compile MyToken.sol" button.
5. Once the code is compiled, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.
6. After deploying, you can interact with the contract by calling its `mint` and `burn` functions. Select the deployed "MetaTokenCu" contract in the left-hand sidebar to see these functions and interact with them.

## Authors

- Sandeep Vashishtha

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.# ETH-MyToken