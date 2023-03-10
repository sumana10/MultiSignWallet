# MultiSignWallet

 This is the code for a smart contract called MultiSigWallet which implements a multi-signature wallet. 
 
## Features

- The contract allows multiple owners to submit and confirm a transaction before it is executed. 
- The contract has several events that are emitted when a deposit is made, a transaction is submitted, confirmed, revoked or executed. 
- The contract has several public variables such as an array to store the owners, a mapping to check if a user is an owner, a variable to store the number of confirmations required before a transaction is executed. 
- It also has a struct to store the transaction details, and several mappings to check the confirmations of the transaction. 
- The contract has several modifiers to check if the transaction exists, if it is executed or confirmed, and if the user is an owner. 
- The contract also has a constructor to initialize the contract and several functions to deposit ETH, submit, confirm, revoke and execute a transaction. 
- The contract also has a fallback function to receive ether.

## 🛠 Skills
Solidity.

## Authors

- [@sumana](https://www.github.com/sumana10)

