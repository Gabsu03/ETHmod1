// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract AssertionExample {
    uint256 public value;

    constructor(uint256 _initialValue) {
        value = _initialValue;
    }

    function setValue(uint256 _newValue) external {
        // Example of require statement
        require(_newValue != value, "New value must be different");

        // Example of assert statement
        assert(_newValue > 0);

        // Example of revert statement
        if (_newValue > 100) {
            revert("New value must be less than or equal to 100");
        }

        value = _newValue;
    }
}