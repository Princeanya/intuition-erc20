# Intuition ERC20 (MyToken)

A simple ERC20 token deployed on the **Intuition Testnet** as part of the Builder’s Epoch program.  
This project was built using [Remix](https://remix.ethereum.org/) and OpenZeppelin libraries.

---

## 📜 Contract Details
- **Name:** MyToken  
- **Symbol:** MTK  
- **Decimals:** 18  
- **Initial Supply:** 1,000,000 MTK  
- **Deployed Address:** `0x3A1f8Ba195902732b0F43B64aE1c61BDDDC315fc`  
- **Explorer Link:** `https://testnet.explorer.intuition.systems/address/0x3A1f8Ba195902732b0F43B64aE1c61BDDDC315fc`  

---

## 🚀 How to Deploy (Step by Step)
1. Open [Remix IDE](https://remix.ethereum.org/).  
2. Create `contracts/MyToken.sol` and paste the ERC20 code.  
3. Compile with Solidity `^0.8.20`.  
4. Switch MetaMask to **Intuition Testnet** (Chain ID `84532`).  
5. Go to **Deploy & Run Transactions** → Environment: *Injected Provider - MetaMask*.  
6. Enter the constructor argument (e.g., `1000000` for 1 million supply).  
7. Click **Deploy** and confirm in MetaMask.  
8. Copy the deployed address → paste above.  
9. Verify the contract on the Intuition Testnet Explorer.  

---

## 🔧 How to Interact
- `totalSupply()` → Check total token supply.  
- `balanceOf(address)` → See token balance of a wallet.  
- `transfer(to, amount)` → Send MTK to another wallet.  
- `mint(to, amount)` → (Owner only) Mint new tokens.  

---

## 🏆 Builder’s Epoch Submission
This repo is submitted as part of the Intuition Builder’s Epoch program.  
Builders can earn **IQ Points** for deploying contracts, experimenting, and sharing repos with the community.  

---

## 📂 Tech Stack
- Solidity ^0.8.20  
- OpenZeppelin Contracts (ERC20, Ownable)  
- Remix IDE  
- MetaMask (Injected Provider)  

---

## ✨ Next Steps
- Add staking contract (stake MTK → earn MTK).  
- Create a frontend (React + wagmi/viem).  
- Extend with Intuition primitives (Atoms/Triples) for identity-aware DeFi flows.  

---

