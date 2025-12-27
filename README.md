# 🚀 CryptoTracker – Cryptocurrency Tracking & Demo Trading Platform

CryptoTracker is a real-time cryptocurrency tracking and demo trading web application built using Angular.  
It allows users to track live crypto prices, analyze market trends using interactive charts, and practice trading with a virtual portfolio — all without real money.

---

## ✨ Features

### 📊 Cryptocurrency Tracking
- Live price updates for 100+ cryptocurrencies  
- Interactive charts for price, volume, and market capitalization  
- Search and filter by coin name or symbol  
- Add coins to Favorites / Watchlist  
- Top Coins Carousel (BTC, ETH, USDT, etc.)

### 📊 Market Details
- Market Capitalization  
- 24h Volume  
- Market Rank  
- Circulating Supply  
- Fully Diluted Valuation  
- Market Sentiment indicators  

---

## 💰 Demo Trading Features

- Virtual Portfolio with default balance (e.g. $10,000)  
- Buy & Sell cryptocurrencies using live market prices  
- Real-time Profit & Loss (PnL) tracking  
- Complete Trade History  
- Real-time price feed for realistic trading simulation  

Note: This is a demo trading application. No real money is involved.

---

## 📦 Technologies Used

Frontend  
- Angular 17  
- TypeScript  
- RxJS  
- SCSS / Tailwind CSS  
- Chart.js / ng2-charts  

APIs & Services  
- CoinGecko API – Live cryptocurrency data  
- Firebase Authentication – Secure login  

Backend (Optional)  
- Node.js  
- Express.js  

---

## 📂 Project Structure

CriptoTraker-main  
│  
├── cripto/              → Angular Frontend  
│   ├── src/  
│   ├── angular.json  
│   └── package.json  
│  
├── node/                → Node.js Backend  
│   ├── index.js  
│   └── package.json  
│  
└── README.md  

---

## ⚙️ Installation & Setup

Backend Setup (Node.js)

1. Navigate to backend folder  
cd node  

2. Install dependencies  
npm install  

3. Start backend server  
node index.js  

Optional (Auto Reload with Nodemon)  
npm install -g nodemon  
nodemon index.js  

---

Frontend Setup (Angular)

1. Navigate to frontend folder  
cd cripto  

2. Install dependencies  
npm install  

3. Run Angular application  
ng serve  

Application will be available at:  
http://localhost:4200  

---

## 🔐 Firebase Configuration

Open node/index.js (or environment file) and add your Firebase credentials:

export const environment = {  
  production: false,  
  firebaseConfig: {  
    apiKey: "YOUR_API_KEY",  
    authDomain: "your-app.firebaseapp.com",  
    projectId: "your-project-id",  
    storageBucket: "your-app.appspot.com",  
    messagingSenderId: "SENDER_ID",  
    appId: "APP_ID"  
  }  
};  

---

## 💡 Tips & Notes

- Make sure both frontend and backend servers are running  
- Internet connection is required for CoinGecko API  
- API rate limits depend on CoinGecko policy  

---

## 🎯 Project Use Case

- Learn cryptocurrency market behavior  
- Practice trading strategies safely  
- Understand real-time API integration  
- Improve Angular, TypeScript, and data-handling skills  

---

## 👨‍💻 Author

Sandip Gavandhare  
Final Year Computer Science Student  

Email: sandipgavandhare3@gmail.com  
LinkedIn: https://www.linkedin.com/in/sandip-gavandhare----7822887596--  

---

## ⚡ Fun Fact

I built this project to combine real-time market data, analytics, and trading logic into a single hands-on learning platform 🚀
