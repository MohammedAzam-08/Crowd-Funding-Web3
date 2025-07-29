# 💸 Crowd-Funding Web3 dApp

A decentralized crowdfunding platform built using **Next.js**, **TypeScript**, **Thirdweb SDK**, and **Solidity**. This application enables users to create blockchain-backed fundraising campaigns and allows others to contribute using their crypto wallets in a secure, transparent, and immutable way.

> ⚙️ Built with: **Thirdweb**, **React**, **Solidity**, **TailwindCSS**, and **Next.js**

> 🧪 Web3 + Frontend + Smart Contracts in one full-stack dApp

---

## 📌 Key Features

- 🔐 **Wallet Authentication** via MetaMask using `thirdweb`
- 🧾 **Create & View Campaigns** with campaign metadata stored on IPFS
- 💸 **Crypto Contributions** using smart contracts (ERC-20 / native tokens)
- ⛓️ **Smart Contract Integration** using `thirdweb` SDK
- 🌐 **Next.js + Tailwind** responsive frontend
- ⚡ Deployed on Ethereum-compatible networks (Polygon / Sepolia)

---

## 🛠️ Tech Stack

| Frontend        | Blockchain         | Smart Contracts | Styling        | Tooling         |
|-----------------|--------------------|------------------|----------------|------------------|
| Next.js (App Dir) | thirdweb SDK + Wallet | Solidity (via Remix) | Tailwind CSS   | TypeScript, Hardhat |
| React.js        | Ethers.js (indirect) | IPFS (via Thirdweb) | CSS Modules    | Prettier, ESLint  |

---

## 📂 Folder Structure

Crowd-Funding-Web3/
│
├── src/ # Main app logic (Next.js)
│ ├── components/ # Reusable UI components
│ ├── pages/ # Pages (index.tsx, create.tsx, campaign.tsx)
│ └── styles/ # TailwindCSS styles
│
├── crowdfundingcontracts/ # Solidity smart contracts
│ ├── Campaign.sol
│ └── deploy.js / deploy.ts
│
├── public/
├── .env.example
├── next.config.mjs
├── tailwind.config.ts
├── package.json
└── README.md

yaml
Copy
Edit

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MohammedAzam-08/Crowd-Funding-Web3.git
cd Crowd-Funding-Web3
2️⃣ Install Dependencies
bash
Copy
Edit
yarn
🚀 Running the App Locally
🔧 Development Mode
bash
Copy
Edit
yarn dev
Access the app at: http://localhost:3000

🔨 Production Build
bash
Copy
Edit
yarn build
yarn start
🔐 Environment Variables
Create a .env file at the root and add:

env
Copy
Edit
NEXT_PUBLIC_CLIENT_ID=your_thirdweb_project_client_id
To get a client ID, refer to thirdweb docs.

📸 Screenshots (Add Once UI is Finalized)
Connect Wallet	Create Campaign	Campaign Page

💡 How It Works
Users connect their MetaMask wallet via Thirdweb.

They can create campaigns by filling in details.

Campaign data is stored on IPFS (via Thirdweb).

Smart contract handles crypto payments (ETH or tokens).

All contributions are recorded on-chain, ensuring transparency.

🧠 Future Enhancements
 Dashboard for user’s own campaigns

 Email notifications using Webhooks or Notifi

 Multi-token support (USDC, DAI, etc.)

 DAO-based fund approvals

 Optimized gasless transactions using Thirdweb Pay

👨‍💻 Author
Mohammed Azam
Web3 & Full Stack Developer | Solidity Enthusiast
📍 Bengaluru, India
🔗 Portfolio | LinkedIn | GitHub

🙌 Acknowledgements
Thirdweb

Ethereum Dev Community

TailwindCSS

⭐ Feedback & Support
If you find this project helpful:

🌟 Star this repository

🧵 Share feedback via Issues or Pull Requests

🤝 Connect for collaboration

"Empowering decentralized finance through transparent crowdfunding."
