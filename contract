// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

/**
 * @title SimpleStorage
 * @dev A basic contract to store and retrieve a number.
 */
contract SimpleStorage {

    // This is a "state variable" stored permanently on the blockchain.
    uint256 private number;

    /**
     * @dev Stores a new number on the blockchain.
     * @param _newNumber The number to be stored.
     */
    function set(uint256 _newNumber) public {
        number = _newNumber;
    }

    /**
     * @dev Retrieves the currently stored number.
     * @return The stored number.
     */
    function get() public view returns (uint256) {
        return number;
    }
}
