# hello-world-rads

## Setup

Steps:
- run `npm install` to set up all the dependencies (hardhat)
- rename `.env-example` to `.env` and then fill in the environment variables with your own info
- set up an Alchemy account
- set up a metamask wallet with fake testnet ether
- run `npx hardhat run scripts/deploy.js` to deploy the contract to the sepolia testnet
- run `npx hardhat run scripts/interact.js` to read and write a new message to the smart contract on sepolia
- run `npx hardhat verify --network sepolia <your deployment address> 'Hello World!'` to verify your contract on Etherscan