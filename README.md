# 💼 Smart Money

## 📌 Overview
This project implements **Smart Money** functionality that allows users to deposit ETH, check the balance, and withdraw ETH either to their own address or to a specified address on the Ethereum blockchain.

---

## ⚙️ Features
- Deposit ETH into Smart Money  
- Check total ETH balance stored  
- Withdraw all ETH to the caller’s address  
- Withdraw all ETH to a given address  

---

## 🛠️ Technology Used
- Solidity (0.8.14)
- Ethereum Blockchain
- Remix IDE
- MetaMask Wallet

---

## 🚀 How to Use

### 1️⃣ Deploy
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
- `withToAddress(address)` → withdraw to a specified address  

---

## 🔐 Notes
- Any user can withdraw funds  
- Entire balance is transferred during withdrawal  
- Designed for learning and academic purposes  

---

## 👨‍💻 Author
Jatin Ukey  

---

## 📎 License
MIT License
0