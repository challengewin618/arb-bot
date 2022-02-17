# Arbitrage Bot
Trading bot that utilizes Solidity contracts, in conjunction with decentralized exchanges, to execute token arbitrage opportunities on any EVM compatible blockchain. 

## Technologies
Javascript/Node.js, Solidity, Hardhat, Ethers.js, Waffle. 

## Setup
1. Following https://hardhat.org/tutorial/, install Node.js if needed
2. ```npm install --save-dev hardhat```
3. ```npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai```
4. ```npx hardhat compile``` - if any contract dependancies are needed, npm install them. 
 
 TODOs:
 - First step, follow this tutorial to start a new proj in hardhat https://hardhat.org/tutorial/, using ethers.js etc. Then can port over exisitng bot code and change where neccessary.  
 - Finish initial configuration, port over web3.js references to ethers.js, setup hardhat, etc. See existing readme in downloads
 - Research new stategies, create modular scripts for each blockchain, implement bot for DEXs on AVAX/FTM/MATIC, etc. 
 - Neat React front-end
 - Find inspiration for data pipelines
 - Write up TDD here and setup instructions, maybe draw out FSM
 - Is it worth doing this proj in Rust?  
 - Ideally make this super portable for new DEXs
