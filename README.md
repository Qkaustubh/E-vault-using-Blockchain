# Blockchain eVault System for Legal Records

## 🚀 Overview
This repository hosts the **Blockchain eVault System for Legal Records**, designed to **revolutionize legal record management** using **blockchain technology**. The project ensures **security, transparency, and efficiency** in managing sensitive legal documents.

## 🏗️ Tech Stack
- **Smart Contracts**: Solidity (Authentication and Authorization)
- **Frontend**: React.js + ChakraUI (User Interface)
- **Backend**: Node.js + Express (API & Web Server)
- **Blockchain Interaction**: Web3.js
- **Database**: SQLite3 + Sequelize (Efficient Storage)

## 🛑 Existing Problems in Legal Record Management
- ⚠️ **Lack of Transparency** – Difficulty in verifying document authenticity
- ⚠️ **No Long-term Data Storage** – Vulnerability to data loss
- ⚠️ **Server Downtime Risks** – Centralized systems prone to failures
- ⚠️ **Improper Authorization** – Weak access control mechanisms
- ⚠️ **Complex Sharing Mechanisms** – Inefficient document access protocols

## ✅ Proposed Solution: Blockchain eVault System
- 🔹 **Dispute Resolution**: Establishes a transparent evidence-sharing platform.
- 🔹 **Role-Based Access**: Implements **fine-grained authorization** and **KYC authentication**.
- 🔹 **Third-Party API Integration**: Provides seamless **legal database connectivity**.
- 🔹 **Blockchain-Powered Document Sharing**: Secured via **smart contracts**.
- 🔹 **Accelerated Court Proceedings**: Enhances case handling efficiency with **real-time verification**.

## 🏛️ System Architecture


## 🏗️ Project Structure
### 🔹 Smart Contracts (Solidity)
- Implements **user authentication & authorization**.
- Manages document access permissions via **Ethereum-based smart contracts**.
- Enforces **tamper-proof document integrity**.

### 🔹 Frontend (React.js + ChakraUI)
- **User-friendly dashboard** for document management.
- Features **real-time tracking**, **uploading**, and **sharing**.
- Intuitive UI with seamless blockchain interactions.

### 🔹 Backend (Node.js + Express + Web3.js)
- **Handles API requests & user authentication**.
- Manages **blockchain transactions** via Web3.js.
- Uses **SQLite3 + Sequelize** for additional structured data storage.

## 📡 API Endpoints
### 🔹 Authentication & User Management
- **Login User**: `POST /api/login` (Params: `email`, `password`) → Returns auth key
- **Sign Up User**: `POST /api/signup` (Params: `username`, `name`, `email`, `password`) → Success response

### 🔹 Document Handling
- **Upload Document**: `POST /api/upload` (Params: `file`, `doc_type`, `doc_id`, `owner`, `user_id`) → Stores file securely
- **Share Access**: `POST /api/share` (Params: `toAddress`, `auth key`) → Grants permission
- **List Documents**: `GET /api/list` (Params: `auth key`) → Returns all owned/shared documents
- **Download File**: `GET /api/download` (Params: `document ID`) → Secure retrieval

## 🛠️ Installation & Setup
### 🔹 Prerequisites
- **Node.js** (v16+)
- **MetaMask Wallet** (Configured for Ethereum network)
- **Ganache** (For local blockchain testing)

### 🔹 Steps to Run the Project
```sh
# Clone Repository
git clone https://github.com/your-repo/blockchain-evault.git
cd blockchain-evault

# Install Dependencies
npm install

# Start Backend Server
cd backend
node server.js

# Start Frontend
cd ../frontend
npm start
```

## 🔥 Key Features & Advantages
- ✅ **Blockchain Security** – Data is immutable & secure
- ✅ **Decentralized Storage** – No central point of failure
- ✅ **Role-Based Authorization** – Only authorized users access documents
- ✅ **Smart Contract Execution** – Enforces rules without intermediaries
- ✅ **Interoperability** – Seamless API for third-party integrations

## 📜 Summary
The **Blockchain eVault System** is a **secure and decentralized solution** for legal record management. By leveraging **Ethereum smart contracts, AI-powered document authentication, and an efficient API-driven architecture**, this project significantly improves **data integrity, document security, and legal process automation**.

🔹 **Status**: 🚧 Under Development 🔹
🔹 **Next Steps**: Testing & Deployment 🔹

🌟 **Contributions Welcome!** Feel free to fork, raise issues, and contribute! 🚀

