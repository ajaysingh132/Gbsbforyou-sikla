# GBSBFI Security Checklist

## Contract controls

- [x] No hidden transfer fee
- [x] No blacklist
- [x] No external token dependency
- [x] Explicit owner-only mint
- [x] Holder burn
- [x] Emergency pause
- [x] Ownership transfer
- [x] Ownership renunciation

## Before mainnet

- [ ] Independent Solidity review
- [ ] Unit tests pass
- [ ] Testnet deployment
- [ ] Explorer source verification
- [ ] Constructor parameters reviewed
- [ ] Tokenomics published
- [ ] Owner/multisig policy decided
- [ ] Legal/regulatory review where applicable
- [ ] Frontend tested against the exact deployed address

Do not publish a mainnet address until these checks are complete.
