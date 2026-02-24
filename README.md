# 🚀 Normad App

Normad is a transparent payment infrastructure for artists built on blockchain.

Too often, artists are underpaid, paid late, or lack visibility into how their revenue is calculated. Normad solves this problem by leveraging the Stellar blockchain to provide transparent, automated, and verifiable payments.

With Normad, every payment is traceable. Every split is verifiable. Every artist gets clarity.

---

## 🌍 The Problem

Artists across creative industries struggle with:

- Opaque revenue reporting
- Delayed payouts
- Hidden platform fees
- No real-time tracking
- No ownership of financial data

Platforms control the numbers. Artists are left guessing.

---

## 💡 The Solution

Normad introduces:

- 🔎 On-chain revenue transparency
- ⚡ Automated smart contract payouts
- 💰 Direct wallet payments
- 📊 Real-time dashboard tracking
- 🔐 Immutable transaction records

All payments are processed through smart contracts on the Stellar network, ensuring fairness and transparency.

---

## 🏗️ Architecture

Normad is a fullstack Web3 application consisting of:

### 1️⃣ Frontend

Built with:

- React (Vite)
- TailwindCSS
- shadcn/ui
- TypeScript

Features:

- Artist dashboard
- Revenue overview
- Payment history
- Wallet connection
- Transaction verification

---

### 2️⃣ Backend

Built with:

- Node.js
- REST API
- JWT Authentication
- PostgreSQL / MongoDB

Responsibilities:

- User authentication
- Revenue data aggregation
- Smart contract interaction
- Transaction indexing
- Role-based access (Artist / Platform)

---

### 3️⃣ Smart Contract (Stellar Soroban)

Built on Stellar using Soroban smart contracts.

Responsibilities:

- Revenue split logic
- Automated artist payouts
- On-chain transparency
- Immutable transaction records

---

## 🔄 How It Works

1. A platform generates revenue.
2. Payment is routed through Normad’s smart contract.
3. The contract distributes funds based on predefined splits.
4. Artists receive funds directly into their wallets.
5. All transactions are permanently recorded on-chain.

---

## 📦 Project Structure

normad-app/
│
├── frontend/        # React + Vite application
├── backend/         # Node.js API
├── contract/        # Stellar Soroban smart contract
└── README.md

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- TailwindCSS
- shadcn/ui
- TypeScript

### Backend
- Node.js
- REST API
- PostgreSQL / MongoDB
- JWT Authentication

### Blockchain
- Stellar Network
- Soroban Smart Contracts

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/normad-app.git
cd normad-app