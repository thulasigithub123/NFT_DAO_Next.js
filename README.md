# NFT_DAO_Next.js
Build an NFT-powered fully on-chain DAO to invest in NFT collections as a group and Next.js

# CryptoDevs DAO: NFT-Powered On-Chain DAO

Welcome to CryptoDevs DAO, a decentralized autonomous organization (DAO) built on the Ethereum blockchain. This project allows holders of the CryptoDevs NFT collection to collectively make decisions on how to use the DAO treasury, which is funded by the sale of CryptoDevs NFTs. Members can propose, vote, and execute actions such as purchasing NFTs from a simulated on-chain marketplace.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Setting up Hardhat](#setting-up-hardhat)
  - [Deploying Contracts](#deploying-contracts)
  - [Frontend Development](#frontend-development)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

CryptoDevs DAO is a fully on-chain DAO that leverages NFT ownership for membership and voting power. The project consists of three main components:

1. **NFT Contract (CryptoDevsNFT.sol):** This contract represents the CryptoDevs NFT collection. NFT holders can mint new NFTs, which serve as membership tokens for the DAO.

2. **Fake NFT Marketplace (FakeNFTMarketplace.sol):** Simulated on-chain marketplace where DAO funds can be used to purchase NFTs. This contract helps demonstrate the DAO's ability to speculate on NFT prices.

3. **DAO Contract (CryptoDevsDAO.sol):** The core DAO contract where members can create proposals to use the DAO treasury, vote on proposals, and execute passed proposals. It interacts with the NFT contract and the fake NFT marketplace.

## Project Structure

The project is organized into two main directories:

1. **Hardhat:** Contains the smart contracts written in Solidity, the deployment script (`deploy.js`), and configuration files for Hardhat.

2. **Frontend:** A simple Next.js web application that provides a user interface for interacting with the DAO. It includes wallet connection, proposal creation, and voting features.

## Tech Stack

The CryptoDevs DAO project uses the following technologies and tools:

- **Solidity:** The programming language for writing smart contracts on the Ethereum blockchain.

- **Hardhat:** A development environment for Ethereum that makes it easy to compile, test, and deploy smart contracts.

- **OpenZeppelin Contracts:** A library for secure and community-vetted smart contract code on Ethereum.

- **Next.js:** A React framework for building the frontend application.

- **Web3.js:** A JavaScript library for interacting with the Ethereum blockchain.

- **Metamask:** A cryptocurrency wallet and gateway to blockchain apps.
 
