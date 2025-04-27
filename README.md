Buy Adarsh a Chai! ☕
A decentralized tipping application built with Next.js and Ethereum smart contracts, allowing users to send "chai" (tips) to Adarsh with personalized messages. Powered by MetaMask for wallet integration, this app features a modern, glassmorphic UI with smooth animations and responsive design.
✨ Features

Send Tips: Connect MetaMask to send 0.001 ETH with a name and message.
View Memos: Display all on-chain messages (memos) with sender details.
Modern UI: Glassmorphic cards, vibrant gradients, and subtle animations.
Responsive Design: Scales beautifully on desktop and mobile.
Accessible: High-contrast text, focus states, and reduced motion support.
Real-Time Updates: Listens for new memos via smart contract events.

🛠️ Tech Stack

Frontend: Next.js, React, CSS Modules
Blockchain: Ethereum, Ethers.js, MetaMask
Styling: Custom CSS with glassmorphism, Google Fonts (Inter)
Smart Contract: Solidity (deployed at 0x608f745a736Da98650f9A35b086409794F6D628b) You can use remix!
Environment: Replit (https://replit.com/@adarshkr1380/BuyMeACoffee-Solidity-DeFi-Tipping-app)

📋 Prerequisites

Node.js (included in Replit)
MetaMask browser extension
Ethereum testnet funds (e.g., Sepolia ETH)
Replit account

🚀 Setup in Replit

Clone the Project:

Fork or import this project in Replit.
Alternatively, create a new Replit project and copy the files.


Install Dependencies:

Ensure package.json includes:{
  "dependencies": {
    "next": "latest",
    "react": "latest",
    "react-dom": "latest",
    "ethers": "^5.7.2"
  }
}


Run npm install in Replit’s terminal.


File Structure:
├── pages/
│   ├── _app.js              # Global CSS import
│   ├── index.js            # Main app component
├── styles/
│   ├── global.css          # Global styles and variables
│   ├── Home.module.css     # Component-scoped styles
├── utils/
│   ├── BuyMeACoffee.json   # Smart contract ABI
├── package.json
├── README.md


Run the App:

Click the Run button in Replit.
Open the preview in a new tab (Replit’s iframe may restrict MetaMask).



🖥️ Usage

Connect Wallet:

Install MetaMask and connect to a testnet (e.g., Sepolia).
Click "Connect your wallet" to link your account.


Send a Chai:

Enter your name (optional, defaults to "anon").
Add a message (optional, defaults to "Enjoy your chai!").
Click "Send 1 Chai for 0.001ETH" to send 0.001 ETH to the contract.
Confirm the transaction in MetaMask.


View Memos:

After connecting, view all memos (name, message, timestamp) below the form.
New memos appear in real-time via contract events.


Test Responsiveness:

Use Replit’s preview or browser dev tools to test mobile layouts.



🎨 Styling Highlights

Glassmorphism: Semi-transparent cards with blur effects for forms and memos.
Animations: Smooth fadeIn and slideUp transitions for components.
Typography: Clean, scalable fonts using Inter (Google Fonts).
Colors: Vibrant gradient background with blue-green accents.
Responsive: Fluid typography and layouts for all screen sizes.
Accessible: High contrast, focus states, and reduced motion support.

📂 Project Structure

pages/index.js: Main component with wallet connection, form, and memo display.
pages/_app.js: Imports global.css for global styles.
styles/global.css: Defines :root variables and global resets.
styles/Home.module.css: Scoped styles for components (form, memos, etc.).
utils/BuyMeACoffee.json: Smart contract ABI.

🛠️ Troubleshooting

MetaMask Not Connecting:
Open the preview in a new tab (not Replit’s iframe).
Ensure MetaMask is on the correct testnet with sufficient ETH.


Styles Not Applying:
Verify global.css import in _app.js and Home.module.css in index.js.
Clear Replit’s cache (Ctrl+C, then npm run dev).


Contract Errors:
Confirm the contract address (0x608f745a736Da98650f9A35b086409794F6D628b) and ABI match the deployed contract.


Console Errors:
Check Replit’s preview console (Right-click > Inspect > Console) and share errors.



🤝 Contributing

Fork the project in Replit.
Create a branch (git checkout -b feature/your-feature).
Commit changes (git commit -m "Add your feature").
Push to your fork (git push origin feature/your-feature).
Submit a pull request with a clear description.

📜 License
MIT License. See LICENSE for details.
🙌 Credits

Created by: @Adarsh
Built for: Alchemy Road to Web3
Smart Contract: Deployed on Ethereum testnet
Inspiration: Web3 tipping platforms


💡 Have feedback or issues? Create an issue or ping @Adarsh on Replit!
