<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,1,2&height=220&section=header&text=Miko&fontSize=100&fontColor=FF0000&animation=fadeIn&fontAlignY=42&desc=The%20Only%20Discord%20Bot%20You%20Will%20Ever%20Need&descAlignY=66&descSize=22&descColor=ffffff" width="100%"/>

<br/>

[![Discord Bot](https://img.shields.io/badge/🤖%20Miko%20Bot-Add%20to%20Server-FF0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1477957460575649903&permissions=8&integration_type=0&scope=bot+applications.commands)
[![Support Server](https://img.shields.io/badge/💬%20Support-discord.gg/DUKpjHJtj3-FF0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/DUKpjHJtj3)
[![Version](https://img.shields.io/badge/Version-V7.0-FF0000?style=for-the-badge)](.)
[![discord.js](https://img.shields.io/badge/discord.js-v14-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.js.org)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![License](https://img.shields.io/badge/License-MIT-FF0000?style=for-the-badge)](LICENSE)

<br/>

```
███╗   ███╗██╗██╗  ██╗ ██████╗     ██████╗  ██████╗ ████████╗
████╗ ████║██║██║ ██╔╝██╔═══██╗    ██╔══██╗██╔═══██╗╚══██╔══╝
██╔████╔██║██║█████╔╝ ██║   ██║    ██████╔╝██║   ██║   ██║   
██║╚██╔╝██║██║██╔═██╗ ██║   ██║    ██╔══██╗██║   ██║   ██║   
██║ ╚═╝ ██║██║██║  ██╗╚██████╔╝    ██████╔╝╚██████╔╝   ██║   
╚═╝     ╚═╝╚═╝╚═╝  ╚═╝ ╚═════╝     ╚═════╝  ╚═════╝    ╚═╝   
```

### 🔴 **150+ Commands · Slash + Prefix · Crash-Proof · Games · Moderation · Fun**

<br/>

[![Add to Server](https://img.shields.io/badge/➕%20ADD%20MIKO%20TO%20YOUR%20SERVER-FF0000?style=for-the-badge&logo=discord&logoColor=white&labelColor=8B0000)](https://discord.com/oauth2/authorize?client_id=1477957460575649903&permissions=8&integration_type=0&scope=bot+applications.commands)

</div>

---

## 📋 Table of Contents

- [✨ What is Miko?](#-what-is-miko)
- [🎯 Features at a Glance](#-features-at-a-glance)
- [🚀 Quick Setup](#-quick-setup)
- [📖 All Commands](#-all-commands)
  - [🛡️ Moderation](#️-moderation-commands)
  - [🤖 Auto Responder](#-auto-responder-commands)
  - [📌 Sticky Messages](#-sticky-message-commands)
  - [🔧 Utility](#-utility-commands)
  - [🎉 Fun](#-fun-commands)
  - [🎮 Games (Slash)](#-games-slash-commands)
  - [🕹️ Games (Prefix)](#️-games-prefix-commands)
  - [⚙️ Admin](#️-admin-commands)
  - [👑 Owner Only](#-owner-only-commands)
- [🤖 Bot Preview](#-bot-preview)
- [📁 Project Structure](#-project-structure)
- [🔧 Configuration](#-configuration)
- [🌐 Website / Dashboard API](#-website--dashboard-api)
- [📦 Changelog](#-changelog)
- [❓ FAQ](#-faq)
- [🔗 Links](#-links)

---

## ✨ What is Miko?

**Miko** is a fully-featured, crash-proof multipurpose Discord bot built with **discord.js v14** and **Node.js**. Whether you run a small gaming server or a large community, Miko handles everything — from hardcore moderation to 30+ multiplayer mini-games — all under one roof.

> **Prefix:** `m!` · **Slash Commands:** `/` · **Bot ID:** `1477957460575649903`

<div align="center">

| 🛡️ Moderation | 🎮 30+ Games | 🤖 Auto Responder | 📌 Sticky Messages |
|:---:|:---:|:---:|:---:|
| Full mod toolkit | Multiplayer & solo | Text & embed ARs | Per-channel sticky |
| **22 commands** | **50+ commands** | **10 commands** | **10 commands** |

| 🔧 Utility | 🎉 Fun | 🌐 Website API | 🔴 Crash-Proof |
|:---:|:---:|:---:|:---:|
| Info, polls, weather | Roasts, games, memes | REST dashboard sync | Global error guards |
| **27 commands** | **16 commands** | **Built-in server** | **Never crashes** |

</div>

---

## 🎯 Features at a Glance

```
✅  150+ slash & prefix commands across 9 categories
✅  30+ multiplayer mini-games (Trivia, Connect4, WordRace, BombParty & more)
✅  Full moderation suite — ban, kick, warn, mute, timeout, purge, nuke & more
✅  Auto Responder — text & embed, with custom variables
✅  Sticky Messages — plain text or full embeds per channel
✅  Built-in giveaway system with button entry
✅  Live polls with real-time vote counters
✅  AFK system, snipe, reminders, weather, translate
✅  Per-server custom prefix + log channels
✅  Website/Dashboard API with admin-auth (REST)
✅  Global crash protection — bot NEVER goes down from user errors
✅  Webhook-based action logging
✅  Pure red branding — consistent #FF0000 embed color
```

---

## 🚀 Quick Setup

### Prerequisites

- [Node.js v18+](https://nodejs.org/)
- A Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications)
- (Optional) Firebase Realtime Database for ranking features

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Miko.git
cd Miko

# 2. Install dependencies
npm install

# 3. Create your .env file
cp .env.example .env
```

### Configuration

Edit `.env` with your token:

```env
TOKEN=your_discord_bot_token_here
```

Edit `config.json` to customize the bot:

```json
{
  "defaultPrefix": ["m!"],
  "embedColor": "#FF0000",
  "botName": "Miko",
  "footerText": "Miko | Better than before",
  "developer": "levi_ackerman.09",
  "inviteLink": "https://discord.com/oauth2/authorize?client_id=YOUR_BOT_ID&permissions=8&scope=bot+applications.commands",
  "website": {
    "enabled": true,
    "apiKey": "YOUR_SECRET_KEY",
    "port": 3000
  }
}
```

### Run the bot

```bash
# Production
node index.js

# Or with npm
npm start
```

> 💡 **Tip:** Use [PM2](https://pm2.keymetrics.io/) to keep Miko running 24/7:
> ```bash
> npm install -g pm2
> pm2 start index.js --name "Miko"
> pm2 save
> ```

### Register Slash Commands

Slash commands are registered automatically on bot startup via the slash handler. No manual registration step required.

---

## 📖 All Commands

> `[optional]` = optional argument · `<required>` = required argument · `/` = slash command · `m!` = prefix command

---

### 🛡️ Moderation Commands

> Requires appropriate Discord permissions (e.g. Ban Members, Kick Members, Manage Roles).

| Command | Usage | Description |
|:--------|:------|:------------|
| `/ban` | `/ban <user> [reason]` | Ban a member from the server |
| `/kick` | `/kick <user> [reason]` | Kick a member from the server |
| `/softban` | `/softban <user> [reason]` | Ban then immediately unban (deletes messages) |
| `/massban` | `/massban <id1> <id2> ...` | Ban multiple users by ID at once |
| `/unban` | `/unban <user_id>` | Unban a user by their ID |
| `/mute` | `/mute <user> <minutes>` | Timeout a member (1–1440 min) |
| `/timeout` | `/timeout <user> <duration>` | Timeout with flexible duration (e.g. `10m`, `1h`, `1d`) |
| `/rto` | `/rto <user>` | Remove timeout from a member |
| `/untimeoutall` | `/untimeoutall` | Remove timeout from ALL timed-out members |
| `/warn` | `/warn <user> [reason]` | Issue a warning to a member |
| `/warnings` | `/warnings <user>` | View all warnings for a member |
| `/clearwarns` | `/clearwarns <user>` | Clear all warnings for a member |
| `/purge` | `/purge <amount> [user]` | Delete 1–100 messages (optional: only from a specific user) |
| `/nick` | `/nick <user> [nickname]` | Change or reset a member's nickname |
| `/role` | `/role <user> <role>` | Add or remove a role from a member |
| `/roleall` | `/roleall <role> <add/remove>` | Add or remove a role from ALL members |
| `/lock` | `/lock [channel]` | Lock a channel (deny Send Messages) |
| `/unlock` | `/unlock [channel]` | Unlock a previously locked channel |
| `/slowmode` | `/slowmode <seconds>` | Set slowmode for the current channel |
| `/nuke` | `/nuke [reason]` | Clone and delete the channel — wipes all messages 💥 |
| `/autorole` | `/autorole <add/remove/list> [role]` | Manage roles automatically assigned on member join |
| `/setlogs` | `/setlogs <type> <channel>` | Configure a log channel (mod, messages, members) |
| `/giveaway` | `/giveaway <prize> <duration> <winners>` | Start a giveaway with button entry 🎉 |

**Prefix equivalents:** All moderation commands also work with `m!` prefix (e.g. `m!ban @user reason`).

---

### 🤖 Auto Responder Commands

> Automatically reply to messages matching a trigger. Supports both plain text and full embed responses.

| Command | Description |
|:--------|:------------|
| `/ar add` | Add a text auto-responder (trigger → reply) |
| `/ar remove` | Remove a text auto-responder by trigger |
| `/ar list` | List all text auto-responders in the server |
| `/ar clear` | Remove ALL text auto-responders |
| `/ear add` | Add an embed auto-responder with full embed customization |
| `/ear remove` | Remove an embed auto-responder |
| `/ear list` | List all embed auto-responders |
| `/ear preview` | Preview an embed auto-responder before it goes live |
| `/ear variables` | Show all available variables (e.g. `{user}`, `{server}`, `{membercount}`) |
| `/ear clear` | Remove ALL embed auto-responders |

**Prefix equivalents:** `m!ar add`, `m!ar remove`, `m!ar list`, `m!ear add`, `m!ear remove`, `m!ear list`, `m!ear variables`

---

### 📌 Sticky Message Commands

> Sticky messages are automatically re-sent at the bottom of a channel whenever someone else sends a message.

| Command | Description |
|:--------|:------------|
| `/sticky set` | Set a plain text sticky message in a channel |
| `/sticky embed` | Set a full embed sticky (title, color, image, footer, thumbnail) |
| `/sticky remove` | Remove the sticky from a channel |
| `/sticky list` | List all sticky messages across the server |
| `/sticky info` | View details of the sticky in a specific channel |

**Prefix equivalents:** `m!sticky set`, `m!sticky embed`, `m!sticky remove`, `m!sticky list`, `m!sticky info`

---

### 🔧 Utility Commands

| Command | Usage | Description |
|:--------|:------|:------------|
| `/serverinfo` | `/serverinfo` | Detailed server info — members, roles, channels, boost level |
| `/userinfo` | `/userinfo [user]` | Detailed user profile — joined, roles, badges |
| `/channelinfo` | `/channelinfo [channel]` | Channel type, topic, slowmode, creation date |
| `/roleinfo` | `/roleinfo <role>` | Role color, permissions, member count |
| `/botinfo` | `/botinfo` | Miko's stats — uptime, commands, servers |
| `/botstats` | `/botstats` | Detailed system performance — CPU, memory, ping |
| `/membercount` | `/membercount` | Live member breakdown (online / idle / dnd / offline) |
| `/avatar` | `/avatar [user]` | View a user's full-size avatar |
| `/banner` | `/banner [user]` | View a user's profile banner |
| `/servericon` | `/servericon` | View the server's icon in full resolution |
| `/ping` | `/ping` | Bot latency and API response time |
| `/afk` | `/afk [message]` | Set AFK status — Miko will notify others who ping you |
| `/afklist` | `/afklist` | See all AFK members in the server |
| `/snipe` | `/snipe` | Snipe the last deleted message in the channel |
| `/remind` | `/remind <time> <message>` | Set a reminder — Miko will DM you |
| `/timer` | `/timer <duration>` | Start a live countdown timer in chat |
| `/poll` | `/poll <question> <options>` | Create a reaction poll |
| `/pollrace` | `/pollrace <question>` | Live poll with real-time vote counts updating every few seconds |
| `/translate` | `/translate <language> <text>` | Translate text into any language |
| `/weather` | `/weather <city>` | Current weather for any city worldwide |
| `/urban` | `/urban <term>` | Urban Dictionary definition lookup |
| `/calc` | `/calc <expression>` | Safe math calculator |
| `/color` | `/color <hex>` | Preview a hex color with info |
| `/firstmsg` | `/firstmsg [channel]` | Jump link to the very first message in a channel |
| `/stealemoji` | `/stealemoji <emoji>` | Add an emoji from another server by name |
| `/steal` | `/steal <emoji/url>` | Steal an emoji by pasting it or an image URL |
| `/emojilist` | `/emojilist` | Browse all custom emojis in the server (paginated) |
| `/invites` | `/invites [user]` | Check how many invites a user has |
| `/randommember` | `/randommember [role]` | Pick a random member (optional role filter) |
| `/announce` | `/announce <channel> <message>` | Send a formatted announcement embed to any channel |

---

### 🎉 Fun Commands

| Command | Description |
|:--------|:------------|
| `/8ball` | Ask the magic 8-ball a question |
| `/joke` | Get a random joke |
| `/quote` | Get an inspirational quote |
| `/fact` | Learn a random fun fact |
| `/roast` | Roast someone with 300+ savage one-liners 🔥 |
| `/compliment` | Brighten someone's day with a compliment 💌 |
| `/ship` | Calculate the love percentage between two users 💘 |
| `/rps` | Play Rock Paper Scissors vs Miko |
| `/coinflip` | Flip a coin — heads or tails? 🪙 |
| `/slots` | Pull the slot machine lever 🎰 |
| `/clap` | Convert text to 👏clap👏format |
| `/mock` | SpOnGeBoB mOcK aNy TeXt |
| `/choose` | Can't decide? Let Miko pick from your options |
| `/triviarace` | Multiplayer trivia race — buttons, live timer, scoreboard |
| `/anagram` | Solve a scrambled word puzzle |
| `/emojiriddle` | Guess what the emoji sequence means |

**Extra prefix-only fun:** `m!dare`, `m!truth`, `m!twotruth_dare`, `m!meme`, `m!ascii`, `m!hack`, `m!howgay`, `m!pp`, `m!rate`, `m!reverse`, `m!fortune`, `m!dice`

---

### 🎮 Games (Slash Commands)

> All slash games support Play Again buttons and proper multiplayer handling.

| Command | Type | Description |
|:--------|:----:|:------------|
| `/trivia` | Solo / MP | Quiz — 6 categories, live countdown timer, Play Again 🧠 |
| `/tictactoe` | 1v1 / vs Bot | Tic-Tac-Toe with interactive buttons, Play Again ⭕ |
| `/connect4` | 1v1 / vs Bot | Connect Four — full 6×7 board, Play Again 🔴 |
| `/mathbattle` | Multiplayer | Math race — multiple rounds, live timer, scoreboard 🧮 |
| `/wordhunt` | Multiplayer | Word unscramble race — rounds, live timer, leaderboard 🔤 |
| `/fastquiz` | Multiplayer | Speed quiz — 1st = 3pts, 2nd = 2pts, 3rd = 1pt ⚡ |
| `/wordrace` | Multiplayer | Type the hinted word before anyone else — categories 🏃 |
| `/quickdraw` | Multiplayer | Reaction speed — click DRAW the instant the signal appears 🔫 |
| `/numberbomb` | 1v1 | Pick 1–3 numbers each turn. Whoever hits the bomb loses 💣 |
| `/emojichain` | Multiplayer | Click emojis in the correct sequence together 🎭 |
| `/bombparty` | Multiplayer | Type any word containing the given letters — miss = lose a life 💣 |
| `/deathmatch` | Multiplayer | Trivia deathmatch — wrong answer = lose a life ⚔️ |
| `/mostlikely` | Multiplayer | Vote on who in the server is most likely to... 🤔 |
| `/giveaway` | Event | Full giveaway system with button entry, duration, and winner count 🎉 |

---

### 🕹️ Games (Prefix Commands)

> Classic text-based and interactive games using the `m!` prefix.

| Command | Description |
|:--------|:------------|
| `m!guess` | Guess the number between 1 and 100 |
| `m!hangman` | Classic hangman — guess the word letter by letter |
| `m!scramble` | Unscramble the randomly shuffled word |
| `m!snake` | Play Snake game in Discord 🐍 |
| `m!memory` | Flip and match the hidden emoji pairs |
| `m!fastmath` | Solve math problems as fast as possible |
| `m!wouldyourather` | Vote on a "would you rather" dilemma |
| `m!wordle` | Guess the 5-letter word in 6 attempts (Wordle clone) |
| `m!typerace` | Typing speed race — who finishes the sentence first? |
| `m!trivia` | Classic prefix trivia quiz |
| `m!riddle` | Get a tricky riddle to solve |
| `m!twotruth` | Two truths and a lie — who gets it right? |
| `m!akinator` | Akinator-style character guesser |
| `m!countgame` | Server counting game — count together without mistakes |
| `m!numguess` | Classic number guessing game |
| `m!rps` | Rock Paper Scissors — prefix version |
| `m!coinflip` | Flip a coin |
| `m!quickdraw` | Multiplayer quick draw — react first! |
| `m!wordrace` | Multiplayer word race — type it first! |
| `m!fastquiz` | Multiplayer speed quiz |
| `m!numberbomb` | 1v1 Number Bomb |
| `m!bombparty` | Multiplayer Bomb Party |
| `m!deathmatch` | Trivia Deathmatch |
| `m!mostlikely` | Most Likely To... vote |
| `m!challenge` | 1v1 duel — challenge someone to a series of mini-games ⚔️ |
| `m!geoquiz` | Geography trivia quiz |
| `m!anagram` | Prefix anagram puzzle |
| `m!emojiriddle` | Prefix emoji riddle |
| `m!mathrace` | Prefix math race |
| `m!quiztournament` | Full bracket-style quiz tournament |

---

### ⚙️ Admin Commands

> For server admins and moderators. Manage server-level bot configuration.

| Command | Description |
|:--------|:------------|
| `m!prefix <new_prefix>` | Set a custom prefix for this server |
| `m!setlogs <type> #channel` | Set a log channel (`mod` / `messages` / `members`) |
| `m!autorole <add/remove/list> @role` | Configure roles automatically assigned on member join |
| `m!ar add <trigger> \| <reply>` | Add a text auto-responder |
| `m!ear add` | Add an embed auto-responder via interactive builder |
| `m!sticky set <text>` | Set a plain text sticky message |
| `m!sticky embed <Title \| Body>` | Set an embed sticky message |
| `m!announce #channel <message>` | Send an announcement embed |
| `m!memberlist` | Get a full list of server members |

---

### 👑 Owner-Only Commands

> Restricted to bot owners defined in `config.json`. These commands control the bot globally.

| Command | Description |
|:--------|:------------|
| `m!botstatus <text>` | Change the bot's status/activity |
| `m!broadcast <message>` | Broadcast a message to all servers |
| `m!globalannounce <message>` | Send a global announcement embed |
| `m!servers` | List all servers the bot is in |
| `m!stats` | Global bot statistics |
| `m!leave <server_id>` | Force leave a server |
| `m!leaveserver <server_id>` | Leave a server with confirmation |
| `m!blacklist <user_id>` | Blacklist a user from using the bot |
| `m!trustserver <server_id>` | Trust a server for expanded features |
| `m!maintenance <on/off>` | Toggle maintenance mode |
| `m!reboot` | Restart the bot process |
| `m!eval <code>` | Execute JavaScript (dangerous — owner only) |
| `m!noprefix <user_id>` | Grant a user no-prefix access |
| `m!disablecmd <command>` | Disable a command globally |
| `m!cmdstats` | View command usage statistics |
| `m!finduser <user_id>` | Find a user across all servers |
| `m!userglobal <user_id>` | View global user data |
| `m!invitegen <server_id>` | Generate a server invite |
| `m!dm <user_id> <message>` | DM any user from the bot |
| `m!dma <message>` | DM all server members |

---

## 🤖 Bot Preview

### Embed Color — Pure Red (`#FF0000`)

All Miko embeds use a consistent **pure red (#FF0000)** color theme throughout.

### Help Command — Dropdown Menu

```
┌─────────────────────────────────────────┐
│  🔴  Miko Help                          │
│─────────────────────────────────────────│
│  Welcome! Use the dropdown to browse    │
│  commands by category.                  │
│                                         │
│  🛡️ Moderation — 22 commands            │
│  🤖 Auto Responder — 10 commands        │
│  📌 Sticky Messages — 10 commands       │
│  🔧 Utility — 27 commands               │
│  🎉 Fun — 16 commands                   │
│  🎮 Games (Slash) — 14 commands         │
│  🕹️ Games (Prefix) — 25+ commands       │
│  ⚙️ Admin — 9 commands                  │
│                                         │
│  💡 Both / slash and m! prefix work!    │
│  📌 New: Sticky · AR/EAR · 300+ Roasts  │
│─────────────────────────────────────────│
│  [ 📚 Select a category...          ▼ ] │
└─────────────────────────────────────────┘
```

### Example Game — Connect Four

```
🔴 Connect Four — Round 1

   1️⃣ 2️⃣ 3️⃣ 4️⃣ 5️⃣ 6️⃣ 7️⃣
⬛⬛⬛⬛⬛⬛⬛
⬛⬛⬛⬛⬛⬛⬛
⬛⬛⬛⬛⬛⬛⬛
⬛⬛⬛🔴⬛⬛⬛
⬛⬛🔴🟡⬛⬛⬛
⬛🟡🔴🟡🔴⬛⬛

🔴 Player1's turn — click a column!
[ 1️⃣ ][ 2️⃣ ][ 3️⃣ ][ 4️⃣ ][ 5️⃣ ][ 6️⃣ ][ 7️⃣ ]
```

### Example — Moderation Embed

```
┌─────────────────────────────────────────┐
│  🔨  Member Banned                      │
│─────────────────────────────────────────│
│  User:    BadUser#1234                  │
│  ID:      123456789012345678            │
│  Reason:  Spamming in general           │
│  Mod:     levi_ackerman.09              │
│  Time:    Today at 14:32                │
└─────────────────────────────────────────┘
```

### Example — Trivia Deathmatch

```
⚔️ TRIVIA DEATHMATCH — Round 4/10

❓ What is the capital of Japan?

  [A] Beijing    [B] Seoul
  [C] Tokyo      [D] Bangkok

❤️ Player1: ██████ (3 lives)
❤️ Player2: ████   (2 lives)
💀 Player3: ✗ Eliminated

⏱️ 10 seconds remaining...
```

---

## 📁 Project Structure

```
Miko/
├── 📄 index.js                  — Entry point, crash guards, client setup
├── 📄 config.json               — Bot config (prefix, color, owners, webhooks)
├── 📄 package.json
│
├── 📂 commands/                 — Prefix command modules
│   ├── admin/                   — announce, ar, ear, sticky, etc.
│   ├── fun/                     — 8ball, roast, ship, meme, etc.
│   ├── games/                   — All text-based and multiplayer games
│   ├── moderation/              — ban, kick, warn, mute, purge, etc.
│   ├── owner/                   — eval, broadcast, maintenance, etc.
│   └── utility/                 — avatar, userinfo, weather, poll, etc.
│
├── 📂 slash/                    — Slash command modules (150+ files)
│
├── 📂 handlers/
│   ├── commandHandler.js        — Auto-loads all prefix commands
│   ├── eventHandler.js          — Auto-loads all events
│   └── slashHandler.js          — Auto-loads all slash commands
│
├── 📂 events/
│   ├── client/                  — ready, error
│   ├── guild/                   — guildCreate, guildDelete, memberAdd/Remove
│   ├── interaction/             — interactionCreate (slash handler)
│   └── message/                 — messageCreate (prefix handler)
│
├── 📂 utils/
│   ├── autoDisableButtons.js    — Auto-disables buttons on collector expiry
│   ├── constants.js             — Shared constants
│   ├── embed.js                 — Embed builder helpers (success/error/info)
│   ├── emoji.js                 — Emoji constants
│   ├── functions.js             — Utility functions (getMember, getUser, etc.)
│   ├── logSender.js             — Webhook log sender
│   ├── noRepeat.js              — Anti-repeat utility for games
│   ├── permissions.js           — Permission check helpers
│   ├── safeInteraction.js       — safeReply, safeUpdate, safeEdit
│   ├── saveData.js              — JSON data persistence
│   ├── webhook.js               — Webhook wrapper
│   ├── website.js               — Website API client helper
│   └── websiteServer.js         — Built-in REST server (dashboard sync)
│
└── 📂 data/                     — Auto-created runtime data (JSON files)
    ├── autoroles.json
    ├── prefixes.json
    ├── logchannels.json
    ├── afk.json
    ├── warns.json
    └── stickies.json
```

---

## 🔧 Configuration

`config.json` is the central config file. All fields explained:

```json
{
  "owners": ["YOUR_DISCORD_ID"],
  "allowedUsers": ["TRUSTED_USER_ID"],

  "defaultPrefix": ["m!"],
  "embedColor": "#FF0000",
  "botName": "Miko",
  "footerText": "Miko | Better than before",
  "developer": "your_discord_username",
  "botId": "YOUR_BOT_CLIENT_ID",

  "inviteLink": "https://discord.com/oauth2/authorize?...",

  "status": {
    "text": "m!help | Moderation Bot",
    "type": "dnd"
  },

  "webhooks": {
    "sendLog": "https://discord.com/api/webhooks/...",
    "logs1":   "https://discord.com/api/webhooks/...",
    "logs2":   "https://discord.com/api/webhooks/..."
  },

  "website": {
    "enabled": true,
    "apiKey": "your_secret_api_key",
    "port": 3000
  },

  "logChannels": {
    "modLogs":     "",
    "messageLogs": "",
    "memberLogs":  ""
  }
}
```

### Environment Variables (`.env`)

```env
TOKEN=your_discord_bot_token
```

> ⚠️ **Never commit your `.env` file or your actual `TOKEN` to GitHub.** It is already in `.gitignore`.

---

## 🌐 Website / Dashboard API

Miko includes a **built-in HTTP REST server** that allows external websites or dashboards to interact with the bot in real time.

### Enable

Set in `config.json`:
```json
"website": {
  "enabled": true,
  "apiKey": "your_secret_key",
  "port": 3000
}
```

### Authentication

All requests must include:
```http
X-Bot-Secret: your_secret_key
```

### Available Endpoints

| Method | Endpoint | Description |
|:-------|:---------|:------------|
| `POST` | `/api/...` | Sync data from website to bot |
| `GET`  | `/api/...` | Fetch current bot/server state |

All guild-level endpoints verify that the requesting user is an **Administrator** in the target server before processing.

---

## 📦 Changelog

### 🔴 V7.0 — Current (June 2026)

**New Games**
- Added `/bombparty` + `m!bombparty` — Multiplayer word bomb party
- Added `/deathmatch` + `m!deathmatch` — Trivia deathmatch (lives system)
- Added `/mostlikely` + `m!mostlikely` — Vote who is most likely to...
- Added `/rps` (fixed) + `m!rps` — Rock Paper Scissors
- Added `/coinflip` + `m!coinflip` — Coin flip
- Added `/quickdraw` + `m!quickdraw` — Reaction speed game
- Added `/wordrace` + `m!wordrace` — Type the word first
- Added `/fastquiz` + `m!fastquiz` — Multiplayer speed quiz
- Added `/numberbomb` + `m!numberbomb` — 1v1 number bomb
- Added `m!challenge` — 1v1 multi-game duel

**Bug Fixes**
- Fixed `/rps` crash — `withResponse: true` replaced with `fetchReply: true` across ALL slash commands
- Fixed all button "Interaction Failed" — stale buttons now silently dismissed
- Fixed Play Again buttons — collectors now filter by user and handle expiry properly

**Crash Protection**
- Added global `unhandledRejection` handler in `index.js`
- Added global `uncaughtException` handler
- All interactions wrapped in `try/catch`
- Stale button interactions silently acknowledged in `interactionCreate.js`
- All button collectors properly expire and clean up

**New Files Added**
- `utils/safeInteraction.js` — `safeReply`, `safeUpdate`, `safeEdit`, `disableButtons`
- All new game files under `commands/games/` and `slash/`

---

### V6.x — Previous

- Added Sticky Messages system (text + embed, per channel)
- Added Embed Auto Responder (`/ear` / `m!ear`) with variable support
- Added `/giveaway` with button entry and auto-draw
- Added `/pollrace` with live vote counter updates
- Added 300+ roast lines to `/roast`
- Added `/emojichain`, `/wordhunt`, `/mathbattle` multiplayer games
- Added Website/Dashboard REST API integration
- Added per-server prefix system
- Added AFK system with auto-notify on ping
- Added `/botstats` with system performance metrics

---

### V5.x and Earlier

- Initial release with core moderation suite
- Slash command framework setup
- Prefix command framework setup
- Basic games: Trivia, TicTacToe, Connect4, Hangman, Wordle
- Utility commands: userinfo, serverinfo, weather, translate, poll

---

## ❓ FAQ

**Q: How do I add Miko to my server?**
Click the invite button at the top of this README or use this link:
[Invite Miko](https://discord.com/oauth2/authorize?client_id=1477957460575649903&permissions=8&integration_type=0&scope=bot+applications.commands)

---

**Q: What is the default prefix?**
The default prefix is `m!`. You can change it per server with `m!prefix <new_prefix>`.
Slash commands (`/`) always work regardless of prefix.

---

**Q: Why is the bot offline / not responding?**
- Make sure the bot has the correct permissions in your server.
- Verify your `.env` contains a valid `TOKEN`.
- Check that Node.js 18+ is installed (`node --version`).
- Restart with `node index.js` and check the console for errors.

---

**Q: Slash commands aren't showing up in my server.**
Slash commands register automatically on startup. This can take up to **1 hour** to propagate globally. If they never appear, ensure the bot was invited with `applications.commands` scope.

---

**Q: Can I host Miko for free?**
Yes! You can use [Railway](https://railway.app), [Render](https://render.com), or [Koyeb](https://www.koyeb.com) for free hosting. For better uptime, a cheap VPS (e.g. Hetzner, Contabo) is recommended.

---

**Q: How do I set up log channels?**
Use `/setlogs` or `m!setlogs <type> #channel` where type is `mod`, `messages`, or `members`.
Example: `m!setlogs mod #mod-logs`

---

**Q: The bot crashed / an error appeared.**
Miko V7 has global crash protection — it should never fully crash. If it does, check the console for the error and open an issue or contact the developer on Discord.

---

**Q: Can I self-host and modify Miko?**
Yes, under the MIT License. You're free to self-host and modify. Please don't claim it as your original work if you redistribute it.

---

**Q: How do I become a bot owner / get owner commands?**
Add your Discord user ID to the `owners` array in `config.json`.

---

**Q: Where can I get support?**
Join the official support server: [discord.gg/DUKpjHJtj3](https://discord.gg/DUKpjHJtj3)
Or DM the developer on Discord: `levi_ackerman.09`

---

## 🔗 Links

<div align="center">

| Resource | Link |
|:---:|:---|
| 🤖 **Add Miko to Server** | [Click to Invite](https://discord.com/oauth2/authorize?client_id=1477957460575649903&permissions=8&integration_type=0&scope=bot+applications.commands) |
| 💬 **Support Server** | [discord.gg/DUKpjHJtj3](https://discord.gg/DUKpjHJtj3) |
| 🧑‍💻 **Developer** | `levi_ackerman.09` on Discord |
| 📜 **Privacy Policy** | [MikoDev-Sd.github.io/miko-privacy](https://MikoDev-Sd.github.io/miko-privacy/) |
| 📦 **discord.js Docs** | [discord.js.org](https://discord.js.org) |
| 🌐 **Node.js** | [nodejs.org](https://nodejs.org) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,1,2&height=150&section=footer&text=Miko%20V7%20%F0%9F%94%B4%20—%20Built%20Different&fontSize=28&fontColor=FF0000&animation=fadeIn&fontAlignY=65" width="100%"/>

**Made with 🔴 by [levi_ackerman.09](https://discord.gg/DUKpjHJtj3) · Pakistan 🇵🇰**

*"Better than before — always."*

[![Add Miko](https://img.shields.io/badge/➕%20Add%20Miko%20to%20Your%20Server-FF0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1477957460575649903&permissions=8&integration_type=0&scope=bot+applications.commands)
[![Support](https://img.shields.io/badge/💬%20Join%20Support%20Server-FF0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/DUKpjHJtj3)

![Views](https://komarev.com/ghpvc/?username=MikoDev-Sd&color=FF0000&style=flat-square&label=Repo+Views)

</div>
