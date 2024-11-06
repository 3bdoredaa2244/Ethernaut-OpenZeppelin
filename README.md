# Ethernaut OpenZeppelin Solutions

![License](https://img.shields.io/github/license/3bdoredaa2244/Ethernaut-OpenZeppelin)
![Stars](https://img.shields.io/github/stars/3bdoredaa2244/Ethernaut-OpenZeppelin)
![Issues](https://img.shields.io/github/issues/3bdoredaa2244/Ethernaut-OpenZeppelin)

## Overview

This repository contains solutions to the **Ethernaut** challenges by **OpenZeppelin**. Ethernaut is a series of security puzzles that help developers learn about smart contract security through hands-on challenges. The solutions in this repository cover various vulnerabilities and exploits in Ethereum smart contracts, focusing on building a strong understanding of security practices in Web3 development.

### Key Features
- **Security Challenges**: Each solution explores vulnerabilities such as reentrancy, access control issues, and integer overflows.
- **OpenZeppelin Libraries**: The solutions emphasize using OpenZeppelin contracts and tools to build secure smart contracts.
- **Practical Learning**: Aimed at helping developers understand how to exploit and prevent vulnerabilities in real-world smart contracts.

## Table of Contents
- [Background](#background)
- [Challenges](#challenges)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background

Ethernaut is a platform by OpenZeppelin that provides interactive security puzzles based on real-world vulnerabilities. This repository includes solutions to these challenges, with a particular focus on utilizing OpenZeppelin's secure and reusable smart contract libraries. By solving these challenges, developers gain a deeper understanding of security principles such as ownership, reentrancy, and gas optimization.

## Challenges

This repository contains solutions for multiple Ethernaut levels, including:

- **Fallback**: Exploiting fallback functions and reentrancy attacks.
- **Coin Flip**: Winning using predictable pseudorandom numbers.
- **Delegation**: Gaining unauthorized access by exploiting `delegatecall`.
- **Token**: Overflowing balances to mint new tokens.
- **Telephone**: Exploiting an unprotected function to change contract ownership.
- ... and more.

Each solution provides:
- **Explanation of the Vulnerability**: How the issue occurs and its implications.
- **Solution Code**: Code snippets to exploit or fix the vulnerability.
- **Walkthrough**: Step-by-step instructions for understanding the solution.

## Installation

To set up the repository locally, you will need:
- **Node.js**: ^14.x or later
- **Hardhat** or **Foundry**: Ethereum development environment
- **OpenZeppelin Contracts**: Pre-installed through npm.

Clone the repository and install dependencies:
```bash
git clone https://github.com/3bdoredaa2244/Ethernaut-OpenZeppelin.git
cd Ethernaut-OpenZeppelin
npm install
