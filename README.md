![nftte](https://github.com/awais922609/Simplest-NFT-DAPP/assets/69464258/72dacd15-9ae5-492c-98db-36b2bc5951e4)

# Ethereum-based NFT Contract Using Hardhat

Welcome to the Ethereum-based NFT Contract built using Hardhat! This repository guides you through creating your very own basic NFT (Non-Fungible Token) contract on the Ethereum blockchain. Whether you're a developer looking to delve into the world of NFTs or simply exploring Ethereum's capabilities, this is the perfect place to start.

## Prerequisites

Before you get started, make sure you have `node` and `npm` installed. If not, you can download them from [here](https://nodejs.org/).

## Getting Started

### 1. Install Required Packages

To set up the environment for the project, run:

```
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox

```

Next, to include the ERC271 module for OpenZeppelin NFT contracts, run:

```

npm install --save-dev @openzeppelin/contracts

```

### 2. Configure Environment Variables

You will need to create and configure a `.env` file in the root directory of the project. Use this command for setting up env file
```

npm install dotenv

```
In this file, add:

```
QUICKNODE_URL=YOUR_QUICKNODE_URL
PRIVATE_KEY=YOUR_METAMASK_PRIVATE_KEY
```

Replace `YOUR_QUICKNODE_URL` with the URL which can be fetched from [QuickNode](https://www.quicknode.com/). And, replace `YOUR_METAMASK_PRIVATE_KEY` with the private key from your MetaMask.

**Note**: Be cautious with your private key. Never share it, commit it, or expose it in any public forum. Always keep it confidential.

### 3. Run the Project

After setting up the environment and configuring the variables, you're all set! To execute the project, simply run:

```

npx hardhat run scripts/deploy.js --network sepolia

```

Copy the contract address it gives you, and look it up on Sepolia Etherscan - open up the first transaction there and it will show you that a NFT was minted and transfered to your address!

## Conclusion

Congratulations! You've now set up and are ready to deploy your very own Ethereum-based NFT contract. Explore the codebase, try deploying your NFT, and have fun experimenting!

---
