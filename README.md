# Swisstronik code challenge #3

## Task details: Craft an ERC20 contract that mints at least 100 tokens with Hardhat (in 7 Steps)

1. Install Hardhat
```
npm install --save-dev hardhat
```

2. Create a Hardhat Project
```
npx hardhat
```

3. Press enter on Create a JavaScript project
```
888    888                      888 888               888
888    888                      888 888               888
888    888                      888 888               888
8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
888    888 .d888888 888    888  888 888  888 .d888888 888
888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

Welcome to Hardhat v2.17.1

? What do you want to do? …
▸ Create a JavaScript project
  Create a TypeScript project
  Create an empty hardhat.config.js
  Quit
```

4. Make sure you install the hardhat toolbox by running
```
npm install --save-dev @nomicfoundation/hardhat-toolbox
```

5. Compile Token
```
npx hardhat compile
```

6. Function Deploy
```
npx hardhat run scripts/deploy.js --network swisstronik
```

7. Function Mint
```
npx hardhat run scripts/mint.js --network swisstronik
```

xxx My Result xxx
```
Name : LOGOS
Symbol : LGS
```
```
Token Contract :
0xB0DFcbA004C21f30c7CfB7B35e56455440732ecB
Tx Hash Mint :
https://explorer-evm.testnet.swisstronik.com/tx/0xf8d4298e102cf08176b2fd98494d081f3321ac42a1113b79a9e51d878131dbda
```


This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
Credited by Logosdibta
