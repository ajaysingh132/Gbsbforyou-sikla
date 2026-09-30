# GBSBFI V2

GBSBFI is a GBSBFORYOU token project being redeveloped as an independent, transparent ERC-20 project.

## Repository strategy

This package is designed to be committed to the existing repository:

`ajaysingh132/Gbsbforyou-sikla`

Recommended branch:

`gbsbfi-redevelopment`

Do **not** overwrite `main` until the contract, tests, documentation and deployment have been reviewed.

## Current V2 scope

- ERC-20 compatible token
- Name: GBSBFI
- Symbol: GBSBFI
- Configurable initial supply at deployment
- Owner-controlled minting
- Token burning by holders
- Ownership transfer
- Pause/unpause emergency control
- No hidden tax
- No blacklist
- No transfer fee
- No automatic liquidity mechanism
- No external wallet custody
- Source-first documentation

> The initial supply is deliberately a deployment parameter. Final tokenomics must be approved before mainnet deployment.

## Directory

```text
contracts/
  GBSBFI.sol

test/
  GBSBFI.test.js

scripts/
  deploy.js

frontend/
  index.html

docs/
  TOKENOMICS.md
  DEPLOYMENT.md
  SECURITY.md

hardhat.config.js
package.json
```

## Development

```bash
npm install
npx hardhat test
```

For deployment, create a `.env` file from `.env.example`, configure the selected network and deploy only after reviewing the tokenomics and security documents.

## Important

This repository is a software project, not a promise of token value, profit, liquidity, exchange listing or investment return. Do not describe GBSBFI as an investment product unless separately supported by applicable legal and regulatory review.
