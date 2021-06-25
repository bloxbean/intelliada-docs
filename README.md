# Overview

IntelliAda is an IntelliJ plugin for Cardano blockchain. Using this plugin developers can interact with Cardano directly from their IDE. In the current version of this plugin, developers can mint native tokens, transfer Ada / Native tokens from one address to another inside their IDE. This plugin doesn't provide any stake pool management related features.

In the current version, plugin provides integration with Blockfrost Cardano Api. Support for other backends like Cardano wallet, Cardano GraphQL will be added in future release.

**GitHub**: [https://github.com/bloxbean/intelliada](https://github.com/bloxbean/intelliada)

**Plugin page:**  [https://plugins.jetbrains.com/plugin/17109-intelliada-cardano-integration](https://plugins.jetbrains.com/plugin/17109-intelliada-cardano-integration)

**Features** 

* Account Management
  * Create new testnet/mainnet accounts
  * Import an account by providing 24w mnemonic phrase
* Transfer transaction
  * Transfer Ada or any native tokens
* Native Token Minting
* Script Management
  * Create script \(sig, all, any, atLeast, after, before\)
  * Use policy scripts while minting new native tokens
* Metadata support
  * Add metdata to the transaction
  * Supports raw json
  * Metadata editor to build metadata
  * Metadata templates
* View transactions
* Utxo explorer
  * View utxos of a specific address
  * Select utxos during transaction submission \(Optional\)
* Blockfrost integration
  * Integrates with Blockfrost Cardano Api



