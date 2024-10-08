# ruksads-token

This repository contains a sample project that you can use as the starting point
for your Ethereum project. It's also a great fit for learning the basics of
smart contract development.

```sh
npm install
```

Once installed, let's run Hardhat's testing network:

```sh
npx hardhat node
```

Then, on a new terminal, go to the repository's root folder and run this to
deploy your contract:

```sh
npx hardhat run scripts/deploy.js --network localhost
```

Finally, we can run the frontend with:

```sh
cd dapp
npm install
npm start
```

Open [http://localhost:3000/](http://localhost:3000/) to see your Dapp. You will
need to have Coinbase Wallet or Metamask  installed and listening to
`localhost 8545`.


# Dapp

```sh
 This Daap is in charge of doing these things:
   1. It connects to the user's wallet
   2. Initializes ethers and the Token contract
   3. Polls the user balance to keep it updated.
   4. Transfers tokens by sending transactions
   5. Renders the whole application

 ``` 

 for testing purpose you can add a few tokens using below command

 ```sh
    npx hardhat --network localhost faucet <address of your wallet>
 ```