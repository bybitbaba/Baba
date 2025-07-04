# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.js
```
git add <file-name>

git commit -m "Commit message (e.g., Added line to README)"

git pull origin main


for i in {1..10}; do
  echo "Change $i" >> changes.txt
  git add changes.txt
  git commit -m "Added change $i"
done
git push origin main

git pull origin main
