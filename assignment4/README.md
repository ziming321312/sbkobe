# Assignment / Lab 4 - Ziming Wang

GEC Academy: Introduction to Ethereum and Cloud Blockchain Solutions Engineering.

[Download the complete source, tests, and execution evidence](Assignment_4_Source.zip).
Extract the archive, then open its `assignment4` folder.

## Contents

- Corrected Solidity voting contract with SafeMath and local exploit tests.
- ERC-20 XYZCoin contract, migrations, and Truffle tests.
- Web3.js scanner using the student's Infura account; first creation transaction found in block 46402.
- Pinned dependencies, Etherscan data, and execution logs.

## Run

```sh
npm ci
npm run compile
npm test
npm run test:scanner
# Set INFURA_API_KEY locally, then:
USE_FEE_HISTORY=1 npm run scan
```

Validation: 18 contract tests and 8 scanner tests passed. The actual Infura scan covered blocks 0 through 46402 and inspected 79 transactions.

The source archive contains no Infura API key, private key, wallet mnemonic, or node_modules directory.
AI assistance was used for explanations, implementation, debugging, testing, and document preparation. The report and personal signature are handled separately through the course submission channel.
