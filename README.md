# Project for State of Art DApp

Welcome to the test project. This project aims to check skills of each kind of developers seamlessly across multiple blockchains, including Solana, Ethereum, and BNB.

---

## Voting System Integration

This project now includes a full-featured Ethereum-based Voting System backend, integrated in the `server/voting/` directory. All voting API endpoints are available under `/api/voting/`.

### How to Run the Voting Backend

1. **Install dependencies**
   ```sh
   npm install
   ```
2. **Start a local Hardhat node** (in one terminal):
   ```sh
   npm run node
   ```
3. **Deploy the contract** (in another terminal):
   ```sh
   npm run deploy:local
   ```
4. **Start the backend server**:
   ```sh
   npm run server
   ```
   Or, for all at once (node, deploy, server):
   ```sh
   npm run voting:dev
   ```

### API Documentation
- See [`docs/API_DOCUMENTATION.md`](docs/API_DOCUMENTATION.md) for all available endpoints and usage examples.

---

## Table of Contents
- [Overview](#overview)
- [Current Functionality](#current-functionality)
- [Expansion Requirements](#expansion-requirements)
- [Games](#games)
- [Wallet Integration](#wallet-integration)
- [Security and Transactions](#security-and-transactions)
- [Performance and Scalability](#performance-and-scalability)
- [Voting System Integration](#voting-system-integration)
- [Contributing](#contributing)
- [License](#license)

## Overview

The test project is a simple online betting site that offers a variety of games, including Dice, Slots, Flip, and others. Users can connect their wallets to participate in these games, place bets, and manage their funds directly through the site.

## Current Functionality

- Integration with the Solana blockchain.
- Users can connect their Phantom wallet to interact with the platform.
- Users can play Dice, Slots, Flip, and other betting games using their connected wallet.
- The platform processes bets and payouts securely on the Solana blockchain.
- **Ethereum Voting System backend available at `/api/voting/`**

## Expansion Requirements

We are expanding the functionality to also work on the Ethereum and BNB chains. The requirements include:

1. **Multi-Chain Support**: Extend support to include Ethereum and BNB chains in addition to Solana.
2. **Wallet Integration**: Add support for MetaMask wallet to enable users to connect using Ethereum and BNB, while maintaining the current Phantom wallet connectivity for Solana users.
3. **Cross-Chain Compatibility**: Ensure that the betting functionalities work seamlessly across Solana, Ethereum, and BNB chains.

## Games

- **Dice**: A classic betting game where users bet on the outcome of dice rolls.
- **Slots**: A slot machine game where users spin to match symbols for a payout.
- **Flip**: A coin flip game where users bet on the outcome of a coin toss.
- **Other Games**: Additional betting games providing various betting experiences.

## Wallet Integration

- **Phantom Wallet**: Currently integrated for Solana users.
- **MetaMask Wallet**: To be integrated for Ethereum and BNB users.

## Security and Transactions

- Ensure secure processing of bets and payouts on all supported blockchains.
- Implement robust security measures to protect user funds and data.

## Performance and Scalability

- Optimize the platform for high performance and scalability to handle a large number of users and transactions across multiple blockchains.

# Goal of Project
## 1. Well-structured design and high-quality code
## 2. Innovative and user-friendly design
## 3. Performance and scalability

