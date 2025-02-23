<!-- lint disable awesome-github -->
<!-- lint disable double-link -->
# Awesome Tact [![Awesome badge](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="logo.svg" alt="" align="right" style="margin-left:2em" width="100">][tl]

> A curated list of resources for learning and using [Tact][tl] programming language.

Tact is an open-source statically typed smart contract programming language for TON Blockchain. It runs on the stack-oriented virtual machine (TVM) and is based on the actor model.

[![Website](https://img.shields.io/badge/Website-blue?style=flat)][tl]
[![Documentation](https://img.shields.io/badge/Documentation-blue?style=flat)][td]
[![Twitter](https://img.shields.io/badge/X%2FTwitter-white?logo=x&style=flat&logoColor=gray)][tlx]
[![Telegram](https://img.shields.io/badge/Community_Chat-white?logo=telegram&style=flat)][tlchat]
[![Telegram](https://img.shields.io/badge/Tact_Kitchen_🥣-white?logo=telegram&style=flat)][tk]
<!-- See: https://shields.io/badges/static-badge -->

## Contents

<!-- lint ignore awesome-toc -->
- [Community](#community-)
- [Tact in Production](#tact-in-production-)
- [Plugins and extensions for editors and IDEs](#plugins-and-extensions-for-editors-and-ides-)
- [Tools and utilities](#tools-and-utilities-)
- [Documentation](#documentation-)
- [Articles](#articles-)
- [Videos](#videos-)
- [Smart contracts](#smart-contracts-)

## Community [↑](#contents)

- [`@tactlang` on Telegram][tlchat] - Main community chat.
- [`@tactlang_ru` on Telegram][tlchat_ru] *(Russian)*
- [`@tact_kitchen` on Telegram][tk] - Channel with updates from the team.
- [`@tact_language` on X/Twitter][tlx]
- [`tact-lang` organization on GitHub](https://github.com/tact-lang)

## Tact in Production [↑](#contents)

Software and applications based on contracts written in Tact, deployed in production, and consumed by end users.

###### Open Source or Source Available

- [Proof of Capital](https://github.com/proof-of-capital/TON) - [Proof of Capital](https://proofofcapital.org/) is a market-making smart contract that protects interests of all holders.

###### Closed Source

- [Tradoor](https://tradoor.io) - Fast and social DEX on TON.
  - See the [security audit report](https://www.tonbit.xyz/reports/Tradoor-Smart-Contract-Audit-Report-Summary.pdf) by TonBit.
- [PixelSwap](https://www.pixelswap.io) - First modular and upgradeable DEX on TON.
  - See the [security audit report](https://github.com/trailofbits/publications/blob/master/reviews/2024-12-pixelswap-dex-securityreview.pdf) by Trail of Bits.
- [GasPump](https://gaspump.tg) - TON memecoin launchpad and trading platform.

## Plugins and extensions for editors and IDEs [↑](#contents)

###### Maintained by TON Studio

- [TON Web IDE](https://ide.ton.org) - Try Tact online in an ultimate browser-based IDE designed to simplify the journey of writing, testing, compiling, deploying, and interacting with smart contracts on TON.
- [VS Code extension](https://marketplace.visualstudio.com/items?itemName=tonstudio.vscode-tact) - Powerful and feature-rich extension for Visual Studio Code (VSCode) and VSCode-based editors like VSCodium, Cursor, Windsurf and others.
  - Get it on the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=tonstudio.vscode-tact).
  - Get it on the [Open VSX Registry](https://open-vsx.org/extension/tonstudio/vscode-tact).
  - Or install from the [`.vsix` files in nightly releases](https://github.com/tact-lang/tact-language-server/releases).
- [Language Server (LSP Server)](https://github.com/tact-lang/tact-language-server) - Supports Sublime Text, (Neo)Vim, Helix, and other editors with LSP support.
- [tact.vim](https://github.com/tact-lang/tact.vim) - Vim 8+ plugin.
- [tact-sublime](https://github.com/tact-lang/tact-sublime) - Sublime Text 4 package.
  - Get it on the [Package Control](https://packagecontrol.io/packages/Tact).

###### Other

- [Plugin for JetBrain IDEs like WebStorm, Intellij IDEA and others](https://plugins.jetbrains.com/plugin/23382-ton)

## Tools and utilities [↑](#contents)

### Grammars and highlighting

###### Maintained by TON Studio

- [tree-sitter-tact](https://github.com/tact-lang/tree-sitter-tact) - Tree-sitter grammar and parser, used for syntax highlighting, code navigation, and more.
- [Prism.js grammar](https://github.com/tact-lang/prism-ton/blob/main/langs/prism-tact.js) - Provides syntax highlighting.
- [TextMate grammar](https://github.com/tact-lang/tact-sublime/blob/main/package/Tact.tmLanguage.json) - Provides syntax highlighting in Sublime Text, VSCode, Tact Documentation (through [Shiki](https://www.npmjs.com/package/shiki)), and on GitHub.

###### Other

- [highlight.js grammar](https://github.com/bakkenbaeck/highlightjs-tact) - (outdated) Provides syntax highlighting.

### Templates

- [tact-template](https://github.com/tact-lang/tact-template) - Ready-to-use template with the development environment set up, including the Tact compiler with TypeScript + Jest, a local TON emulator, AI-based editor support, and examples of how to run tests.

### Frameworks and libraries

###### Featured

- [Blueprint](https://github.com/ton-community/blueprint) - Development environment for TON Blockchain to write, test, and deploy smart contracts.
- [TON Jest](https://github.com/tact-lang/ton-jest) - Testing tools for TON with Jest.
- [Foton](https://foton.sh) - TypeScript toolkit for interacting with TON wallets and the blockchain.
- [Tonion](https://github.com/ton-ion/tonion-contracts) - Collection of reusable traits, functions, and TypeScript scripts.

###### Other

- [Tact Emulator](https://github.com/tact-lang/tact-emulator) - Emulation toolkit for TON Smart Contracts.
- [Tact Deployer](https://github.com/tact-lang/tact-deployer) - Library to prepare the deployment of a Tact package.
- [TON Contract DNS](https://github.com/tact-lang/ton-contract-dns) - Small library for resolving TON DNS names.

### Security

- [Misti](https://github.com/nowarp/misti) - Static smart contract analyzer.
- [TON Symbolic Analyzer (TSA)](https://github.com/espritoxyz/tsa) - Static smart contract analysis tool based on symbolic execution.

## Documentation [↑](#contents)

- [Official Documentation](https://docs.tact-lang.org/)
- [Learn with Tact by Example](https://tact-by-example.org/)

## Articles [↑](#contents)

- [Introduction to Blockchain](https://blog.ton.org/what-is-blockchain)
- [The Open Network](https://docs.ton.org/learn/introduction)

## Videos [↑](#contents)

- [Tact & Blueprint](https://www.youtube.com/@AlefmanVladimirEN-xb4pq/videos) - Made by [@alefman](https://t.me/alefman).

###### Chinese

- [TON 开发从入门到应用](https://openbuild.xyz/learn/challenges/2023609337/2939) - Made by Jason.
- [Tact & TON Basic 手把手學習](https://www.youtube.com/@ton101_zh) - Made by [@howard_peng](https://t.me/ton101_zh).

###### Russian

- [Tact & Blueprint](https://www.youtube.com/watch?v=isYBvzM-MfQ&list=PLOIvUFGfwP93tZI_WnaLyJsZlskU4ao92) - Made by [@alefman](https://t.me/alefman)
- [Tact development](https://www.youtube.com/watch?v=S6wlNsKUHpE&list=PLyDBPwv9EPsAJpR7R0cC4kgo7BjiMmUy7&index=1) - Made by [@nonam3e](https://t.me/nonam3e).

<!-- ## Podcasts [↑](#contents) -->

## Smart contracts [↑](#contents)

- [Tact Wallet Contract](https://github.com/tact-lang/contract-wallet) - This wallet contract supports gasless transactions, allows operations on behalf of the wallet by other contracts, and can execute a scalable number of operations in a single transaction.
- [Tact Payouts Contract](https://github.com/tact-lang/contract-payouts) - Perfect solution for on-chain payouts. This contract generates a list of text tickets for each address entitled to a payout. Tickets are signed transactions serialized as comments to be parsed by the smart contract.
- [TON VOTE Contracts](https://github.com/orbs-network/ton-vote-contracts/tree/main) - Smart contracts for [ton.vote](https://ton.vote/).
- [Simple DNS Contract](https://github.com/tact-lang/contract-dns-simple) - Contract that allows you to manage DNS records in a simple way. It also allows to burn fuses disallowing certain modifications of records.
- [NFT Standard Example](https://github.com/howardpen9/nft-template-in-tact) - Basic implementation of NFT standard that conforms to [TEP-62](https://github.com/ton-blockchain/TEPs/blob/master/text/0062-nft-standard.md) and [TEP-66](https://github.com/ton-blockchain/TEPs/blob/master/text/0066-nft-royalty-standard.md) standards. Made by [@howard_peng9](https://dune.com/Howard_Peng).
- [TonDynasty](https://github.com/Ton-Dynasty/tondynasty-contracts) - Ton Dynasty Contracts is a library built by the Perman Lab Team for efficient smart contract development using Tact. It provides a number of templates, including contract traits, for Ton developers to utilize. Perman Lab will always stand by you. Ask for our help in [Perman Lab Community](https://t.me/permanlab).
- [Tact Fireworks](https://github.com/ton-community/tact-fireworks) - Educational contract for learning Tact and writing tests for special cases, such as exit codes.
- [Ready-to-use templates for Jetton & NFT](https://github.com/Laisky/tact-utils) - Provides ready-to-use templates for Jetton, NFT, Traits, as well as some commonly used tools.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## Related

- [awesome-ton](https://github.com/ton-community/awesome-ton) - Awesome list for TON Blockchain.

[tl]: https://tact-lang.org
[td]: https://docs.tact-lang.org
[tlchat]: https://t.me/tactlang
[tlchat_ru]: https://t.me/tactlang_ru
[tk]: https://t.me/tact_kitchen
[tlx]: https://x.com/tact_language
