# tBTC and Tornado Cash

This is a submission of July Play for the Keep from Crypto Investor

Forked from Tornado-Cash

## Contract Addresses:

1. 0.001 tBTC slot mixer: `0xAb4c4bc8749136474E5705d81Ba5936B5274AC33`
1. 0.01 tBTC slot mixer: `0xEb7392dEcde73cd75C566CBFA6638dca37BA9D38`
1. 0.1 tBTC slot mixer: `0x4484C2ABEbA0D431c59D97207523d7dDe6C3caE4`
1. 1 tBTC slot mixer: `0x1cddf698BCD67A83e65f2C87bB2b48ba0310A3a2`

## Requirements

1. `node v11.15.0`
2. `npm install -g npx`

## Usage

You can see example usage in cli.js, it works in nodejs console.

1. `npm install`
1. `cp .env.example .env`
1. `npm run build` - this may take 10 minutes or more

Use with command line version. Works for Ropsten Network:

### Example:

Try tbtc mixer on Ropsten

```bash
./cli.js deposit tBTC 0.001 --rpc https://ropsten.infura.io/v3/27a9649f826b4e31a83e07ae09a87448

```

```bash
./cli.js withdraw tornado-tbtc-0.001-3-0xbdae9a193bea274079ce3c2cfb2eede0d03ddf5aee8d069833e616a97036af0e2747cdfbde6bf87fafb17375646e9d2528c4576fe539ce1757055f30cbcc --rpc https://ropsten.infura.io/v3/27a9649f826b4e31a83e07ae09a87448
```

You can see example usage in minimo-demo-ropsten-token.js.
