# DecentRaised: Elevating Crowdfunding through Ethereum Blockchain

DecentRaised is an innovative crowdfunding platform designed to leverage the Ethereum blockchain to enhance the security, transparency, and accessibility of fundraising campaigns.

## Problem Statement and Necessity

Crowdfunding is a popular method for raising funds for various causes. However, existing platforms face challenges:

- **Security:** Traditional e-payment systems are vulnerable to hacking despite encryption. Blockchain offers superior security through decentralization.
- **Transparency and Anti-Fraud:** Many platforms lack transparency, raising concerns about fund misuse. DecentRaised ensures full visibility of fund usage to reduce fraud.
- **Global Contribution:** Geographic limitations can restrict international contributions. Blockchain allows global participation seamlessly.

Inspired by successful initiatives like [CryptoRelief](https://www.cryptorelief.in), DecentRaised aims to set a new standard in crowdfunding.

## Tech Stack

- **Frontend:** Next.js, Chakra UI
- **Smart Contracts:** Solidity
- **Blockchain Interaction:** Web3.js

## Setup and Installation

1. **Clone the Repository:** Fork and clone the project to your local machine.
2. **Install Dependencies:** Run `yarn install` to install the necessary packages.
3. **Run the Application Locally:** Execute `yarn dev` to start the development server.

## Prerequisites

- **MetaMask:** Install MetaMask as a Google Chrome extension and create an account.
- **Ethereum:** Request Ether from [Rinkeby Faucet](https://faucet.rinkeby.io/) for testing purposes.

## Deploying Your Own Contract

1. **Create an Account on Infura:** Sign up at [Infura](https://infura.io).
2. **Setup Environment:**
   - Create a `.env` file in the Ethereum directory with the following lines:
     ```plaintext
     mnemonic = 'Your mnemonic code'
     link = 'Your infura end point link'
     ```
3. **Modify Solidity Contract:** Make necessary changes to the Solidity file.
4. **Compile and Deploy:**
   - Compile: Run `node compile.js`.
   - Deploy: Run `node deploy.js`.

---

