# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
GAS_REPORT=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## ✈️ A note on contract redeploys
Let's say you want to change your contract. You'd need to do 3 things:

1. We need to deploy it again.
2. We need to update the contract address on our frontend.
3. We need to update the abi file on our frontend.