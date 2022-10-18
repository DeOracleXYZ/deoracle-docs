---
description: P2P Oracle Platform & Reputation System
---

# 💡 What we do

#### 1.1 POST REQUESTS (WIDE SCOPE DATA)

Post request to oracles with description, bounty (USDC), min. required reputation (RP) and due date. Requester accepts a valid answer to release the bounty to said oracle's wallet address. Request and answer data is brought on-chain for use in smart contracts.\


#### 1.2 P2P ORACLE ANSWERS

Oracles browse through requests and post verified answers to earn bounties and build reputation. Community votes on the answers (via upvotes, downvotes) which affects the oracle's reputation.\


#### 1.3 CROSS-CHAIN REPUTATION

Verify your identity with Worldcoin and ENS on Polygon. Build up your reputation by posting valid answers. Hop chains to Optimism and your reputation points follow you. deOracle Reputation can be implemented by other on-chain protocols.



## Tech

* deOracle smart contracts are deployed on Polygon Mumbai and Optimism Kovan.
* The cross chain reputation system and cross chain data mirroring is done using Hyperlane.
* Users can verify their identity to earn their first reputation points using Worldcoin (PPPoPP) and ENS.
* deOracle front-end is deployed on Filecoin/IPFS via Spheron.
* Front-end tech stack: Next.js, Tailwind CSS, Ethers.js.
