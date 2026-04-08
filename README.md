# NumberStorage.sol
JadeNguyen
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NumberStorage {
    uint public number;

    function setNumber(uint _num) public {
        number = _num;
    }
}
Clean up code
Simplify contract flow
Add input validation
Update deployment config
