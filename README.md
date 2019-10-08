# KORGAN: An Efficient PKI Architecture Based on Permissioned-Blockchain by Modifying PBFT Through Dynamic Threshold Signatures

## Getting Started
This repository contains smart contracts and proof generation/verification codes for implementation of 
"KORGAN: An Efficient PKI Architecture Based on Permissioned-Blockchain by Modifying PBFT Through Dynamic Threshold Signatures" paper. The general architecture is depicted in the Picture below.

<p align="center">
  <img src="/images/tls-system-of-korgan.png?raw=true" title="TLS System of KORGAN">
  <div align="center">TLS System of KORGAN</div>
</p>
                         
Please find the article in https://eprint.iacr.org/2019/1141

### Prerequisites
In order to deploy the smartcontracts a private Ethereum network is required.
Use https://github.com/snt-sedan/pki-blockchain for setting up infrastructure to deploy smart contracts in to Ethererum network. 

### Repository Organization

* **smart-contracts** - comprises the  smartcontracts to manage Block Chain Based PKI Architecture.

* **proof-generation-verification** - comprises the nodejs codes to generate state Merkle proof for TLS certificates and verify it. We use [zmitton/eth-proof](https://github.com/zmitton/eth-proof) as the underlying library.
