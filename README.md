A Discord bot created for learning purposes. Currently, it is not actively running.

Purpose

Beidot was developed to practice Discord.js, slash commands, and modular bot architecture. It is intended as a learning project, rather than a production bot.

Features (Implemented)
🛠 Moderation Commands

/kick @user – Kicks a user from the server.

/prune <number> – Deletes a specified number of messages.

🎉 Fun & User Commands

/ping – Checks the bot’s online status and latency.

/avatar [@user] – Displays your or the mentioned user’s avatar.

Note: All commands are slash commands (/command).

Project Setup

Clone the repository:

git clone https://github.com/username/beidot.git
cd beidot


Install dependencies:

npm install


Create a .env file and add your bot token (optional, for testing):

DISCORD_TOKEN=your_bot_token
CLIENT_ID=your_bot_client_id
GUILD_ID=your_guild_id


Start the bot (if you want to test it locally):

node index.js

Folder Structure Example
beidot/
├─ commands/
│  ├─ fun/
│  │  ├─ ping.js
│  │  └─ avatar.js
│  ├─ moderation/
│  │  ├─ kick.js
│  │  └─ prune.js
│  └─ utility/
│     ├─ server.js
│     └─ user.js
├─ index.js
├─ package.json
└─ .env

Learning Goals

Understand slash commands in Discord.js.

Practice modular command structure.

Learn how to handle users and server interactions programmatically.

License

MIT License © 2026
