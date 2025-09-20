
---

## Features

- Atomic swap between **TURON ERC-20 tokens** and **Bitcoin (BTC)**
- Fully **trustless** using HTLCs
- Supports both **Ethereum testnet/mainnet** and **Bitcoin testnet/mainnet**
- Refund mechanism for timelock expiry
- Python backend for orchestration and monitoring
- Deployment scripts for ERC-20 HTLC

---

## Prerequisites

- Python 3.9+
- Node provider for Ethereum (Infura, Alchemy)
- Bitcoin testnet/mainnet wallet
- ERC-20 TURON token deployed on Ethereum-compatible chain

---

## Setup Instructions

### 1. Install Python dependencies
```bash
pip install -r requirements.txt
ETH_NODE=https://goerli.infura.io/v3/YOUR_PROJECT_ID
PRIVATE_KEY=0xYOUR_ETH_PRIVATE_KEY
BTC_WALLET_NAME=BTC-Test-Wallet
python scripts/deploy_htlc.py
python scripts/deploy_htlc.py
python scripts/deploy_htlc.py
