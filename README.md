# Insane Nights & Days — Telegram Bot

🎛️ **Insane Nights & Days** is a Web3-powered Telegram bot that enables booking DJs, selling NFT-based event tickets, and building a music community on the TON blockchain.

## 🚀 Features

- 🔗 Connect your TON Wallet via WebApp
- 📅 Create or book a DJ for events
- 🎟️ Buy NFT tickets directly from Telegram
- 🧬 View your profile (score, events, likes, comments, tickets)
- 🥇 Like and comment on DJ profiles
- 🧾 Scan and validate NFT tickets at events
- 🌐 Web3 + community-driven design

## 💻 Technologies Used

- [Node.js](https://nodejs.org/)
- [Telegraf.js](https://telegraf.js.org/) — Telegram Bot Framework
- [TON Wallet](https://ton.org/)
- JSON File-Based Storage (for MVP)
- WebApp integration via Telegram buttons

## 📂 File Structure

- `index_english_final.js`: Full source code of the Telegram bot in English
- `users.json`, `djs.json`, `evenements.json`: Store user data, DJs, and events
- `ton-connect.html`: WebApp for wallet connection

## ⚙️ How to Run

```bash
npm install
node index.js
```

Make sure to define your Telegram Bot Token in a `.env` file:

```env
BOT_TOKEN=your_telegram_bot_token
```

## 🌍 Deployment

For deployment, host the TON connect WebApp on a static host (like Netlify or GitHub Pages), and make sure your Telegram bot has WebApp permissions enabled.

## 🤖 Bot Commands

- `/start` — Launch the bot and show menu
- `🔗 Connect my TON Wallet` — Link wallet
- `📅 Book a DJ` — Open DJ booking WebApp
- `🎶 Events` — View upcoming events
- `🧬 My Profile` — See your user stats
- `🏆 DJ Rankings` — Like, comment, view DJs
- `ℹ️ About` — About the project

## 📜 License

This project is part of a hackathon prototype and is licensed under MIT.

## 💡 Credits

Created by **Insane Corporation**  
Follow our Web3 ecosystem on [insanecorporation.xyz](https://insanecorporation.xyz)
