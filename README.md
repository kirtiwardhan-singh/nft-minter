# 🚀 NFT Minter Bootcamp Template

Welcome to the **Blockchain & Web3 Bootcamp NFT Project**!

This repo contains the **starter template** for the *NFT Attendance Proof Minter dApp* that you'll build during the 2-day BootCamp. You'll write smart contracts, integrate frontend, and finally mint your own NFT on the **Polygon Mumbai Testnet**.

---

## 📚 Bootcamp Agenda (Recap)

**🗓️ Day 1 – Blockchain & Smart Contracts (Rohit Gupta)**
- What is Blockchain & Web3
- Smart Contracts in Solidity
- Deploy your NFT contract to Polygon Mumbai
- Tools: MetaMask, Remix, PolygonScan, OpenSea Testnet

**🗓️ Day 2 – Frontend + Integration (Shubhankar Banerjee)**
- HTML, CSS, JS refresher
- Interacting with blockchain via frontend
- Build & run NFT minter dApp
- Host with Node.js + Express

---

## 🎯 Project Goal

> Mint a personalized NFT as proof of your BootCamp attendance, using your own image and metadata!

---

## 🛠️ Tech Stack

- Solidity + Hardhat
- Node.js + Express.js
- HTML, CSS, JavaScript
- Ethers.js
- IPFS (via Pinata or NFT.Storage)
- Polygon Mumbai Testnet

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/ShubhankarBanerjee87/BlockchainBootcamp2025.git
cd BlockchainBootcamp2025
```

### 2. Install Dependencies

```bash
npm install 
```

### 3. Configure Environment

```bash
PRIVATE_KEY=your_wallet_private_key
RPC_URL=https://polygon-mumbai.infura.io/v3/your_project_id
```

🔐 Important: Do not share your .env file publicly or commit it to version control.

### 4. Compile the Contract

```bash
npx hardhat compile
```

### 5. Deploy

```bash
npx hardhat run scripts/deploy.js --network mumbai
```

---

## 🧠 Your Tasks

### 📄 Smart Contract (Solidity)

- [ ] Complete the `mintNFT()` function in `contracts/NFTAttendance.sol`
- [ ] Deploy the contract to **Polygon Mumbai Testnet**

### 🌐 Frontend (HTML/JS)

- [ ] Connect MetaMask to the frontend
- [ ] Upload your NFT image to IPFS
- [ ] Generate metadata and upload it to IPFS
- [ ] Call `mintNFT()` using **Ethers.js** from the frontend

---

## 🌐 Tools & Links

- 🔧 [Remix IDE](https://remix.ethereum.org/)
- 🦊 [MetaMask](https://metamask.io/)
- 🔎 [PolygonScan (Mumbai)](https://mumbai.polygonscan.com/)
- 🖼️ [OpenSea Testnet](https://testnets.opensea.io/)
- 📤 [Pinata](https://www.pinata.cloud/)
- 📦 [NFT.Storage](https://nft.storage/)

---

## 📸 Sample Output

> Once minted successfully, your NFT will appear on OpenSea Testnet like this:  
> `https://testnets.opensea.io/assets/mumbai/<your_contract_address>/<token_id>`

---

## 👨‍🎓 Completion Badge

Each NFT you mint is proof of:

✅ Your participation in this BootCamp  
✅ Your ability to write smart contracts  
✅ Your confidence with full-stack Web3 development 🚀

---

## ✨ Credits

**Organized by:** 🎯 SHARP Foundation

**BootCamp Trainers:**

- 👨‍🏫 **Rohit Gupta** – Smart Contracts  
- 👨‍💻 **Shubhankar Banerjee** – Frontend + Integration

---

> 🚀 Happy Building, and welcome to Web3!
