# JIMP Token
> Solana SPL Token for ProphecyJimpsons Ecosystem

- **Max Supply**: 1B JIMP
- **Decimals**: 9
- **Program ID**: `FLLkxbfaKxAycFjk*********nXdfejkqz2Jun1Dmh`

## Features
- Fixed maximum supply enforcement
- Controlled token initialization
- Associated Token Account (ATA) support
- Authority-based minting controls

## Build & Deploy
yarn install
anchor build
anchor deploy --provider.cluster mainnet
text

## Test
anchor test
anchor verify -p jimp_token --provider.cluster mainnet
text

## Contract Functions
// Initialize token
initialize(ctx: Context<Initialize>)
// Mint new tokens
mint_token(ctx: Context<MintToken>, amount: u64)
text

## Security
- Supply cap enforcement
- Overflow protection
- Authority validation
- Secure ATA initialization

## Integration
- Anchor Framework
- SPL Token Program
- Associated Token Program

> Mainnet deployment pending pump.fun release. Contact team for integration details.

© 2025 ProphecyJimpsons | All Rights Reserved
