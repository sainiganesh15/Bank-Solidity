# Bank Smart Contract

This is a smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. This contract allows users to deposit and withdraw funds, and also provides the owner of the contract with the ability to withdraw funds from the contract.

## Features

- Depositing funds: Users can deposit funds into the contract by calling the `deposit()`function. The minimum deposit amount is 10 wei.
- Withdrawing funds: Users can withdraw funds from the contract by calling the `withdraw(_amount)` function, where _amount is the amount of funds to be withdrawn.
- Checking balance: Users can check their balance in the contract by calling the `getbalance()` function.
- Checking contract balance: The owner of the contract can check the contract balance by calling the `getcontractbalance()` function.
- Withdrawing contract funds: The owner of the contract can withdraw funds from the contract by calling the `withdrawFunds(_amount)` function, where _amount is the amount of funds to be withdrawn.


## License

This smart contract is licensed under the MIT License, which means anyone can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of it, under the condition that they include the same license in any derivative works.
