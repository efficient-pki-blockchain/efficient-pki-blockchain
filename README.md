# An Efficient, Secure and Privacy Preserving Blockchain-Based PKI Architecture

## Getting Started
This repository contains smart contracts and proof generation/verification codes for implementation of "An Efficient, Secure and Privacy Preserving Blockchain-Based PKI Architecture" paper. The general architecture is depicted in the Picture below.

![Alt text](/images/efficient-pki-architecture.png?raw=true "Efficient PKI Architecture")


### Prerequisites
In order to deploy the smartcontracts a private Ethereum network is required.
Use https://github.com/snt-sedan/pki-blockchain for setting up infrastructure to deploy smart contracts in to Ethererum network. 

### Repository Organization

* **smart-contracts** - comprises the  smartcontracts to manage Block Chain Based PKI Architecture.

* **proof-generation-verification** - comprises the nodejs codes to generate state Merkle proof for TLS certificates and verify it. We use [zmitton/eth-proof](https://github.com/zmitton/eth-proof) as the underlying library.
