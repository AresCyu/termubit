# Termubit (TRB) Core Official Repository 🚀

**Termubit (TRB)** is a decentralized Layer-1 blockchain platform engineered for security, scalability, and long-term value. Built on a robust Scrypt-based architecture, Termubit introduces a balanced economic model with a focus on scarcity and network stability.

---

## 📊 Technical Specifications

| Parameter | Value |
| :--- | :--- |
| **Ticker** | TRB |
| **Algorithm** | Scrypt (Proof of Work) |
| **Total Max Supply** | 281,000,000 TRB |
| **Block Target Time** | 3 Minutes (180 Seconds) |
| **Difficulty Retarget** | DigiShield (Every Block) |

---

## ⚙️ Core Mechanics

- **Scrypt Proof-of-Work:** Memory-intensive hashing to ensure mining decentralization and ASIC resistance.
- **3-Minute Block Target:** Optimized for efficient network propagation and significantly reduced orphan block rates compared to faster chains.
- **DigiShield:** Real-time difficulty adjustment mechanism to protect the network against hashrate volatility and "flash-mining" attacks.

---

## 🛠 Installation & Build Guide (Linux/Ubuntu)

### 1. Install Required Dependencies
Before building, ensure your system has the necessary libraries installed:
```bash
sudo apt-get update && sudo apt-get install -y build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libdb5.3++-dev libdb5.3-dev
