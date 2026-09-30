# GBSBFI Deployment Guide

## 1. Test locally

```bash
npm install
npm test
npm run compile
```

## 2. Remix option

The contract can be opened in Remix as a standalone Solidity file.

Compile with Solidity `0.8.24`.

For the constructor, pass the initial supply in base units.

Example for 1,000,000 tokens with 18 decimals:

`1000000000000000000000000`

Do not use a production amount until tokenomics are finalized.

## 3. Testnet

Configure:

- `SEPOLIA_RPC_URL`
- `DEPLOYER_PRIVATE_KEY`

Never commit `.env`.

Run:

```bash
npm run deploy:sepolia
```

## 4. Verification

After testnet deployment:

1. Save the contract address.
2. Save the deployment transaction hash.
3. Verify the exact source and compiler version on the relevant block explorer.
4. Confirm name, symbol, decimals, total supply and owner.
5. Test transfer, approve, transferFrom, burn, mint and pause behavior.

## 5. Mainnet

Mainnet deployment is a separate approval step. The contract address and deployment parameters must be recorded permanently.
