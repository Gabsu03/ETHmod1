## This is the code that i've created:
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;
 contract SmartContractProject{
    uint256 public Amount;
    function setAmount(uint256 _amount)
    public{
        require(_amount != 0, "Amount cannot be zero");
        assert(_amount != Amount);
        if (_amount < Amount) {
            revert("New Amount must be greater than current amount");
        }

    Amount = _amount;
    } 
 }