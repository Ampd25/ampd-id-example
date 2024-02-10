# Example of AMPDid implementation

## ⚙️ Requirements
- Install Node.js LTS https://nodejs.org/en/download

## ✨ Getting started
- Run: npm start
- The example is now available at http://localhost:8080 or http://127.0.0.1:8080

## 🛜 Setting Cardano network
- Open ./public/index.html on row 14 you can change between preprod and mainnet.
- preprod: https://development.d1nka4q7xxcu3u.amplifyapp.com/ampd-id.js
- mainnet: https://main.dxqw1evy7de7x.amplifyapp.com/ampd-id.js

## 🧠 ampdId object
The component exposes an object window.ampdId which has these methods: 
- `await getAssets()` Returns list of assets for connected wallets.
- `getIdToken()` Returns the encoded JWT
-  `getUser()` Returns the decoded info from the JWT
- `isLoggedIn()` Returns a boolean stating if the user is logged in or not.