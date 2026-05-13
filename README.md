<p align="center">
  <img src="https://raw.githubusercontent.com/your-username/your-repo/main/logo.png" width="200" alt="Termubit Logo">
</p>

<h1 align="center">Termubit Core [TRB]</h1>

<p align="center">
  <strong>A Decentralized Peer-to-Peer Electronic Cash System.</strong><br>
  Open Source | High-Speed Settlement | Permissionless Infrastructure
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Mainnet--Ready-green" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License">
  <img src="https://img.shields.io/badge/Network-Layer--1-orange" alt="Layer-1">
</p>

---

## What is Termubit?

**Termubit (TRB)** is an innovative, decentralized cryptocurrency designed to function as a primary medium of exchange. Termubit provides a secure, transparent, and immutable ledger for global peer-to-peer transactions.

The mission of Termubit is to provide a functional alternative to traditional currencies by offering a scalable payment infrastructure that is not controlled by any central authority.

## Core Pillars

- **Medium of Exchange:** Optimized for high-velocity transactions and daily commercial use.
- **Decentralization:** No central server or authority. The network is maintained by a global community of miners and node operators.
- **Financial Sovereignty:** Users have total control over their private keys and funds at all times.
- **Low-Cost Transfers:** Engineering focuses on maintaining near-zero fees to ensure the network remains practical for micro-payments.

## Technical Specifications

| Parameter | Specification |
| :--- | :--- |
| **Ticker** | $TRB |
| **Consensus Mechanism** | Proof of Work (PoW) |
| **Hashing Algorithm** | Scrypt |
| **Max Supply** | 128.000.000 TRB |
| **Block Time** | 5 Minutes |
| **Difficulty Retarget** | DigiShield |
| **Transaction Fees** | Minimal / Dynamic |

## How It Works

### 1. Peer-to-Peer Network
Termubit operates on a distributed network of nodes. Every node maintains a full copy of the blockchain, ensuring that the history of all transactions is transparent and verifiable by anyone, anywhere.

### 2. Transaction Processing & Settlement
Unlike slower legacy systems, Termubit is engineered for speed. With a **5 minute block time**, transactions are confirmed and settled across the network rapidly. This makes it a viable tool for real-world merchant payments and rapid digital transfers.

### 3. Mining & Network Security
The network is secured via the **Scrypt Algorithm**. Miners provide computational power to validate transactions and secure the blockchain against double-spending attacks. In exchange for this work, miners receive a block reward, ensuring a fair and decentralized distribution of the currency.

### 4. Difficulty Management
To maintain the stability of the 5 Minutes block interval, Termubit utilizes **DigiShield**. This technology allows the network to adjust mining difficulty in real-time after every block, protecting the network from hashrate fluctuations and ensuring consistent payment processing times.

## Getting Started

### Building from Source (Linux/macOS)

To compile Termubit Core, ensure all dependencies are met (libboost, libevent, berkeleydb, etc.), then execute the following:

```bash
./autogen.sh
./configure
make
sudo make install

## To start the Termubit node and begin synchronizing with the network:

```bash
termubitd -daemon
