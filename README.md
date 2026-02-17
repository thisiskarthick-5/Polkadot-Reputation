# 🟣 Polkadot Reputation

A Web3 reputation scoring system built on Polkadot.

Polkadot Reputation connects to a user's wallet, fetches real on-chain data from the Westend testnet, and calculates a dynamic reputation score based on blockchain activity.

---

## 🚀 Features

- 🔗 Wallet connection using Polkadot.js Extension
- 🌐 Live connection to Polkadot Westend Testnet
- 💰 Real balance fetching
- 📊 Transaction count (nonce) tracking
- 🧠 Weighted reputation scoring model
- 🏆 Tier classification (Bronze / Silver / Gold)
- 🎨 Polkadot-themed professional UI with loading animation

---

## 🏗 Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript (ES Modules)
- @polkadot/api
- @polkadot/extension-dapp

**Network**
- Polkadot Westend Testnet

---

## ⚙️ How It Works

1. User clicks "Connect Wallet"
2. Polkadot.js extension requests permission
3. Application connects to Westend RPC
4. On-chain account data is fetched:
   - Free balance
   - Transaction count (nonce)
5. A weighted scoring algorithm calculates reputation
6. User is assigned a tier:
   - 🟤 Bronze
   - ⚪ Silver
   - 🟡 Gold

---

## 🧮 Reputation Logic

Score is calculated using:

- Wallet balance weight
- Transaction activity weight
- Base trust score

Example:

- High balance + high transaction activity → Gold tier
- Moderate activity → Silver tier
- Low activity → Bronze tier

---

## 🖥 Installation & Running

1. Clone the repository

```bash
git clone <your-repo-link>
