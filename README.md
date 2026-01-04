# 💼 Wallet Smart Contract

## 📌 Overview
This project implements a **Wallet Smart Contract** that allows users to deposit ETH, check the contract balance, and withdraw ETH either to themselves or to a specified address.

---

## ⚙️ Features
- Deposit ETH into the smart contract  
- Check total ETH balance stored in the contract  
- Withdraw all ETH to caller’s address  
- Withdraw all ETH to a given address  

---

## 🛠️ Technology Used
- Solidity (0.8.14)
- Ethereum Blockchain
- Remix IDE
- MetaMask Wallet

---

## 🚀 How to Use

### 1️⃣ Deploy Contract
- Open Remix IDE  
- Compile `Wallet.sol`  
- Deploy using MetaMask  

---

### 2️⃣ Deposit ETH
- Call `deposit()`  
- Send ETH with the transaction  

---

### 3️⃣ Check Balance
- Call `getContractBalance()`  

---

### 4️⃣ Withdraw ETH
- `withdrawAll()` → withdraw to your address  
- `withToAddress(address)` → withdraw to specified address  

---

## 🔐 Notes
- Any user can withdraw funds
- Entire contract balance is transferred
- Designed for learning and academic purposes

---

## 👨‍💻 Author
Jatin Ukey

---

## 📎 License
MIT License
