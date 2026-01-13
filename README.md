# 🔐 Crypto Recovery Service - Smart Contract Escrow System

A full-stack, decentralized application implementing a trustless escrow system for cryptocurrency recovery services. Clients deposit service fees into a secure smart contract, which are automatically released to the service provider only upon successful delivery of verifiable proof of work.

## 🏗️ Architecture

This is a three-tier application:
1.  **Smart Contract** (`RecoveryEscrow.sol`): The core escrow logic on the Ethereum blockchain.
2.  **Backend API** (Node.js/Express): Handles business logic and interfaces with the blockchain.
3.  **Frontend Client** (React.js): A web interface for users to create and manage escrow agreements.

## 🚀 Quick Start

### Prerequisites
- Node.js (v18 or higher) & npm
- MetaMask browser extension
- Ethereum RPC endpoint (e.g., from [Alchemy](https://www.alchemy.com/))
- Test ETH on Sepolia (get from a [faucet](https://sepoliafaucet.com/))

### 1. Clone and Setup
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/crypto-recovery-escrow.git
cd crypto-recovery-escrow
