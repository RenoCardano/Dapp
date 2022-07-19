# Welcome to my Dapp Voting project

    This website allows to register voters, to manage workflow status, to make submit proposals. Subsequently, registered voters can vote for any proposal once. The votes ccan be tallied and the result is shown immediately in a efficient way powered by the blockchain.

# Contract address on Ropsten Test Network
    0x7A1823D4021eb07A27e8d045f71a666066a5fa13

# Short video presentation of the Dapp
 https://www.loom.com/share/97a5870ca59040d788c2f7df4803911e

#Website link:

This Dapp is accessible for testing purpose at this address: https://renocardano.github.io/Dapp/

# Image
    This decentralized application runs Ropsten network, the smart contract is called voting.sol
   ![image](https://user-images.githubusercontent.com/68705151/179346146-c89f9220-342c-44ea-95b5-f2180ed6f17a.png)

# Ropsten deployment

    To deploy run : truffle deploy --network ropsten (with .env containning MNEM & INFURA_IF)

    Starting migrations...
    ======================
    > Network name:    'ropsten'
    > Network id:      3
    > Block gas limit: 30000000 (0x1c9c380)

    1_deploy_simple_voting.js
    =========================

       Deploying 'Voting'
       ------------------
       > transaction hash:    0x750cd9232314ee7b694e2e1892abf7ca1dbea21e1f6d17d58b15489538bc4e5c
       > Blocks: 1            Seconds: 20
       > contract address:    0x7A1823D4021eb07A27e8d045f71a666066a5fa13
       > block number:        12623232
       > block timestamp:     1658220540
       > account:             0x4DD0F9FfbdB344050f33F2F13fa734D0c06Bf898
       > balance:             8.990169339972474152
       > gas used:            1966132 (0x1e0034)
       > gas price:           2.500000007 gwei
       > value sent:          0 ETH
       > total cost:          0.004915330013762924 ETH

       > Saving artifacts
       -------------------------------------
       > Total cost:     0.004915330013762924 ETH

    Summary
    =======
    > Total deployments:   1
    > Final cost:          0.004915330013762924 ETH


## Getting started with dependencies.
To make this project work please intall:
npm install => truffle unbox react

# React Truffle Box

This box comes with everything you need to start using Truffle to write, compile, test, and deploy smart contracts, and interact with them from a React app.

## Installation

First ensure you are in an empty directory.

Run the `unbox` command using 1 of 2 ways.

```sh
# Install Truffle globally and run `truffle unbox`
$ npm install -g truffle
$ truffle unbox react
```

```sh
# Alternatively, run `truffle unbox` via npx
$ npx truffle unbox react
```

Start the react dev server.

```sh
$ cd client
$ npm start
  Starting the development server...
```

From there, follow the instructions on the hosted React app. It will walk you through using Truffle and Ganache to deploy the `SimpleStorage` contract, making calls to it, and sending transactions to change the contract's state.

## FAQ
To install ganache  => npm install -g ganache-cli
- __How do I use this with Ganache (or any other network)?__

  The Truffle project is set to deploy to Ganache by default. If you'd like to change this, it's as easy as modifying the Truffle config file! Check out [our documentation on adding network configurations](https://trufflesuite.com/docs/truffle/reference/configuration/#networks). From there, you can run `truffle migrate` pointed to another network, restart the React dev server, and see the change take place.

- __Where can I find more resources?__

  This Box is a sweet combo of [Truffle](https://trufflesuite.com) and [Create React App](https://create-react-app.dev). Either one would be a great place to start!
   
Set up a proper truffle-config.js
npm install --prefix . @truffle/hdwallet-provider
npm install --prefix . --save dotenv

To deploy with your INFURA_ID and MNEMONIC. Do not push it to Github
To an other terminal => truffle migrate or truffle migrate --network ropsten for a testnest
To deploy run :  npm run deploy to deploy
