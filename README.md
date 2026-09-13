<h1 align="center">Ashhad ur Rehman</h1>

<p align="center">
  Smart contract developer. Building on Ethereum, based in Dublin.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ashhad-ur-rehman-a834b219b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:ashhadrehman7@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## About

MSc Computing at Griffith College Dublin, currently finishing a dissertation on decentralised dispute resolution.

I write Solidity and the front ends that talk to it. Most of my time goes into escrow logic, collateral maths, and making contracts behave under conditions I did not plan for. I care more about test coverage than feature count.

**Open to graduate and junior roles** in smart contract, backend, or full stack development. Open to hybrid or remote.

---

## Projects

### ChainWork

Decentralised freelance escrow with on-chain dispute resolution.

Four contracts (`EscrowFactory`, `Escrow`, `ArbitratorPool`, `ReputationRegistry`) handle milestone payments, arbitrator selection and reputation tracking. Clients lock funds, freelancers deliver against milestones, and disputes go to a pool of staked arbitrators rather than a central authority.

**Solidity · Hardhat · ethers.js · React** · 41 passing tests · Live on Sepolia

---

## ChainWork on Sepolia

The system is deployed and has been exercised end to end on testnet.

| | |
|---|---|
| **EscrowFactory** | [`0x0f899f...74ba52`](https://sepolia.etherscan.io/address/0x0f899fCAa4a7E4BD5a95e104231116B4A074ba52) |
| **Escrows created** | 3 |
| **Paths exercised** | Fund, Approve Milestone, Raise Dispute |

Two of the escrows show the full lifecycle: one funded and settled through
milestone approval, one funded and escalated to dispute.

- [Milestone approval flow](https://sepolia.etherscan.io/address/0x9F4d657f7e85BD9cBe1BC20f2464d8AB8a6bfA9D)
- [Dispute flow](https://sepolia.etherscan.io/address/0x772822dd4936D94cC3be3C0a5b8A7bBB74536f52)

[Repository](https://github.com/Ashhad7/ChainWork) 

### lending-vault

Over-collateralised lending and borrowing protocol.

Users deposit collateral and borrow against it, with Chainlink price feeds driving valuation and liquidation thresholds. Built in two phases: a single-sided collateral vault first, then extended into a pooled market with depositors and an interest rate model.

**Solidity · Foundry · Chainlink** · Sepolia

[Repository](https://github.com/Ashhad7/lending-vault)

### NFT Marketplace

Full stack marketplace for minting and trading ERC-721 tokens, with IPFS metadata storage and wallet-based auth. My undergraduate final year project, and where I first learned Solidity.

**Solidity · React · ethers.js · IPFS**


---

## Tools

<p>
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Foundry-FE5000?style=flat-square&logo=rust&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hardhat-FFF100?style=flat-square&logo=hardhat&logoColor=black"/>
  <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white"/>
  <img src="https://img.shields.io/badge/Chainlink-375BD2?style=flat-square&logo=chainlink&logoColor=white"/>
  <img src="https://img.shields.io/badge/IPFS-65C2CB?style=flat-square&logo=ipfs&logoColor=white"/>
</p>

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

---

