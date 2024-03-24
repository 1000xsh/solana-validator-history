# solana-validator-history
fetches the transaction history for a solana vote account and saves it to a local json file. it queries the solana blockchain in batches and respects the rate limit.

# config
change VOTE_ACCOUNT_ADDRESS

# requirements
- node
- npm, yarn or pnpm
- solana vote account public key

# install
npm install

# run
npx ts-node index.ts

# json output
```json
  {
    "blockTime": 1711007833,
    "confirmationStatus": "confirmed",
    "err": null,
    "memo": null,
    "signature": "2WdyahigjqwQ9f8e5QDnQuS2v8o722Vo1k7HCWVtLMw342vGHrCWNY8zkG7PfiHKfd14xt3NRdahNfRc6Nc51sEt",
    "slot": 255506148
  },
```
