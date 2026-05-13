<p align="center">
  <img src="https://raw.githubusercontent.com/your-username/your-repo/main/logo.png" width="200" alt="Termubit Logo">
</p>

<h1 align="center">Termubit Core [TRB]</h1>

<p align="center">
  <strong>A Decentralized Layer-1 Blockchain for the Next Generation of Gaming Economies.</strong><br>
  Based on Scrypt PoW | Fast Transactions | Community Driven
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0--Alpha-orange" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/Blockchain-Layer--1-blue" alt="Layer-1">
</p>

---

## What is Termubit?

**Termubit (TRB)** is a decentralized, peer-to-peer digital currency and Layer-1 blockchain platform. Forked from the robust Dogecoin/Litecoin codebase, Termubit is specifically optimized to serve as the backbone for gaming ecosystems, starting with our dedicated Minecraft server community.

Unlike traditional tokens, Termubit operates on its own independent infrastructure, providing high security through Proof of Work (PoW) while maintaining low latency and near-zero transaction fees.

## Core Features

- **Gaming Integration:** Designed to bridge the gap between virtual economies and real-world value.
- **Fair Launch:** No pre-mine, no ICO. Everyone has a fair chance to participate in the network.
- **Scrypt Algorithm:** Energy-efficient mining compared to SHA-256, allowing for a more decentralized mining landscape.
- **Lightning Fast:** 5 minute block times ensure that in-game transactions and transfers are confirmed almost instantly.

## Specifications

| Features | Details |
| :--- | :--- |
| **Ticker** | $TRB |
| **Algorithm** | Scrypt (Proof of Work) |
| **Max Supply** | 182M TRB |
| **Block Time** | 5 Minutes |
| **Difficulty Retarget** | DigiShield (Every Block) |
| **Block Reward** | 75 TRB |

## How It Works

### 1. Network Consensus
Termubit utilizes the **Scrypt Proof of Work** consensus mechanism. Miners use their hardware to solve complex mathematical puzzles, securing the network and validating transactions. This ensures that the ledger is immutable and resistant to centralized control.

### 2. The Ecosystem Loop
The Termubit ecosystem is built on a "Play-to-Earn" philosophy:
*   **Earn:** Players on the integrated Minecraft server earn $TRB through quests, trading, and milestones.
*   **Transact:** TRB can be sent between players or used to purchase unique in-game assets stored on the blockchain.
*   **Hold:** As a Layer-1 coin, TRB can be stored in secure desktop or mobile wallets for long-term value.

### 3. Difficulty Stability
By implementing **DigiShield**, Termubit protects itself against "multi-pool" mining spikes. The difficulty adjusts every single block, ensuring that even if large amounts of hash power enter or leave the network, the 1-minute block time remains stable.

## Getting Started

### Installation (Build from Source)

To build the Termubit Core daemon and CLI, ensure you have the necessary dependencies installed (Boost, Libevent, BerkeleyDB 4.8, etc.), then run:

```bash
./autogen.sh
./configure
make
sudo make install # Optional
