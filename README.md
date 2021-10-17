# Actions

To start the project, you need to 

1) provide a `.env` file, look the `.env.example` to know what you need
2) build the contract with `npm run deploy`
3) Get the contract id from the console and update the variable `CONTRACT_ADDRESS` at the begining of the file `react-client/src/App.js` 
4) Update the json contract with `npm run updateJsonContract`
5) Go on the front folder `cd react-client/`
6) Update dependencies if needed `npm i`
7) Start the front `npm run start`

# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

# Thanks 

Thanks to [buildspace.so](buildspace.so) to learn the basics about minting nfts
