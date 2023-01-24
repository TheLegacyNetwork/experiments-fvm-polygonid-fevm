## ZKP Verifier on FEVM

### Overview

Repository contains implementation for onchain zero-knowledge proof verification.

We aim to provide solidity implementations of:

- Atomic query MTP validator
- Atomic query Signature validator
- ZKP Verifier standard

Also, it contains the example of ERC20 based smart contract with enabled zkp verifications for token transfers.

### Contracts

#### Hyperspace
StateV1: [0x3E5A1dec88f22b0beb8BdDf5a6460360C2DcAd1B](https://fvm.starboard.ventures/contracts/0x3E5A1dec88f22b0beb8BdDf5a6460360C2DcAd1B)
MTPValidator: [0x2c851D061277527503EB444CE43FAc1DF4e2bbc9](https://explorer.glif.io/address/0x2c851D061277527503EB444CE43FAc1DF4e2bbc9/?network=hyperspacenet)

SigValidator: [0x2c851D061277527503EB444CE43FAc1DF4e2bbc9](https://explorer.glif.io/address/0x2c851D061277527503EB444CE43FAc1DF4e2bbc9/?network=hyperspacenet)


Current addresses on Polygon Mumbai testnet.

|                    |                    Sig                   |                    MTP                     |
|:------------------:|:------------------------------------------:|:------------------------------------------:|
|   **Validators**   | 0xb1e86C4c687B85520eF4fd2a0d14e81970a15aFB | 0x217Ca85588293Fb845daBCD6385Ebf9877fAF649 |
| **ERC20 examples** | 0x752A8f2Fd1c5FC5c9241090BD183709D4591D4cb | 0x16b2e8653c7dCFd221114A7e1664D3c884f03090 |
