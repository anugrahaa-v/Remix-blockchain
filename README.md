Simple Storage DApp

Overview

This is a basic blockchain project built using Solidity and Remix IDE.
It allows users to store a number on the blockchain and retrieve it.
This project is ideal for beginners who want to learn smart contracts, blockchain workflow, and interacting with contracts without using real Ethereum or MetaMask.

Features

Store a single number on the blockchain.
Retrieve the stored number.
Fully functional using Remix JavaScript VM — no MetaMask or real ETH needed.
Simple and beginner-friendly.

Tools & Technologies

Solidity — smart contract programming language
Remix IDE — for writing, compiling, and deploying contracts
JavaScript VM — local blockchain for testing
HTML/JS frontend (optional) — for connecting to the smart contract

How It Works
Deploy the Storage.sol smart contract on Remix using JavaScript VM.
Use the set(uint256 _num) function to store a number.
Use the get() or storedNumber functions to retrieve the stored number.

How to Run
Open Remix IDE
Create a new file Storage.sol and paste the contract code
Compile the contract → Solidity Compiler tab → Compile
Deploy → Deploy & Run Transactions tab → Environment: JavaScript VM
Interact:
Click set → input a number → click transact
Click get → see the stored number
