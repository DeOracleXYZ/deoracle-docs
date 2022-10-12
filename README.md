---
description: Welcome to the deOracle.xyz documentation!
---

# 👋 Welcome to deOracle.xyz!

## Overview

deOracle.xyz is a decentralised P2P oracle platform with a cross-chain reputation system for digital identities. Our goal is to bring reliable real-world data of any kind on-chain.

deOracle is useful for Smart Contract and dApp developers who are looking for wide scope data feeds not supported by mainstream oracles. Use cases: prediction markets, betting, lotteries, raffles, etc.\


#### 1.1 POST REQUESTS (WIDE SCOPE DATA)

Post request to oracles with description, bounty (USDC), min. required reputation (RP) and due date. Requester accepts a valid answer to release the bounty to said oracle's wallet address. Request and answer data is brought on-chain for use in smart contracts.\


#### 1.2 P2P ORACLE ANSWERS

Oracles browse through requests and post verified answers to earn bounties and build reputation. Community votes on the answers (via upvotes, downvotes) which affects the oracle's reputation.\


#### 1.3 CROSS-CHAIN REPUTATION

Verify your identity with Worldcoin and ENS on Polygon. Build up your reputation by posting valid answers. Hop chains to Optimism and your reputation points follow you. deOracle Reputation can be implemented by other on-chain protocols.

## 1. Roadmap

### a. Phase 1

* Stability improvements and bug fixes
* Error handling with UI messages
* Utility token & staking
* Launch on Polygon and Optimism Mainnet

### b. Phase 2

* Decentralised governance via deOracle DAO
* Distribute soul-bound NFTs for on-chain identity
* Implement type formatted answers (number, boolean, multiple choice, etc.)
* deOracle Dev API
* Launch on Ethereum and Arbitrum Mainnet

## 2. Tech

* deOracle smart contracts are deployed on Polygon Mumbai and Optimism Kovan.
* The cross chain reputation system and cross chain data mirroring is done using Hyperlane.
* Users can verify their identity to earn their first reputation points using Worldcoin (PPPoPP) and ENS.
* deOracle front-end is deployed on Filecoin/IPFS via Spheron.
* Front-end tech stack: Next.js, Tailwind CSS, Ethers.js.

## 4. Features:

### 4.1 Connect

Web 3 Login with Metamask on Polygon Mumbai and Optimism Kovan. Mainnet coming soon.

(...)

### 4.2 Verification

Verify your identity with Worldcoin and ENS on Polygon.

SBT (Soul Bound Token)

(...)

### 4.3. Inquirer

As an inquirer, you can: post a request for oracles to answer.

* Post a request
* Submit a bounty with the request
* See answers
* Vote on answers (upvotes, downvotes)
* Accept an answer for your request
* See results of other requests

(...)

### 4.4. Request

Request details:

* Free / Bounty
* Set min. reputation for oracles
* Answer: yes / no
* Disputed: yes / no
  * If yes (optional):
  * Requester creates a dispute with a stake
  * Other oracle with higher reputation provides answer
  * If dispute fails, requester loses stake
* Set question string (expand types of requests)
* Event date
* Expiry date

(...)

### 4.5. Oracle

As an oracle:

* See requests
* Respond to requests
* Earn reputation
* Lose reputation
* Earn bounty

(...)

### 4.6. Reputation

Reputation formula for oracle & requester:

* Number of upvotes vs downvotes
* Total number of votes
* Account age
* Activity vs balance ratio
* Number of disputes

Reputation Points (RP):

* Registration: 0 RP
* Verification:
  * Worldcoin: +100 RP
  * ENS: +50 RP
  * Lens: +50 RP
* Create Request: +5 RP
* Answer request:
  * Accepted Answer:
    * \+15 RP for answer owner
    * \+5 RP for request owner
  * Faulty Answer: -20 RP - ???
  * Create Answer: 5 RP
  * Community Upvotes:
    * \+3 RP per Upvote
    *
      * 3 RP per Downvote
* Vote:
  * \+1 RP per vote for voters

(...)
