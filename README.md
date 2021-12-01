# RockstarsNFT

RockstarsNFT is a collection of 10,000 uniquely generated NFTs rockin' out on the Ethereum blockchain. The frontend can be viewed at https://rockstars.buzz.

### Getting started locally

Run `npm install`

- Navigate to localhost:3000 (or wherever your server is running)
- Click "connect wallet"
- Make sure you're on the rinkeby network
- Select how many NFTs to mint, and click the mint button
- After minting, links will take you directly to your created resources

### Running tests

- Be sure to have `ganache-cli` installed and running
- From the project's root directory, type `truffle test` in your terminal

### Deploying the contract

Create a .env file in the root directory and populate it with your wallet's mnemonic, as well as any eth provider endpoints

```
MNEMONIC_DEV=your mnemonic goes here
INFURA_URL_ROPSTEN=https://ropsten.infura.io/v3/<your id here>
```

### Folder Structure

`/`

Contains the package manager, README.md, and truffle-config.js

`/contracts`

Contains the NFT smart contract and migration smart contract

`/migrations`

Contains the initial and deployment migration

`/public`

Contains artifacts compiled when `npm run build` is called

`/src`

Contains the frontend code

`/src/Components`

React components

`/src/contracts`

Contains the compiled contracts

`/src/images`

Images for the app to use

`/test`

Test files

### My ethereum address

0xe5Bd46FAD7572bAdc19F23723Ba2B82ac2AE0612

### Walkthough video

https://youtu.be/EbdCBGo9-8U
