# SLP SDK

[Simple Ledger Protocol](https://simpleledger.cash) is an emerging standard for issuing secure tokens on the Bitcoin Cash blockchain.

[SLP SDK](https://developer.bitcoin.com/slp) is powered by [BITBOX](https://developer.bitcoin.com/bitbox).

This fork was modified by [KeepBitcoinFree-org](https://github.com/KeepBitcoinFree-org) to allow for one to many SLP transactions (up to 19 addresses/amounts at once).

## Installation and Usage

- Ensure you have node.js v10 or higher installed.

- Clone this repository

```bash
git clone https://github.com/KeepBitcoinFree-org/slp-sdk
cd slp-sdk
```

- Install dependencies: `npm install`

- Explore the [example apps](examples/README.md)

- To send multi-SLP transactions, use typical syntax but include address and amount arrays instead of singular variables within sendConfig:
```
const sendTxId = await SLP.TokenType1.send(sendConfig);
```

### Handy Links

- [SLP API introduction](https://developer.bitcoin.com/slp)
- [SLP API docs](https://developer.bitcoin.com/slp/docs/js/getting-started)
- [SLP specification](https://github.com/simpleledger/slp-specifications/blob/master/slp-token-type-1.md)
- [SLP website](https://simpleledger.cash/)
- [Bitcoin.com SLP explorer](https://simpleledger.info/)
- [Fountainhead SLP explorer](https://simpleledger.info/)
- [SLP specification unit tests](https://github.com/simpleledger/slp-unit-test-data) (Python)
- [KeepBitcoinFree.org] (https://keepbitcoinfree.org)

### Token-Aware Wallets

- [Badger Wallet](https://badger.bitcoin.com/)
- [Electron Cash SLP](https://github.com/simpleledger/Electron-Cash-SLP)
- [Zapit] (https://Zapit.io)
