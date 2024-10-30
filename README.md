# Ethernaut Challenges Solutions

![License](https://img.shields.io/github/license/3bdoredaa2244/ethernaut)
![Stars](https://img.shields.io/github/stars/3bdoredaa2244/ethernaut)
![Issues](https://img.shields.io/github/issues/3bdoredaa2244/ethernaut)

## Overview

This repository contains solutions to the **Ethernaut** challenges, a series of security puzzles by OpenZeppelin designed to teach smart contract security and Ethereum hacking skills. Each solution in this repository demonstrates step-by-step approaches to exploit vulnerabilities and secure smart contracts, providing a practical way to learn Ethereum security principles.

### Key Features
- **Step-by-Step Solutions**: Clear explanations of each challenge and how to solve it.
- **Security Concepts**: Demonstrates vulnerabilities such as reentrancy, integer overflows, and delegate calls.
- **Smart Contract Best Practices**: Highlights secure programming practices to avoid common pitfalls.

## Table of Contents
- [Background](#background)
- [Challenges](#challenges)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background

Ethernaut, created by OpenZeppelin, is a series of Web3-based security puzzles for Ethereum. Each level presents a vulnerable smart contract that users must exploit to gain access or complete an objective. These challenges cover essential concepts in Ethereum security and serve as an effective hands-on learning experience for smart contract developers.

## Challenges

This repository contains solutions for various Ethernaut levels, including:

- **Level 1: Fallback** - Manipulate contract ownership through fallback functions.
- **Level 2: Fallout** - Exploit incorrect constructor naming to gain ownership.
- **Level 3: Coin Flip** - Leverage pseudorandomness to predict outcomes and win.
- **Level 4: Telephone** - Exploit contract calls to bypass restricted functions.
- **Level 5: Token** - Overflow token balances to obtain more tokens.
- **Level 6: Delegation** - Use delegatecall to gain unauthorized access.
- ... and more.

Each level solution includes:
- **Explanation of Vulnerability**: Understanding the underlying issue.
- **Solution Code**: Code to exploit or secure the vulnerability.
- **Walkthrough**: Step-by-step process on how the exploit works.

## Installation

To run the solutions locally, you’ll need:
- **Node.js**: ^14.x or later
- **Hardhat or Foundry**: Solidity development environment

Clone the repository and install dependencies:
```bash
git clone https://github.com/3bdoredaa2244/ethernaut.git
cd ethernaut
npm install
