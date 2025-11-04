# TTA - Compiled Binaries

This directory contains the compiled release binaries for the TTA (ThisThingAgain) cryptocurrency project.

## Binaries

### ThisThingAgain
The main daemon for the TTA cryptocurrency network. This is the core node software that:
- Validates and relays transactions
- Participates in the peer-to-peer network
- Maintains the blockchain
- Provides RPC interface for wallets and other tools

**Usage:** `./ThisThingAgain [options]`

### simplewallet
Command-line wallet application for managing TTA coins. Features include:
- Create and manage wallets
- Send and receive TTA
- View balance and transaction history
- Generate addresses

**Usage:** `./simplewallet [options]`

### walletd
Wallet daemon with RPC interface (also known as Payment Gate Service). This provides:
- JSON-RPC API for wallet operations
- Suitable for integration with services and applications
- Multi-wallet support
- Programmatic access to wallet functions

**Usage:** `./walletd [options]`

### miner
Standalone mining application for TTA cryptocurrency. Allows you to:
- Mine TTA coins
- Connect to a daemon
- Configure mining threads
- Monitor hashrate

**Usage:** `./miner [options]`

### connectivity_tool
Diagnostic and connectivity testing tool for the TTA network. Useful for:
- Testing peer-to-peer connections
- Debugging network issues
- Requesting network state information
- Testing RPC endpoints

**Usage:** `./connectivity_tool [options]`

## Build Information

- **Build Type:** Release
- **Compiler:** GCC 13.3.0
- **Boost Version:** 1.83.0
- **CMake Version:** 3.31.6
- **Build Date:** 2025-11-04

## Notes

These binaries are compiled with optimizations enabled (-Ofast -flto) for maximum performance.

For more information about configuration options, run each binary with `--help` flag.
