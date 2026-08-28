<div align="center">
  <img src="https://raw.githubusercontent.com/core-dev-group/core-dev-group-bot/main/web/public/logo.png" alt="Core Dev Group Bot Logo" width="150" height="150" />
  <h1>Core Dev Group Bot</h1>
  <p><em>A next-generation AI-powered Discord Bot & Web Dashboard built to manage, moderate, and scale developer communities.</em></p>

  [![Discord.js](https://img.shields.io/badge/discord.js-v14-blue.svg?logo=discord)](https://discord.js.org)
  [![Node.js](https://img.shields.io/badge/Node.js-v18+-green.svg?logo=node.js)](https://nodejs.org)
  [![React](https://img.shields.io/badge/React-18-blue.svg?logo=react)](https://reactjs.org)
  [![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-brightgreen.svg?logo=mongodb)](https://mongodb.com)
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
</div>

<br />

## 🌟 Features

Core Dev Group Bot is packed with features designed specifically for developers, community managers, and tech enthusiasts. 

### 🤖 AI Integration (Powered by Gemini)
- **Conversational AI**: Tag the bot in designated channels to ask coding questions or chat normally. The AI remembers up to 10 previous messages for context!
- **AI Code Review**: Drop a code snippet inside the `#tech-talks` channel and get instant, constructive feedback and best-practice suggestions from the AI.
- **Smart GitHub Summaries**: Converts complex GitHub commit logs and PRs into easy-to-read, conversational updates.

### 🛡️ Smart Auto-Moderator
- **Toxicity Filter**: AI-powered blocklist that automatically scans and removes toxic messages.
- **Configurable Punishments**: Automatically warns, timeouts, kicks, or bans members who violate the rules (configurable via the Dashboard).
- **Immunity System**: Set roles or channels to be immune from AutoMod actions.

### 🌐 Full-Stack Web Dashboard
- **Module Toggles**: Turn specific bot features (Leveling, AutoMod, Kanban, Code Review) ON or OFF dynamically.
- **Customizable Messages**: Edit Welcome, Level-Up, and AutoMod warning messages directly from the web interface.
- **Live Statistics**: Displays real-time metrics including total members, bot uptime, and total commands served.
- **Discord OAuth2**: Secure login using Discord accounts.

### 🚀 Developer Tools & Kanban
- **Tech Lookups**: Instantly search for NPM packages (`!npm`), GitHub repositories (`!github`), and MDN documentation (`!mdn`) directly from Discord.
- **In-Discord Kanban Board**: Create, list, complete, and delete tasks (`!task add`, `!task list`) to manage team workflows natively inside Discord.

### 🎮 Leveling & Profiles
- **Interactive Gamification**: Users gain XP by chatting. Generate aesthetic rank cards using `!rank` (Powered by Canvacord v6).
- **Custom Profiles**: Link your GitHub (`!setgithub`) and write a bio (`!setbio`) to showcase your developer portfolio via `!profile`.

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js, Discord.js v14
- **Database**: MongoDB (Mongoose)
- **Frontend**: React, Vite, TailwindCSS (Vanilla CSS implementation)
- **AI Integration**: Google Gen AI SDK (Gemini)
- **Image Generation**: Canvacord v6

---

## 📜 Documentation

Full documentation on how to configure the bot, setup specific channels, and manage the Kanban board is available directly on the [Web Dashboard](https://web-core-dev-group-bot.vercel.app/#docs).

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License
This project is licensed under the MIT License.
