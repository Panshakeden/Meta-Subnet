# Creating Subnet Project

## Overview
Creating an EVM-Subnet on Avalanche Overview This project establishes an EVM Subnet on the Avalanche network named "Test," featuring its native token, CM. The network seamlessly integrates with MetaMask, enabling the deployment and interaction with smart contracts through the injected provider on Remix.

## Project Features
 CM Token
Minting new tokens: The platform should be able to create new tokens and distribute . Only the owner can mint tokens.

Transferring tokens:Should be able to transfer their tokens to others.

Checking token balance: Should be able to check their token balance at any time.

Burning tokens: Anyone should be able to burn tokens, that they own, that are no longer needed.

The Vault contract

This is a simple contract to enable users get donations from one or more donors. A time lock is set and users can only claim after the lock time is expired.
Getting Started
Follow these steps to get the project up and running on your local machine.

## Prerequisites

Node.js and npm installed on your machine.
Clone the repository using the command - git clone https://github.com/username/projectname.git
Change directory into your project file - cd projectname
Install all dependencies with - npm install
Compile the contract using Hardhat - npx hardhat compile
Run deployment script- npx hardhat run scripts/deploy.js
Interact with the deployed contract through transactions like transfers, minting, and burning.

## Author
Panshak Samson
