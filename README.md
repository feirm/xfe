# XFE

Smart contract for the Feirm (XFE) token residing on the Binance Smart Chain. It has been written using the OpenZeppelin smart contract libary and Truffle for deployment.

## Getting started
```bash
$ yarn install
```

### Development
```bash
$ truffle compile
$ truffle migrate --network bsc
$ truffle run verify Feirm@<CONTRACT_ADDRESS> --network bsc
```