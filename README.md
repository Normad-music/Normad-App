# 🚀 Normad App

> Transparent Payments for Artists — Powered by Stellar

Normad is a blockchain-powered payment infrastructure that ensures artists are paid fairly, transparently, and automatically.

Built for creatives who are tired of guessing where their money went.

---

## 🏆 Hackathon Submission

Normad solves one of the biggest problems in the creative economy:

**Lack of payment transparency.**

Artists often:
- Don't know how revenue is calculated
- Experience delayed payouts
- Cannot verify platform fees
- Have no real-time visibility into earnings

Normad fixes this using on-chain payment distribution on the Stellar network.

---

## 💡 What Makes Normad Different?

✅ On-chain revenue splits  
✅ Automated smart contract payouts  
✅ Real-time earnings dashboard  
✅ Immutable payment history  
✅ Wallet-to-wallet payments  

Every transaction is verifiable.

No hidden fees.
No opaque reporting.

---

## ⚙️ How It Works

1. A platform generates revenue.
2. Revenue is sent to the Normad smart contract.
3. The contract distributes funds based on predefined splits.
4. Artists receive funds directly in their Stellar wallets.
5. All transactions are permanently recorded on-chain.

---

## 🏗️ Architecture

### 🔹 Frontend
- React (Vite)
- TailwindCSS
- shadcn/ui
- Wallet integration
- Artist dashboard

### 🔹 Backend
- Node.js
- REST API
- Authentication (JWT)
- Smart contract interaction
- Transaction indexing

### 🔹 Smart Contract
- Built on Stellar
- Soroban smart contracts
- Automated revenue distribution
- Transparent split logic

---

## 🛠️ Tech Stack

Frontend:
- React + Vite
- TailwindCSS
- shadcn/ui
- TypeScript

Backend:
- Node.js
- PostgreSQL / MongoDB

Blockchain:
- Stellar Network
- Soroban Smart Contracts

---

## 📦 Project Structure

normad-app/
├── frontend/
├── backend/
├── contract/
└── README.md

---

## 🚀 Running Locally

### Clone Repo

```bash
git clone https://github.com/your-username/normad-app.git
cd normad-app

Frontend
cd frontend
npm install
npm run dev
Backend
cd backend
npm install
npm run dev
Contract
cd contract
# build & deploy using Soroban CLI


# Blockchain
VITE_STELLAR_RPC_URL=
VITE_CONTRACT_ADDRESS=

# Backend
DATABASE_URL=
JWT_SECRET=
STELLAR_SECRET_KEY=