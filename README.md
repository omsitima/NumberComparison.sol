# NumberComparison.sol
How to deploy a contract on Base Chain NumberComparison.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract NumberComparison {
    function compare(uint a, uint b) public pure returns (string memory) {
        if (a > b) {
            return "a is greater";
        } else if (a < b) {
            return "b is greater";
        } else {
            return "equal";
        }
    }
}
