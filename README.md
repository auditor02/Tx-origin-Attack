# Tx origin  Project

Tx.origin refers to the original account that started a transaction. msg.sender refers to the account that called the function. For security reasons, it's better to use msg.sender.
This project demonstrates an attack which shows why you shouldn't use tx.origin. it contains a basic Hardhat use case, a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
# Tx-origin-Attack
