# Stellar Voting Mini dApp

## Overview

This project is a **mini decentralized voting application** built using the Stellar Soroban smart contract platform.

The application allows users to connect their wallet and vote for proposals. Each vote is recorded on the Stellar blockchain, ensuring transparency and immutability.

This project demonstrates a complete **end-to-end decentralized application (dApp)** including:

- Smart contract interaction
- Wallet authentication
- Frontend dashboard
- Live voting results

---

## Features

- Connect wallet using Freighter
- Vote on blockchain proposals
- Live vote result updates
- Leader detection
- Simple and responsive dashboard UI

---

## Tech Stack

- Next.js
- TypeScript
- Stellar Soroban
- Freighter Wallet
- Tailwind CSS

---

## Demo Video

The demo video shows the full functionality of the dApp including wallet connection and voting.

Video file is included in this repository.

---

## Tests

The project includes basic unit tests to verify voting logic.

Example test output:

```
PASS tests/voting.test.ts
✓ Proposal 1 vote calculation
✓ Proposal comparison
✓ Total vote calculation
```

Minimum **3 tests are passing successfully**.

---

## Installation

Install dependencies:

```
npm install
```

Run the project:

```
npm run dev
```

---

## Smart Contract

This project interacts with a **Soroban smart contract deployed on the Stellar Testnet**.

The smart contract stores vote counts for proposals and allows users to submit votes through blockchain transactions.

---

## Project Structure

```
stellar-voting-dapp
│
├── app
│   ├── page.tsx
│   ├── contract.ts
│
├── tests
│   └── voting.test.ts
│
├── README.md
└── package.json
```

---

## Future Improvements

Possible improvements for this project:

- Multiple proposals
- Voting history
- DAO governance system
- Analytics dashboard

---

## Author

Chaitanya

Blockchain Student | Stellar Soroban Developer
