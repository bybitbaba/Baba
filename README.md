# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract. This is a great starting point for Ethereum development.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js

git add README.md
git commit -m "Added project description to README"

node_modules/
.env
artifacts/
cache/
coverage/

git add contracts/Lock.sol
git commit -m "Added comment to Lock.sol contract"


git add test/Lock.test.js
git commit -m "Added initial test file for Lock contract"
