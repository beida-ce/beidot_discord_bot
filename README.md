> A Discord bot created for learning purposes. Currently, it is **not actively running**.

## Purpose
Beidot was developed to practice Discord.js, slash commands, and modular bot architecture.  
It is intended as a **learning project**, not a production bot.

## Learning Goals
- Understand slash commands in Discord.js.
- Practice modular command structure.
- Learn how to handle users and server interactions programmatically.

## Features (Implemented)

### 🛠 Moderation Commands
- `/kick @user` – Kicks a user from the server.
- `/prune <number>` – Deletes a specified number of messages.

### 🎉 Fun & User Commands
- `/ping` – Checks the bot’s online status and latency.
- `/avatar [@user]` – Displays your or the mentioned user’s avatar.

> Note: All commands are **slash commands** (`/command`).

## Project Setup

1. Clone the repository:
```bash
git clone https://github.com/username/beidot.git
cd beidot
```
2. Install dependencies:
```bash
npm install
```
3. Create a .env file and add your bot token (optional, for testing):
```bash
DISCORD_TOKEN=your_bot_token
CLIENT_ID=your_bot_client_id
GUILD_ID=your_guild_id
```
4. Start the bot (if you want to test it locally):
```bash
node bot.js
```


