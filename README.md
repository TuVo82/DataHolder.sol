# DataHolder.sol
DataHolder.sol4
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract DataHolder {
    string public message;

    constructor(string memory _message) {
        message = _message;
    }

    function setMessage(string memory _newMessage) public {
        message = _newMessage;
    }
}
Refactor contract code
Add require for safety
Refactor storage logic
Improve readability
