
![Logo](images/bitcoin_logo.png) 


## Awesome Bitcoin with Rust
A collection of awesome open source Rust Bitcoin projects, libraries and packages.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

### Projects
- [Bitcoin Dev Kit (BDK)](https://bitcoindevkit.org/) - With BDK, you can seamlessly build cross platform mobile wallets.
  
- [Lightning Dev Kit (LDK)](https://lightningdevkit.org/) - The simplest way to integrate Lightning into your Bitcoin wallet.
  
- [Nakamoto](https://github.com/cloudhead/nakamoto) - Privacy-preserving Bitcoin light-client implementation in Rust.
  
- [Revault](https://revault.dev/) - A superior custody solution for institutions holding Bitcoin.
  
- [Fedimint](https://fedimint.org/) - A modular open source protocol to custody and transact bitcoin in a community context, built on a strong foundation of privacy.
  
- [LNP/BP](https://www.lnp-bp.org/) - Non-profit supervising layer 2 & 3 protocols on Bitcoin & Lightning Network.
  
- [Braiins OS](https://braiins.com/bitcoin-mining-stack-upgrade) - Our mission is to give you complete control of your Bitcoin mining operation.
  
- [Galoy Money](https://galoy.io/) - Bitcoin-native banking infrastructure for organizations

- [Bitcredit Protocol](https://www.bit.cr/) - Bitcredit Protocol is a community-driven open software project to unblock the adoption of Bitcoin. It provides a fiat-less on-ramp and finances the real economy's working capital and wage fund needs through the decentralised issuance of peer-to-peer Bitcoin credit money.

### Libraries & Frameworks
- [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) - Rust Bitcoin library.
  
- [Miniscript](https://github.com/rust-bitcoin/rust-miniscript/) - Library for handling Miniscript, which is a subset of Bitcoin Script designed to support simple and general tooling.

- [rust-bitcoin-rpc](https://github.com/rust-bitcoin/rust-bitcoincore-rpc) - This is a Rust RPC client library for calling the Bitcoin Core JSON-RPC API.
  
- [Rust Secp256k1](https://github.com/rust-bitcoin/rust-secp256k1) - rust-secp256k1 is a wrapper around libsecp256k1, a C library implementing various cryptographic functions using the SECG curve secp256k1.
  
- [Rust Lightning](https://github.com/lightningdevkit/rust-lightning) - A highly modular Bitcoin Lightning library written in Rust.
  
- [LDK Sample](https://github.com/lightningdevkit/ldk-sample) - Sample node implementation using LDK.
  
- [electrs](https://github.com/romanz/electrs) - An efficient Electrum Server in Rust

- [Blocksteam electrs fork](https://github.com/Blockstream/electrs) - A block chain index engine and HTTP API written in Rust based on romanz/electrs.
  
- [Blocks Iterator](https://github.com/RCasatta/blocks_iterator) - Iterate over Bitcoin blocks.
  
- [Rusty Paper Wallet](https://github.com/RCasatta/rusty-paper-wallet) - Generates Bitcoin paper wallet offline in a single html page.
  
- [Rust DLC](https://github.com/p2pderivatives/rust-dlc) - Rust library for working with Discreet Log Contracts.
  
- [Rust Nostr](https://github.com/rajarshimaitra/rust-nostr) - The Stage 2 building block to reach the dream of DSNs with Bitcoin DeFi.
  
- [BIP 39 Solver](https://github.com/johncantrell97/bip39-solver-cpu) - Brute force BIP-39 Mnemonic using CPU.
  
- [Validating Lightning Signer](https://gitlab.com/lightning-signer/docs/) Improving Lightning security with fully validated remote signing.
  
- [The Eye of Satoshi](https://github.com/talaia-labs/rust-teos) - Lightning Watchtower

- [Bria](https://github.com/GaloyMoney/bria) - The bridge from your applications to the Bitcoin network.

- [Fedimint](https://github.com/fedimint/fedimint) - `Fedimint` is a module based system for building federated applications. It is designed to be a trust-minimized, censorship-resistant, and private alternative to centralized applications.

- [Bitcredit E-Bills](https://github.com/BitcoinCredit/E-Bills) - Bitcoin Credit Money Supply for the Real Economy

- [Internet Computer Bitcoin Canister](https://github.com/dfinity/bitcoin-canister)
  
- [Bitcoin SPV](https://github.com/summa-tx/bitcoin-spv) A low-level toolkit for working with Bitcoin from other blockchain (latest update 2021-06-26).

### Wallets
- [Mutiny](https://www.mutinywallet.com/) - Mutiny is a self-custodial lightning wallet that runs in the browser. [Github code](https://github.com/MutinyWallet/)
  
### Smart Contracts & VMs
- [RGB](https://github.com/RGB-WG) - `RGB` is a system of private & scalable client-validated smart contracts on Bitcoin & Lightning developed by LNP/BP Standards Association.
  
- [BitMask](https://github.com/diba-io/bitmask-core) - `BitMask` is a Bitcoin-only web wallet and browser extension for accessing decentralized web applications on the Bitcoin timechain. It is designed to support UTXO-based smart contracting protocols such as RGB, in addition to Lightning payments.
  
- [bitcoin-scriptexec](https://github.com/BitVM/rust-bitcoin-scriptexec) - This project is a work-in-progress mostly attempting to facilitate `BitVM` development. It does not yet fully implement all opcodes, but as a library already gives you pretty good insight into the internals of the execution in a step-wise manner.
  
- [Toy BitVM ](https://github.com/chainwayxyz/toy-bitvm-rs) - Toy `BitVM` in Rust, Experimental toy BitVM implementation in Rust.
  
- [Sapio](https://github.com/sapio-lang/sapio) - A framework for creating composable multi-transaction Bitcoin Smart Contracts.

- [Minsc](https://min.sc) - A Miniscript-based scripting language for Bitcoin contracts, Source code [on Github](https://github.com/shesek/minsc) 

### Indexers

- [OPI - Open Protocol Indexer](https://github.com/bestinslot-xyz/OPI) - `Open Protocol Indexer(OPI)`, is the best-in-slot open-source indexing client for meta-protocols on Bitcoin, fork of `ord` `0.14.0`
  
- [Ord](https://github.com/ordinals/ord) - `ord` is an index, block explorer, and command-line wallet. 
  
### Tutorials & Walkthroughs
- [Bitcoin From Scratch Part1](https://monokh.com/posts/bitcoin-from-scratch-part-1), [Part2: Node](https://monokh.com/posts/bitcoin-from-scratch-part-2), [Part3: Network](https://monokh.com/posts/bitcoin-from-scratch-part-3) - Bitcoin from scratch with Rust  at 2021
  
- [Programming Bitcoin Rust](https://www.youtube.com/playlist?list=PLa5eH26KEhkf87-l9WizXX_N17uICIQ21) - Rust implement for Programming Bitcoin book video by Gary Krause latest update 2024-01-10

### Related Resources
- [BIPs](https://github.com/bitcoin/bips) - Bitcoin Improvement Proposals
  
- [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page) - This wiki is a public resource for the community of Bitcoin users, developers, and businesses as well as anyone interested in Bitcoin.
  
- [Bitcoin development philosophy](https://bitcoindevphilosophy.com/) - Bitcoin Development Philosophy is a guide for Bitcoin developers who already understand the basics of concepts and processes such as Proof-of-Work, block building, and the transaction life cycle, and who want to level up by gaining a deeper understanding of Bitcoin’s design trade-offs and philosophy.

- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook) - `Mastering Bitcoin` is a technical book that explains what Bitcoin is and how it works.

- [Programming Bitcoin](https://github.com/jimmysong/programmingbitcoin) - by Jimmy Song
  
- [Learning Bitcoin from the Command Line](https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line) - Learning Bitcoin from the Command Line is a tutorial for working with Bitcoin (and Lightning) that teaches direct interaction with the servers themselves, as the most robust and secure way to begin cryptocurrency work
  
- [Bitcoin Design](https://bitcoin.design/) - Design Bitcoin for everyone, Open-source design for Bitcoin products.
  
### Contribute
Contributions welcome! Read the [contribution guidelines](contributing.md) first. PRs always welcome!

### License - MIT License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the author has waived all copyright and related or neighboring rights to this work.