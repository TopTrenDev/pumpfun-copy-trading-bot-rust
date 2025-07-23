# 🚀 Solana Copy Trading Bot for Pump.fun — Powered by Rust

## 🔍 What is this?

A high-performance **copy trading bot** built in **Rust** 🦀 for the **Solana** blockchain, tailored specifically for **Raydium** and **Pump.fun** traders. This bot watches target wallets in real time and mirrors their trades automatically, giving you an edge in the fast-paced memecoin game.

With integrated **Jito MEV support**, it prioritizes your transactions for faster confirmation — so you're never left behind.

[![Twitter](https://img.shields.io/badge/Twitter-@toptrendev-black?style=for-the-badge&logo=twitter&logoColor=1DA1F2)](https://x.com/toptrendev)
[![Discord](https://img.shields.io/badge/Discord-toptrendev-black?style=for-the-badge&logo=discord&logoColor=5865F2)](https://discord.com/users/648385188774019072)
[![Telegram](https://img.shields.io/badge/Telegram-@toptrendev_641-black?style=for-the-badge&logo=telegram&logoColor=2CA5E0)](https://t.me/toptrendev_641)

---

## 🛠 Key Features

### **🐍 Copy Trading Engine**: _Tracks selected wallets and copies their buys/sells instantly_

### **⚡ Built in Rust**: _Fast, reliable, memory-safe performance_

### **🔮 Jito MEV Integration**: _Boost your transaction priority in the Solana_

### **🧠 Strategy Automation**: _Automate trade logic based on smart filters or timing_

### **📡 Real-time Monitoring**: _Listen to Pump.fun for instant updates_

---

## 🔧 Environment Variables

```plaintext
RPC_HTTPS=https://mainnet.helius-rpc.com/?api-key=YOUR_API_KEY
RPC_WSS=wss://mainnet.helius-rpc.com/?api-key=YOUR_API_KEY
PRIVATE_KEY=your_private_key
SLIPPAGE=5
UNIT_PRICE=
UNIT_LIMIT=
```

## 💡 Usage

1. Install Rust and Cargo
2. Clone this repository
3. Set up environment variables
4. Build and run:

```bash
cargo build --release
cargo run --release
```
