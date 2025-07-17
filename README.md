#  CodTech Task 3 - DeFi Lending & Borrowing DApp

A decentralized finance (DeFi) application that allows users to lend and borrow crypto tokens with a simple interest-based model. Developed as part of the **CodTech Blockchain Internship**.

---

## 📌 Features

- ✅ Deposit supported tokens like DAI, LINK, WETH, FAU.
- 🔁 Borrow tokens by locking collateral based on LTV (Loan-to-Value) ratio.
- 🪙 Earn custom reward tokens (LAR) as interest on deposits.
- 🔐 Secure contract interactions with OpenZeppelin's Ownable and IERC20.
- 💰 Fixed APY for borrowing interest.
- 📉 Collateral withdrawal after loan repayment.

---

## 🧰 Tech Stack

- **Smart Contracts:** Solidity + Truffle + Chainlink price feeds
- **Frontend:** React (Next.js) + Tailwind CSS + Web3.js
- **Blockchain:** Ganache for local development, deployed to Ethereum testnet
- **Wallet:** MetaMask

---

## ⚙️ How to Run Locally

### ✅ Prerequisites

- Node.js & npm
- Ganache (GUI or CLI)
- MetaMask extension in your browser

---

### 🚀 Installation Steps

```bash
git clone https://github.com/madhusudan-shukla/codtech-task-3-defi-lending.git
cd codtech-task-3-defi-lending
npm install



Compile & Deploy Contracts

bash
Copy
Edit
truffle compile
truffle migrate --network development
⚠️ Make sure Ganache is running on port 8545 before deploying


                                                                                                                                                                       
