# Abhibth09-Types-of-Functions---ETH-AVAX_Module3

# Overview
Token1 is an ERC20-compliant token smart contract built using Solidity. This token contract allows the owner to mint new tokens and any user to burn their tokens or transfer them to other addresses. It leverages the OpenZeppelin library for secure and reliable implementations of the ERC20 standard and ownership functionality.

# Features
Minting: The contract owner can mint new tokens to any address.
Burning: Any user can burn their tokens, reducing the total supply.
Transferring: Users can transfer tokens to any address.

# Contract Details
Name: Token1
Symbol: PTH

# Getting Started

# Prerequisites
Node.js
npm (Node Package Manager)
Hardhat (Ethereum development environment)
Remix IDE (for interaction with the contract)

# Installation
Clone the repository:

git clone https://github.com/yourusername/token1-project.git
cd token1-project

Install the project dependencies:

npm install

Start a local blockchain using Hardhat:

npx hardhat node

Testing
Run the contract tests:

npx hardhat test

Deployment
Deploy the Token1 smart contract to the local Hardhat network:

npx hardhat run scripts/deploy.js --network localhost

# Interacting with the Contract using Remix
Open the Remix online IDE in your browser.
In the "File Explorer" section, create a new file and paste the contents of Token1.sol into it.
Compile the contract.
Select the "Deploy & Run Transactions" tab.
Choose "Dev - Hardhat Provider" as the environment.
Deploy the contract by clicking the "Deploy" button.
Interact with the contract using the provided functions (mint, burn, exampleTransfer).
Contract Functions

# Mint Tokens
mint(address to, uint256 amount): Allows the contract owner to mint new tokens to a specified address.

# Burn Tokens
burn(uint256 amount): Allows any user to burn a specified amount of their tokens.

# Transfer Tokens
exampleTransfer(address to, uint256 amount): Demonstrates how to transfer tokens from the sender to a specified address.


# Minting Tokens

token1.mint("0x123...", 100);

# Burning Tokens

token1.burn(50);

# Transferring Tokens

token1.exampleTransfer("0x456...", 25);
# Authors
Kumar Abhishek ANand
Email: 21BCS4291@cuchd.in
License
This code is released under the MIT License. Feel free to use, modify, and distribute it as per the terms of the license.
