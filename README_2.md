# Functions-Errors-ETH-AVAX

Simple smart contract project using require, assert, revert statements.

## Description

The SmartContractProject a Solidity smart contract that functions as a manager of single piece of data. It is made using the require, assert, and revert statements which helps in ensuring the integrity and validity of the data.

## Usage/Features

1. Allows the management of a single data value of uint256.
2. Validates data before updating, checking if the new data is not zero, different data value, and is less than current data which ensures its validity and integrity
3. It utilizes 3 statements (assert, require, revert) which is used in error handling, by preventing data modifications providing error messages if certain conditions are not met.

### Executing program

* Use any solidity compiler, I used remix IDE.
* Go to solidity compiler, and compile file.
* On the deploy & run transactions panel, click deploy.
* On the deployed contracts panel, look for setData, wherein you can modify the data value.

Feel free to set new data value and experiment!

### NOTE

* Look for the green check in every transaction that you make, if you see a green check it means that the transaction went through.

## Authors

Aaron Gabrielle A. Galera
email : 8214785@ntc.edu.ph


## License

Unlicensed.
