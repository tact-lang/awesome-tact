<!-- omit from toc -->

# Awesome Tact [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Twitter](https://img.shields.io/twitter/follow/tact_language?style=social)](https://twitter.com/tact_language)
[![Telegram](https://img.shields.io/badge/telegram-Tact%20Community%20Chat-blue?logo=telegram)](https://t.me/tactlang)
[![Telegram](https://img.shields.io/badge/Telegram-🥣%20Tact%20Kitchen%20Channel-white?logo=telegram)](https://t.me/tact_kitchen)


A curated list of resources designed to help you learn and program in Tact.

---

<!-- omit from toc -->

## 📖 Table of Contents

- [📚 Official Resources](#-official-resources)
- [🛠️ Tact in Production](#%EF%B8%8F-tact-in-production)
- [🎓 Education](#-education)
- [🎯 Get Coding in Tact](#-get-coding-in-tact)
  - [Developer Tools](#developer-tools)
  - [Templates](#templates)
  - [Libraries](#libraries)
- [📜 Smart Contracts Examples](#-smart-contracts-examples)

---

## 📚 Official Resources

- [Tact Documentation](https://tact-lang.org/)
- [Tact on GitHub](https://github.com/tact-lang/tact)
- [Tact Community on Telegram](https://t.me/tactlang)
- [TON Dev News Telegram channel](https://t.me/tondev_news)
- [Tact Kitchen Telegram channel](https://t.me/tact_kitchen)
- [Learn with Tact by Example](https://tact-by-example.org/)
- [Get Started with Tact Project Template](https://github.com/tact-lang/tact-template)

## 🛠️ Tact in Production

- [GasPump.tg](https://gaspump.tg) uses Tact (no source code available)
- [Tradoor](https://tradoor.io) uses Tact (no source code available, but there is a [security audit report](https://www.tonbit.xyz/reports/Tradoor-Smart-Contract-Audit-Report-Summary.pdf) by TonBit
- [PixelSwap DEX](https://www.pixelswap.io) uses Tact (no source code available, but there is a [security audit report](https://github.com/trailofbits/publications/blob/master/reviews/2024-12-pixelswap-dex-securityreview.pdf) by Trail of Bits
- [Proof of Capital](https://github.com/proof-of-capital/TON): [Proof of Capital](https://proofofcapital.org/) is a market-making smart contract that protects interests of all holders

## 🎓 Education

### Basics

- [Introduction to Blockchain](https://blog.ton.org/what-is-blockchain)
- [The Open Network](https://docs.ton.org/learn/introduction)

### YouTube Educational Videos

- [Tact & Blueprint [EN]](https://www.youtube.com/@AlefmanVladimirEN-xb4pq/videos) by [@alefman](https://t.me/alefman)
- [Tact & Blueprint [RU]](https://www.youtube.com/watch?v=isYBvzM-MfQ&list=PLOIvUFGfwP93tZI_WnaLyJsZlskU4ao92) by [@alefman](https://t.me/alefman)
- [Tact development [RU]](https://www.youtube.com/watch?v=S6wlNsKUHpE&list=PLyDBPwv9EPsAJpR7R0cC4kgo7BjiMmUy7&index=1) by [@nonam3e](https://t.me/nonam3e)
- [TON 开发从入门到应用 [CN]](https://openbuild.xyz/learn/challenges/2023609337/2939) by Jason
- [Tact & TON Basic 手把手學習 [CN]](https://www.youtube.com/@ton101_zh) by [@howard_peng](https://t.me/ton101_zh)

## 🎯 Get Coding in Tact

### Developer Tools

Editors and IDEs:
- Tact extension for Visual Studio Code by [TON Studio](https://tonstudio.io): get it from [VS Marketplace](https://marketplace.visualstudio.com/items?itemName=tonstudio.vscode-tact), [Open VSX Registry](https://open-vsx.org/extension/tonstudio/vscode-tact) or install from [VSIX files](https://github.com/tact-lang/tact-language-server/releases)
- [TON Web IDE](https://ide.ton.org) by TON Studio
- [Vim 8+: plugin for Tact](https://github.com/tact-lang/tact.vim) by TON Studio
- [⚡ All-in-one Sublime Text 4 package for Tact](https://packagecontrol.io/packages/Tact) by TON Studio
- [JetBrains IDEs: TON plugin for Tact](https://plugins.jetbrains.com/plugin/23382-ton)

Security:
- [Misti](https://github.com/nowarp/misti) – A static program analyzer for smart contracts on the TON Blockchain

Grammars:
- [🌳 Tree-sitter grammar for the ⚡ Tact contract programming language](https://github.com/tact-lang/tree-sitter-tact) developed by TON Studio
- [highlight.js-based grammar for Tact](https://github.com/bakkenbaeck/highlightjs-tact): provides syntax highlighting for Tact
- [Prism.js grammar for Tact](https://github.com/tact-lang/prism-ton/blob/main/langs/prism-tact.js): provides syntax highlighting for Tact

### Templates

- [Tact Template](https://github.com/tact-lang/tact-template): A ready-to-use template with the dev environment set up, it includes Tact compiler with TypeScript + Jest, a local TON emulator and AI-based editors support. Includes examples of how to perform tests

### Libraries

- [Blueprint](https://github.com/ton-community/blueprint): A development environment for TON Blockchain to write, test, and deploy smart contracts.
- [Tact Emulator](https://github.com/tact-lang/tact-emulator): An emulation toolkit for TON Smart Contracts.
- [TON Contract DNS](https://github.com/tact-lang/ton-contract-dns): A small library for resolving TON DNS names.
- [TON Jest](https://github.com/tact-lang/ton-jest): Testing tools for TON and Jest.
- [Tact Deployer](https://github.com/tact-lang/tact-deployer): A library to prepare the deployment of a Tact package.
- [Foton](https://foton.sh): A TypeScript toolkit for interacting with TON wallets and blockchain as a whole.
- [Tonion](https://github.com/ton-ion/tonion-contracts): A collection of reusable smart contract Traits and toolkit for the Tact language on the TON blockchain.

## 📜 Smart Contracts Examples

- [Tact Wallet Contract](https://github.com/tact-lang/contract-wallet): This wallet contract supports gasless transactions, allows operations on behalf of the wallet by other contracts, and can execute a scalable number of operations in a single transaction.
- [Tact Payouts Contract](https://github.com/tact-lang/contract-payouts): A perfect solution for on-chain payouts. This contract generates a list of text tickets for each address entitled to a payout. Tickets are signed transactions serialized as comments to be parsed by the smart contract.
- [TON VOTE Contracts](https://github.com/orbs-network/ton-vote-contracts/tree/main): TON Blockchain smart contracts for [ton.vote](https://ton.vote/)
- [Simple DNS Contract](https://github.com/tact-lang/contract-dns-simple): A contract that allows you to manage DNS records in a simple way. It also allows to burn fuses disallowing certain modifications of records.
- [NFT Standard Example](https://github.com/howardpen9/nft-template-in-tact): A basic implementation of NFT standard that include the [TEP-62](https://github.com/ton-blockchain/TEPs/blob/master/text/0062-nft-standard.md) and [TEP-66](https://github.com/ton-blockchain/TEPs/blob/master/text/0066-nft-royalty-standard.md) in practice. Contributed by community contributor [@howard_peng9](https://dune.com/Howard_Peng)
- [Jetton Standard Example](https://github.com/howardpen9/jetton-implementation-in-tact): Followed the [TEP-74](https://github.com/ton-blockchain/TEPs/blob/master/text/0074-jettons-standard.md), contributed by [@howard_peng9](https://github.com/howardpen9).
- [TonDynasty](https://github.com/Ton-Dynasty/tondynasty-contracts): The Ton Dynasty Contracts is a library built by the Perman Lab Team for efficient smart contract development using Tact. It provides a number of templates, including contract traits, for Ton developers to utilize.
  Perman Lab will always stand by you. Ask for our help in [Perman Lab Community](https://t.me/permanlab).
- [Fireworks](https://github.com/ton-community/tact-fireworks): An educational contract for learning basic tools in tact and writing tests for special cases.
- [Ready-to-use templates for Jetton & NFT](https://github.com/Laisky/tact-utils): Provides ready-to-use templates for Jetton, NFT, Traits, as well as some commonly used tools.

- [More Examples](https://github.com/tact-lang/tact/tree/main/examples): Check out 10+ examples in the official Tact repository.

## License

MIT
