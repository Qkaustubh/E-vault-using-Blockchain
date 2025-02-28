Blockchain eVault System for Legal Records

🚀 Overview

This repository hosts the Blockchain eVault System for Legal Records, designed to revolutionize legal record management using blockchain technology. The project ensures security, transparency, and efficiency in managing sensitive legal documents.

🏗️ Tech Stack

Smart Contracts: Solidity (Authentication and Authorization)

Frontend: React.js + ChakraUI (User Interface)

Backend: Node.js + Express (API & Web Server)

Blockchain Interaction: Web3.js

Database: SQLite3 + Sequelize (Efficient Storage)

🛑 Existing Problems in Legal Record Management

⚠️ Lack of Transparency – Difficulty in verifying document authenticity⚠️ No Long-term Data Storage – Vulnerability to data loss⚠️ Server Downtime Risks – Centralized systems prone to failures⚠️ Improper Authorization – Weak access control mechanisms⚠️ Complex Sharing Mechanisms – Inefficient document access protocols

✅ Proposed Solution: Blockchain eVault System

🔹 Dispute Resolution: Establishes a transparent evidence-sharing platform.🔹 Role-Based Access: Implements fine-grained authorization and KYC authentication.🔹 Third-Party API Integration: Provides seamless legal database connectivity.🔹 Blockchain-Powered Document Sharing: Secured via smart contracts.🔹 Accelerated Court Proceedings: Enhances case handling efficiency with real-time verification.

🏛️ System Architecture

🔹 Workflow Overview



🔹 Project Roadmap



🏗️ Project Structure

🔹 Smart Contracts (Solidity)

Implements user authentication & authorization.

Manages document access permissions via Ethereum-based smart contracts.

Enforces tamper-proof document integrity.

🔹 Frontend (React.js + ChakraUI)

User-friendly dashboard for document management.

Features real-time tracking, uploading, and sharing.

Intuitive UI with seamless blockchain interactions.

🔹 Backend (Node.js + Express + Web3.js)

Handles API requests & user authentication.

Manages blockchain transactions via Web3.js.

Uses SQLite3 + Sequelize for additional structured data storage.

📡 API Endpoints

🔹 Authentication & User Management

Login User: POST /api/login (Params: email, password) → Returns auth key

Sign Up User: POST /api/signup (Params: username, name, email, password) → Success response

🔹 Document Handling

Upload Document: POST /api/upload (Params: file, doc_type, doc_id, owner, user_id) → Stores file securely

Share Access: POST /api/share (Params: toAddress, auth key) → Grants permission

List Documents: GET /api/list (Params: auth key) → Returns all owned/shared documents

Download File: GET /api/download (Params: document ID) → Secure retrieval

#   E - v a u l t - u s i n g - B l o c k c h a i n  
 