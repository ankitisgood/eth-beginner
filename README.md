# solidity create a token Assessment
This repository is for the project assessment of the project : solidity beginner course of Metacrafters academy . 

## Problem Statement

create a contract together to fulfill the following requirements:

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5. Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

## Description
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a three function one for mapping, second for mining and third for burning the token.

The mapping function maps the address with balances.

The mint function is used to mint the nft and add the minted amount to total_supply and balances of the address provided.

The burn function is used to burn the nft that we have minted and subtract the burn amount from total_supply and balances of the address provided.
Here, we have provided a if statement to check balance is greater than the value to be burnt, if balance is less than value than the further code will not execute.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by passing the address. call any of the three function and set the value, and you can burn, mint or check the balance of your NFT.

## Author

Ankit kumar

## License

This project is licensed under the MIT License - see the LICENSE file for details
