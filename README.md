# Team1 × Avalanche — JNTUH Workshop

[Avalanche](https://img.shields.io/badge/Avalanche-Fuji%20Testnet-E84142?style=for-the-badge)
![Solidity](https://img.shields.io/badge/Solidity-Development-363636?style=for-the-badge)
![Foundry](https://img.shields.io/badge/Foundry-Smart%20Contracts-orange?style=for-the-badge)
![Workshop](https://img.shields.io/badge/Workshop-Team1%20×%20JNTUH-blue?style=for-the-badge)

A hands-on record of my participation in the Team1 University Connect –
JNTU Hyderabad workshop focused on blockchain development and the
Avalanche ecosystem.

## 🚀 Overview

This repository documents my learning and hands-on work from the
Team1 × Avalanche workshop conducted at JNTUH.

The workshop covered:

- Blockchain fundamentals
- Avalanche ecosystem
- Avalanche L1s
- Core Wallet
- Fuji Testnet
- Solidity
- Remix
- NFT deployment
- Foundry
- Git Bash
- Smart contract deployment
- Avalanche L1 creation
- Cascade
- Vibe coding

## ✅ Workshop Tasks

| Task | Topic | Status |
|---|---|---|
| 01 | Builder Hub | ✅ Completed |
| 02 | Core Wallet | ✅ Completed |
| 03 | Testnet AVAX | ✅ Completed |
| 04 | First Smart Contract | ✅ Completed |
| 05 | NFT Deployment | ✅ Completed |
| 06 | Solidity & Foundry | ✅ Completed |
| 07 | Avalanche L1 | ✅ Completed |
| 08 | Cascade Profile | ✅ Completed |

**8/8 tasks completed successfully.**

## 📂 Repository Structure

```text
task-01-builder-hub/          Builder Hub setup
task-02-core-wallet/          Core Wallet setup
task-03-testnet-avax/         Testnet AVAX
task-04-first-smart-contract/ HelloJNTUH contract
task-05-nft/                   NFT deployment
task-06-foundry/              Foundry development & deployment
task-07-avalanche-l1/         Avalanche L1 creation
task-08-cascade/              Cascade profile
vibe-coding/                  Workshop Vibe Coding session
screenshots/                 Workshop evidence
docs/                        Notes and learning documentation

## 🛠️ Technologies & Tools

- Solidity
- Remix IDE
- Foundry
- Forge
- Cast
- Git Bash
- Avalanche Fuji Testnet
- Core Wallet
- Avalanche Explorer

## 📜 Smart Contract Work

One of the main practical exercises involved creating and deploying
Solidity smart contracts to Avalanche Fuji Testnet.

I also worked with Foundry to compile and deploy contracts from the
command line.

Example commands used:

```bash
forge build
forge test

forge create src/Counter.sol:Counter \
  --rpc-url $FUJI_RPC \
  --private-key $PK \
  --broadcast

Key Learnings are:

This workshop gave me practical exposure to:

How blockchain networks work
Wallets and blockchain addresses
Testnet environments
Smart contracts
Transactions and gas
Contract deployment
RPC endpoints
Solidity development
CLI-based blockchain development
Avalanche L1 concepts

One important lesson was that a blockchain prototype can solve
double-voting at the wallet level, but one-wallet-one-vote does not
necessarily mean one-human-one-vote. Preventing Sybil attacks requires
an additional identity or eligibility mechanism.

📝 Task Highlights

Task 4 — First Smart Contract

Created and deployed a simple Solidity smart contract using Remix on the Avalanche Fuji Testnet.

The contract demonstrates:

State variables
Functions
Reading contract state
Updating contract state
Transactions on Avalanche Fuji
Task 5 — NFT

Created an ERC-721 NFT using OpenZeppelin tooling and deployed it on the Avalanche Fuji Testnet.

The task provided practical experience with:

ERC-721
OpenZeppelin
Remix
Contract deployment
NFT minting
Blockchain explorers
Task 6 — Solidity & Foundry

This was one of the most technically challenging parts of the workshop.

I worked with:

Foundry
Forge
Cast
Git Bash
Solidity
RPC endpoints
Avalanche Fuji Testnet

I also deployed a Solidity contract directly from the command line.

Task 7 — Avalanche L1

Created an Avalanche L1 using the provided testnet workflow.

This introduced concepts around:

Avalanche L1 architecture
Chain configuration
Chain ID
RPC endpoints
Testnet infrastructure
🗳️ SimplePoll

As part of the workshop's Vibe Coding / development work, I also experimented with a simple on-chain voting contract.

The contract allows an address to vote for either Option A or Option B.

It implements a basic:

One wallet → one vote

mechanism.

Important limitation

This does not mean:

One person → one vote.

A person can potentially create multiple wallets.

Therefore, a production-grade voting system would require an additional identity, eligibility, or Sybil-resistance mechanism.

💻 Vibe Coding

The workshop also included a Vibe Coding session where I worked together with:

Vijay Banothu
Devanmani

We built and presented a project during the session.

Although we didn't win the final challenge, the experience of rapidly building, collaborating, debugging, and presenting a project was one of the highlights of the workshop.

📚 What I Learned

This workshop helped me move from understanding blockchain concepts theoretically to actually interacting with a blockchain.

Key learning areas included:

Blockchain fundamentals
Avalanche ecosystem
Avalanche Fuji Testnet
Smart contracts
Solidity
Remix
ERC-721 NFTs
Foundry
Forge
Cast
RPC endpoints
Contract deployment
Avalanche L1s
Web3 development workflow
🔐 Security

This repository intentionally does not contain:

Private keys
Seed phrases
API keys
Passwords
Wallet recovery phrases
.env files containing secrets

Never commit wallet credentials or other sensitive information to GitHub.

🙌 Credits

Thanks to Team1 India, the Avalanche community, the workshop organizers, speakers, mentors, and everyone involved in making the JNTUH workshop possible.

The workshop provided a practical environment to learn, experiment, build, and deploy.

📌 Disclaimer

This repository is a personal learning record of my participation in the workshop.

Contracts and projects in this repository are intended for educational purposes and testnet experimentation.

## GITHUB REPO STRUCTURE :

team1-avalanche-jntuh-workshop/
│
├── README.md
│
├── task-01-builder-hub/
│   └── README.md
│
├── task-02-core-wallet/
│   └── README.md
│
├── task-03-testnet-avax/
│   └── README.md
│
├── task-04-first-smart-contract/
│   └── HelloJNTUH.sol
│
├── task-05-nft/
│   ├── README.md
│   └── NFT.sol
│
├── task-06-foundry/
│   ├── src/
│   │   ├── Counter.sol
│   │   └── SimplePoll.sol
│   ├── script/
│   ├── test/
│   ├── foundry.toml
│   └── README.md
│
├── task-07-avalanche-l1/
│   └── README.md
│
├── task-08-cascade/
│   └── README.md
│
├── vibe-coding/
│   ├── README.md
│   └── project/
│
├── screenshots/
│   ├── workshop/
│   ├── remix/
│   ├── foundry/
│   └── explorer/
│
└── docs/
    └── workshop-notes.md