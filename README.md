# 🤖 Beidot

Lightweight Discord bot for educational purposes, built with **Discord.js**. 
> **Note:** This is a prototype for learning purposes and is intended to be tested locally, not for production.

## 📝 Overview
A prototype project designed to master Discord.js, focusing on:
* **Slash Commands** implementation.
* **Modular Design** pattern for scalability.
* **Event & API Handling** between Discord and the bot.

## 🎯 Objectives
* Implement modern slash command interactions.
* Build a modular architecture (separate command/event handlers).
* Manage user/server events and integrate with Discord APIs.

---

## ✨ Key Features

### 🛠 Slash Commands (`/command`)

| Category | Command | Description |
| :--- | :--- | :--- |
| **Entertainment** | `/ping` | Check bot latency. |
| **Moderation** | `/kick` | Remove a user from the server. |
| **Moderation** | `/prune` | Delete a specific amount of messages. |
| **Utility** | `/server` | Display server information. |
| **Utility** | `/user` | Display user details. |
| **Utility** | `/avatar` | Show a user's profile image. |

---

## 🚀 Installation

Follow these steps to set up the bot locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/username/beidot.git](https://github.com/username/beidot.git)
   cd beidot
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure Environment: Create a .env file in the root directory and add your credentials:**
   ```bash
   DISCORD_TOKEN=your_token_here
   CLIENT_ID=your_client_id_here
   GUILD_ID=your_guild_id_here
   ```
3. **Configure Environment: Create a .env file in the root directory and add your credentials:**
   ```bash
   DISCORD_TOKEN=your_token_here
   CLIENT_ID=your_client_id_here
   GUILD_ID=your_guild_id_here
   ```
3. **Run the bot:**
   ```bash
    node bot.js
   ```

---

## 🤝 Contributing
Feel free to fork the project, enhance the code, and submit a PR. Please ensure you update the documentation for any new features added.
