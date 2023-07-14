# ErrorHandling Contract

This is a Solidity Errorhandling  contract that will show different error handling techniques using `require`,`assert`, `revert`, and  functions.

## License

This contract is using the MIT License.

## Prerequisites

- Solidity ^0.8.17

## Description

The `ErrorHandling` contract has three functions:

### 1.testAssert(uint num)

.This function demonstrates the usage of the `assert` function.

.It is used for internal consistency checks and to verify critical conditions.

.It takes a `num` parameter and checks if it is not equal to zero using the `assert` statement.

.If the condition fails, it will automatically triggers an "Internal error" and aborts the execution.

### 2.divide(uint _numerator, uint _denominator)

 .This function demonstrates the usage of the `revert` function.
 
 .It is used to revert contract execution and provide error messages.
 
 .It has two parameters numerator and denominator to performs division.
 
 .If the numerator is less than denominator it reverts the transaction with an error message stating that the numerator should be greater than the denominator.
 
 .If the condition met, it returns the result of the division.

### 3.mult(uint a)

.This function demonstrates the usage of the `require` function.

.It is used to revert contract execution and provide error messages.

.It will trigger an exceptions and revert changes made to the blockchain.

.It is used to validate conditions and inputs in a contract.

.If the condition provided to require() evaluates to false, the contract execution will immediately stop, and any changes made to the blockchain will be reverted. 

## Usage

1. Make sure you have installed Solidity ^0.8.17
3. Compile and deploy the `ErrorHandling` contract to a supported Ethereum network.
4. Interact with the deployed contract by calling the available functions and providing the required parameters.
