# Solana Bonk Bot

Enabled users to quickly and easily buy or sell any token listed on Jupiter without the need to connect a wallet, adjust slippage tolerance, or confirm transactions. Instead, they can purchase tokens by simply sending the Bonkbot Telegram chat the token’s ticker, address, or URL from platforms like pump.fun, Birdeye, DEX Screener, or Meteora. Users can choose to buy tokens using quick buy buttons or in instant mode, where the bot instantly purchases any token’s ticker or contract entered, based on a specific amount of $SOL sent to it.

# 👋 Contact Me

### 
Telegram: https://t.me/earthzeta
###
<div style={{display : flex ; justify-content : space-evenly}}> 
    <a href="https://t.me/earthzeta" target="_blank"><img alt="Telegram"
        src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
    <a href="https://discordapp.com/users/339619501081362432" target="_blank"><img alt="Discord"
        src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
    <a href="mailto:johncriswick25@gmail.com" target="_blank"><img alt="Email"
        src="https://img.shields.io/badge/Gmail-CE5753?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</div>


#### Feel free to contact me if you need any help.

# Overview

## 🌟 Features and buttons in Bonkbot settings to streamline the trading process:

- ⚙️ Minimum position value to display in the portfolio and bot language;
- 🔄 Autobuy for instant purchases with a certain amount of $SOL once users enter a token address;
- 🚀 Customization of the quick buy button's $SOL amount;
- 🚀 Slippage tolerance, MEV protection, and transaction priority settings to speed up buy transactions;
- 🛠️ Sell protection and chart preview setup from DEX Screener;


#  🚀 Usage
### 1. Clone the repository
```
git clone https://github.com/earthzetaorg/solana-bonk-bot.git
cd solana-bonk-bot
```
### 2. Install dependencies
```
npm install
```
### 3. Configure the environment variables

Rename the .env.copy file to .env and set RPC and WSS, main keypair's secret key and other variables.

### 4. Run the bot

```
npm start
```

### 5. Gather the funds from distributed wallets

```
npm run gather
```



