// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

/*
Simple HelloWorld Smart Contract
For learning Web3 development
*/

contract HelloWorld {
    string public message = "Hello Web3";

    // function untuk menampilkan pesan
    function getMessage() public view returns (string memory) {
        return message;
    }
}

# README.md
This repository demonstrates a basic HelloWorld smart contract built with Solidity for learning Ethereum and Web3 development.
