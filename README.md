# solana-anchor-mint-transfer-token

## [BE] Token-Contract
### Preparation
set this, related issues: 
- https://solana.stackexchange.com/questions/13076/anchor-idl-different-incorrect-from-solana-playground-idl-generated
- https://solana.stackexchange.com/questions/13362/type-solananftanchor-is-missing-the-following-properties-from-type-idl-addr
```
[toolchain]
anchor_version = "0.29.0" 
```
### Build Contract
preparation for build contract:
```
cargo add anchor_spl
```

### Test
preparation for run test:
```
yarn add @project-serum/anchor
yarn add @solana/spl-token
```

### Run Test 
```
anchor test --skip-local-validator
```

## [FE] Front-end
<TBD>