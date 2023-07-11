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
This program is a simple contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a three function that inputs the values, checks the condition using error handling statement and executes the function.

The check_require function sets a value but requires the input value to be greater than 0 for this it uses require() for input validation, If the 
value is less than 0 than ot returns string value "Input is valid".

The check_assert function takes two uint value and their sum is stored in another variable. Now if the sum is less than 255, The function returns 
"sum is valid" string, for this we use assert() for validation here.

The check_revert function takes two uint value and their sum is stored in another variable. Now if the sum is greater than 0 and less than 255, The function returns "no overflow" string and sum value, for this we use revert() for validation here. 

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "errorhandlingcontract" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling any of the three function to set the value, check_require function to perform the require statement, check_assert function to perform the assert statement and check_revert function to perform the revert function. you just need to enter the values and then click on call. 

## Author

Ankit kumar

## License

This project is licensed under the MIT License - see the LICENSE file for details
