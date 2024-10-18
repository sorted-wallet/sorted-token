# Sorted Token (SORT)

## Overview
**Sorted Token** (SORT) is an ERC-20 token built on the Skale Europa DeFi blockchain, using OpenZeppelin's smart contract library.

## Project Features
- **ERC-20 Token**: A fungible token following the ERC-20 standard.
- **Burnable**: Token holders can burn (destroy) their tokens.
- **Mintable**: The owner can mint new tokens as needed.
- **Permit**: Implements ERC20Permit, allowing token approvals via signatures.

## Technologies Used
- **Solidity**: Smart contract programming language.
- **Hardhat**: Ethereum development environment.
- **OpenZeppelin**: Secure smart contract library.
- **Ethers.js**: Library for interacting with the Ethereum blockchain.
- **TypeScript**: Used for scripting and deployments.

## Prerequisites
- **Node.js**: Ensure Node.js is installed. You can download it from [here](https://nodejs.org/).
- **Hardhat**: Used for smart contract development and deployment.
- **Git**: Version control system to clone and manage the project.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sorted-token.git
   ```

2. Change to the project directory:
   ```bash
   cd sorted-token
   ```

3. Install the project dependencies:
   ```bash
   npm install
   ```

## Configuration

By default this will deploy to test net. Please modify to deploy to main net.

1. Add the private key of the deployer contract in .env:
 ```bash
   PRIVATE_KEY=your-private-key
   ```

2. Ensure you have enough SFUEL in your Skale wallet. You can get it [here] (https://www.sfuelstation.com/).

## Compile the contract

To compile the contract, use Hardhat's built-in compiler:
   ```bash
   npx hardhat compile
   ```

## Deploy the contract
To deploy the contract to the Skale testnet, run the following command:
   ```bash
   npx hardhat run scripts/deploy.ts --network skale
   ```












