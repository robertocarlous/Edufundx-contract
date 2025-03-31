# Google Scholar: Decentralized Research Funding Platform

## Overview
The **Decentralized Research Funding Platform** leverages blockchain technology to provide transparent, verifiable, and secure research funding. It enables **researchers, funding organizations, and university administrators** to interact in a decentralized ecosystem, ensuring credibility and accountability in academic research funding.

## User Personas
- **Researchers (University Academics)** – Apply for research funding, showcase credentials, and manage research projects.
- **Funding Organizations** – Discover, evaluate, and fund high-potential research projects.
- **University Administrators** – Verify academic credentials and support university-affiliated researchers.

---

## User Flow: Researcher Perspective

### 1. **Account Creation**
- Connect **MetaMask** or **WalletConnect**.
- Verify university email (optional; identity can be verified via wallet address).
- Create a profile with:
  - **Academic credentials**
  - **Research history & publication links**
  - **OCID identifier**
  - **Research interests**

### 2. **Profile Building**
- Upload academic achievements.
- Link published research papers.
- Verify credentials via **university blockchain verification**.
- Set **funding requirements and goals**.

### 3. **Funding Request Process**
- **Create Research Proposal** with:
  - Project description
  - Required funding amount
  - Research methodology
  - Expected outcomes
  - Budget breakdown & timeline
- **Proposal Submission**
  - Smart contract generates a **unique proposal ID**.
  - Proposal goes live on the platform.
  - Initial validation score based on:
    - Academic credentials
    - Previous research impact
    - University reputation
    - Publication history

---

## User Flow: Funding Organization Perspective

### 1. **Discovery**
- Browse researcher profiles.
- Filter by:
  - Research domain
  - University
  - Previous funding success
  - Research impact metrics

### 2. **Evaluation**
- **Proposal Review**
  - Access detailed research proposals.
  - View blockchain-verified credentials.
  - Analyze past research outcomes.
  - Check funding requirements.
- **Due Diligence**
  - Review proposal details.
  - Check researcher’s on-chain reputation.
  - Verify university credentials.
  - Assess research potential.

### 3. **Funding Mechanism**
- **Proposal Selection**
  - Choose research projects.
  - Define funding terms via smart contract.
  - Set **milestone-based funding release**.
- **Fund Allocation**
  - Lock funds in **escrow**.
  - Release funds upon **milestone completion**.
  - Track fund utilization transparently.

---

## Key Platform Features
 **Blockchain-verified academic credentials**
 **Transparent funding process**
 **Milestone-based fund release**
 **Reputation scoring system**
 **Immutable research & funding records**

---

## Technical Components
- **Wallet Authentication** (MetaMask, WalletConnect)
- **Decentralized Identity Verification**
- **Smart Contracts for Fund Management**
- **IPFS for Document Storage**
- **On-chain Reputation Scoring**

### Blockchain Network
- **Educhain Network**
- **Contract Deployment:** The smart contract has been deployed on **Edu Chain Testnet**. You can view it here: [Deployed Contract](https://edu-chain-testnet.blockscout.com/address/0x9a52C40420935536ce787FD8eA162F8e6821B790?tab=contract_abi)

---

## Compliance & Security
- **University Partnership Verification** (Potential collaboration with institutions)
- **Data Privacy Protection**
- **Transparent Fund Tracking**

---

## Getting Started
### Prerequisites
- Install [Node.js](https://nodejs.org/)
- Install [Hardhat](https://hardhat.org/)
- Set up a MetaMask wallet

### Installation
```sh
# Clone the repository
git clone https://github.com/yourusername/decentralized-research-funding.git
cd decentralized-research-funding

# Install dependencies
npm install
```

### Running the Platform
```sh
# Compile smart contracts
npx hardhat compile

# Run local blockchain
npx hardhat node

# Deploy smart contracts
npx hardhat run scripts/deploy.js --network localhost
```

### Running Tests
```sh
npx hardhat test
```

---

## Contribution
We welcome contributions! Please submit a pull request or open an issue to discuss improvements.

---

## License
This project is licensed under the **MIT License**.

---

## Contact
For inquiries or collaborations, reach out at [your.email@example.com](mailto:your.email@example.com).

