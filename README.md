# 🚀 FundVerse – Blockchain Crowdfunding DApp

## 📌 Overview
FundVerse is a blockchain-based crowdfunding platform built on Ethereum.  
It allows users to create fundraising campaigns and donate securely using smart contracts without relying on a central authority.

This project demonstrates the integration of frontend, blockchain, and wallet interaction in a decentralized application (DApp).

---

## 🎯 Features
- Create fundraising campaigns
- Connect wallet using MetaMask
- Transparent fund tracking
- Decentralized architecture (no middleman)
- Blockchain-based transaction handling

---

## 🧱 Tech Stack
- **Frontend:** React.js, Tailwind CSS, Vite  
- **Blockchain:** Ethereum (Sepolia Testnet)  
- **Smart Contracts:** Solidity  
- **Development Framework:** Hardhat  
- **Wallet Integration:** MetaMask  
- **RPC Provider:** Alchemy  

---

## ⚙️ System Architecture
User → Frontend (React) → MetaMask → Ethereum Network (Sepolia) → Smart Contract


---

## 🛠️ Setup Instructions

### 1. Clone the repository

git clone https://github.com/NirajanCoder/fundverse-dapp-assignment.git

cd fundverse-dapp-assignment


### 2. Install dependencies

#### Backend (Smart Contracts)

cd web3
npm install


#### Frontend

cd ../client
npm install


---

### 3. Run the application

npm run dev


Open in browser:

http://localhost:5173


---

## 🔐 Environment Variables

Create a `.env` file inside the `web3` folder:


PRIVATE_KEY=your_wallet_private_key
RPC_URL=your_alchemy_or_infura_url


⚠️ Do NOT upload `.env` to GitHub

---

## 🔧 Modifications Made

The following modifications were made to the original project:

- Configured Sepolia testnet using Alchemy RPC  
- Added environment variables for secure key management  
- Fixed Hardhat configuration issues  
- Resolved frontend build errors (BigInt compatibility issue)  
- Integrated MetaMask wallet connection  
- Customized UI for school fundraising use case  
- Tested campaign creation workflow  

---

## ⚠️ Challenges Faced

- Unable to obtain Sepolia ETH due to faucet restrictions  
- Some faucets require mainnet ETH (not available)  
- Smart contract transactions require gas fees  
- Deployment script missing in original setup  
- Build compatibility issues in frontend  

---

## 🚫 Limitations

- Transactions could not be fully executed due to lack of test ETH  
- Depends on external faucet services for blockchain interaction  
- No live deployment on mainnet  

---

## 🔮 Future Improvements

- Deploy smart contract successfully on testnet  
- Improve UI/UX design  
- Add real-time campaign updates  
- Enable multi-wallet support  
- Integrate IPFS for decentralized storage 


---

## 🔗 GitHub Links

### Original Repository
https://github.com/thekiranmahajan/FundVerse

### My Repository
https://github.com/NirajanCoder/fundverse-dapp-assignment

---

## 📚 Conclusion

This project demonstrates the implementation of a decentralized crowdfunding platform using blockchain technology.  
It highlights key concepts such as smart contracts, wallet integration, and decentralized transaction handling.

Although live transactions were limited due to gas fee requirements, the complete architecture and workflow were successfully implemented and demonstrated.

---

## 👨‍💻 Author
NirajanCoder
