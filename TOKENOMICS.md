# GBSBFI Tokenomics — Draft

This document intentionally does not lock a final supply or distribution model.

## Parameters to decide before mainnet

1. Maximum/initial supply
2. Decimals
3. Founder/treasury allocation
4. Community allocation
5. Ecosystem/rewards allocation
6. Liquidity allocation
7. Vesting and lock periods
8. Whether owner minting should remain enabled
9. Whether a permanent supply cap is required
10. Governance and treasury control

## Current contract behavior

- Initial supply is created at deployment and assigned to the deployer.
- Owner can mint additional tokens.
- Any holder can burn their own tokens.
- Approved spenders can burn from an account within allowance.
- Owner can pause transfers.
- There is no transfer tax or hidden fee.

**Mainnet rule:** Do not deploy until these parameters are explicitly approved and documented.
