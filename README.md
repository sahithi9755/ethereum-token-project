# MyToken (MTK) — ERC-20 Token Smart Contract

## 📘 Project Description
This project demonstrates how to create and deploy a custom ERC-20 cryptocurrency token on the Ethereum blockchain using Solidity and Remix IDE.  
The goal is to understand how token standards work, how balances and transfers are handled on-chain, and how smart contracts power digital assets like real-world cryptocurrencies.

## 🎯 Objectives
By completing this project, you will learn:
- Basics of blockchain and smart contract development
- How ERC-20 tokens work under the hood
- Deploying smart contracts on Ethereum networks
- Interacting with deployed contracts using RemixIDE
- Testing token transfers and allowance approvals

## 🧠 What is ERC-20?
ERC-20 is a widely-used token standard that defines:
- How tokens can be transferred
- How balances are tracked
- How wallets and exchanges can interact with tokens

It is the foundation for thousands of popular tokens like:
USDT, LINK, DAI, SHIB, etc.

## 🪙 Token Information
| Parameter | Value |
|----------|--------|
| **Token Name** | MyToken |
| **Symbol** | MTK |
| **Decimals** | 18 |
| **Total Supply** | 1,000,000 MTK |
| **Standard** | ERC-20 |

## ✨ Features
- ✔ Standard ERC-20 Implementation
- ✔ Transfer tokens between wallets
- ✔ Approve spending for third-party addresses
- ✔ TransferFrom for delegated transfers
- ✔ Secure balance + allowance tracking
- ✔ Emits Transfer & Approval events

## ⚙️ Technologies Used
| Tool | Purpose |
|------|---------|
| **Solidity** | Smart contract development |
| **Remix IDE** | Compile and deploy contract |
| **MetaMask** (optional) | Wallet integration |
| **JavaScript VM / Test Networks** | Contract testing |

## 🚀 Deployment Steps
1. Go to **https://remix.ethereum.org/**
2. Create a new file `MyToken.sol`
3. Paste the ERC-20 token smart contract code
4. Compile (Solidity version 0.8.x)
5. Deploy using JavaScript VM or Ethereum Testnet
6. Verify token details using contract functions (balanceOf, name, symbol…)

## 🧪 Testing Instructions
| Test | Method |
|------|--------|
| Check balance | `balanceOf(address)` |
| Transfer tokens | `transfer(to, amount)` |
| Approve allowance | `approve(spender, amount)` |
| Spend tokens on behalf | `transferFrom(from, to, amount)` |

### Example (Check Balance)
```solidity
balanceOf(0xYourAddress)
## 📂 Repository Structure
📁 MyToken-ERC20
├── MyToken.sol
└── README.md
