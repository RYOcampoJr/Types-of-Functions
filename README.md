# MetaTokenCu

This Solidity program defines an advanced ERC-20 token on the Ethereum blockchain, incorporating features from OpenZeppelin's ERC20, ERC20Burnable, and Ownable contracts. It showcases the creation of a cryptocurrency token with functionalities for minting, burning, and ownership management. 

## Description

This program is a smart contract written in Solidity, designed for the Ethereum blockchain. It leverages OpenZeppelin contracts to include the following features:

- A token with a name (`MetaTokenCu`), symbol (`MTCU`), and a maximum supply limit.
- Ownership management allowing only the owner to mint new tokens.
- A `mint` function to increase the total supply and an address's balance, with a check to ensure it does not exceed the maximum supply.
- An enhanced `burn` function allowing token holders to destroy their tokens, reducing the total supply.
- A `transferTokens` function for transferring tokens from the caller's address to another.

This contract extends the basic ERC-20 token functionalities with ownership and supply cap features, making it a more sophisticated example for developers interested in creating their own tokens with similar capabilities.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. Follow these steps:

1. Go to the Remix website at [https://remix.ethereum.org/](https://remix.ethereum.org/).
2. Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a `.sol` extension (e.g., `MetaTokenCu.sol`).
3. Copy and paste the provided Solidity code into the file.
4. To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to a compatible version (e.g., "0.8.20"), and then click on the "Compile MetaTokenCu.sol" button.
5. Once the code is compiled, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MetaTokenCu" contract from the dropdown menu, and then click on the "Deploy" button.
6. After deploying, you can interact with the contract by calling its `mint`, `burn`, and `transferTokens` functions. Select the deployed "MetaTokenCu" contract in the left-hand sidebar to see these functions and interact with them.

## Authors

- Sandeep Vashishtha

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.