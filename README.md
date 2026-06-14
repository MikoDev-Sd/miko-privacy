<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0000,50:8B0000,100:FF0000&height=220&section=header&text=Miko%20%F0%9F%8C%B8&fontSize=90&fontColor=fff&animation=twinkling&fontAlignY=36&desc=The%20Ultimate%20Multipurpose%20Discord%20Bot&descAlignY=58&descSize=22&descColor=ffaaaa" width="100%"/>

</div>

<div align="center">

```
███╗   ███╗██╗██╗  ██╗ ██████╗     ██╗   ██╗███████╗
████╗ ████║██║██║ ██╔╝██╔═══██╗    ██║   ██║╚════██║
██╔████╔██║██║█████╔╝ ██║   ██║    ██║   ██║    ██╔╝
██║╚██╔╝██║██║██╔═██╗ ██║   ██║    ╚██╗ ██╔╝   ██╔╝
██║ ╚═╝ ██║██║██║  ██╗╚██████╔╝     ╚████╔╝    ██║
╚═╝     ╚═╝╚═╝╚═╝  ╚═╝ ╚═════╝       ╚═══╝     ╚═╝
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
       P R I V A C Y   P O L I C Y  —  O F F I C I A L
```

*Transparency · Security · Trust · Power · Reliability*

</div>

<div align="center">

[![Add Miko](https://img.shields.io/badge/➕%20Add%20Miko%20to%20Your%20Server-CC0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1477957460575649903&scope=bot%20applications.commands&permissions=0)
[![Support Server](https://img.shields.io/badge/💬%20Support%20Server-8B0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/DUKpjHJtj3)
[![Policy Live](https://img.shields.io/badge/📜%20Policy%20Page-Live-FF3333?style=for-the-badge&logo=github&logoColor=white)](https://MikoDev-Sd.github.io/miko-privacy/)

</div>

<div align="center">

[![discord.js](https://img.shields.io/badge/discord.js-v14.14.1-CC0000?style=flat-square&logo=discord&logoColor=white)](https://discord.js.org)
[![Node.js](https://img.shields.io/badge/Node.js-18+-8B0000?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![License](https://img.shields.io/badge/License-MIT-FF0000?style=flat-square)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Updated-June%202026-CC0000?style=flat-square)](.)
[![Commands](https://img.shields.io/badge/Commands-146+%20Prefix%20%7C%2088+%20Slash-8B0000?style=flat-square&logo=discord&logoColor=white)](.)
[![Developer](https://img.shields.io/badge/Dev-levi__ackerman.09-FF0000?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/DUKpjHJtj3)
[![Status](https://img.shields.io/badge/Status-Online%20%F0%9F%9F%A2-CC0000?style=flat-square)](.)
[![Hosting](https://img.shields.io/badge/Host-Orihost%20%2F%20Pterodactyl-8B0000?style=flat-square)](.)

</div>

---

## 📖 Table of Contents

| # | Section |
|---|---------|
| 01 | [🤖 About Miko Bot](#-about-miko-bot) |
| 02 | [✨ Features & Preview](#-features--preview) |
| 03 | [📋 Full Command List](#-full-command-list) |
| 04 | [📦 What Data We Collect](#-what-data-we-collect) |
| 05 | [⚙️ How We Use Your Data](#%EF%B8%8F-how-we-use-your-data) |
| 06 | [🔒 Data Storage & Security](#-data-storage--security) |
| 07 | [🚫 Data Sharing](#-data-sharing) |
| 08 | [🗑️ Data Deletion](#%EF%B8%8F-data-deletion) |
| 09 | [👶 Users Under 13](#-users-under-13) |
| 10 | [⚖️ Your Rights](#%EF%B8%8F-your-rights) |
| 11 | [📜 Changelog](#-changelog) |
| 12 | [❓ FAQ](#-faq) |
| 13 | [🔄 Policy Updates](#-policy-updates) |
| 14 | [📬 Contact](#-contact) |
| 15 | [🌐 Live Policy Page](#-live-policy-page) |

---

## 🤖 About Miko Bot

<div align="center">

> **Miko** is a powerful, crash-resistant, feature-packed multipurpose Discord bot built from the ground up with `discord.js v14`. Whether you need serious moderation tools, engaging multiplayer games, smart utility commands, or fun interactions — Miko handles it all from one bot, with zero compromise on stability or performance.

</div>

### 🏗️ Architecture & Tech Stack

```
┌─────────────────────────────────────────────────────────┐
│                    MIKO V7 — CORE                       │
├──────────────┬──────────────────┬───────────────────────┤
│  Runtime     │  Framework       │  Hosting              │
│  Node.js 18+ │  discord.js v14  │  Railway / Pterodactyl│
├──────────────┼──────────────────┼───────────────────────┤
│  Database    │  API             │  Crash Guard          │
│  JSON + Firebase│ Express/REST  │  Global Uncaught      │
│  Realtime DB │  Webhook System  │  Exception Handler    │
└──────────────┴──────────────────┴───────────────────────┘
```

### 🛡️ Crash-Resistant Design

Miko is engineered to **never go down** from user-triggered errors. Every unhandled promise rejection and uncaught exception is caught at the process level — the bot keeps running no matter what.

```js
// Miko's Global Crash Guard
process.on("unhandledRejection", (reason) => {
    console.error("[UnhandledRejection] Caught:", reason?.message);
    // Bot NEVER exits — always stays online ✅
});
process.on("uncaughtException", (err) => {
    console.error("[UncaughtException] Caught:", err.message);
    // Bot NEVER exits — always stays online ✅
});
```

### 📊 At a Glance

<div align="center">

| Stat | Value |
|:----:|:-----:|
| 🎮 **Total Prefix Commands** | `146` |
| ⚡ **Total Slash Commands** | `88+` |
| 🗂️ **Command Categories** | `6` |
| 🤖 **Bot ID** | `1477957460575649903` |
| 🏷️ **Default Prefix** | `m!` |
| 📦 **Framework** | `discord.js v14.14.1` |
| 🟢 **Node.js Requirement** | `≥ 18.0.0` |
| 🛡️ **Intents Used** | `Guilds, Messages, Members, Voice, Moderation, Invites` |
| 💾 **Database** | `JSON (local) + Firebase Realtime DB` |
| 🌐 **Dashboard** | `Express API + Webhook System` |

</div>

---

## ✨ Features & Preview

### 🎯 What Makes Miko Special

```
╔══════════════════════════════════════════════════════════════╗
║  ✅  146 prefix commands + 88 slash commands                 ║
║  ✅  Never crashes — global exception handler built in       ║
║  ✅  Per-server configuration (prefix, logs, autorole)       ║
║  ✅  Firebase-backed ranking & tier system via /rp           ║
║  ✅  Full moderation suite (ban, kick, mute, timeout, purge) ║
║  ✅  34 multiplayer & solo games in one bot                  ║
║  ✅  Invite tracker with cache system                        ║
║  ✅  Sticky messages, AFK system, Snipe command              ║
║  ✅  Auto-responder & embed autoresponder system             ║
║  ✅  Giveaway system with timer-based draws                  ║
║  ✅  Weather, Translate, Urban Dictionary & more             ║
║  ✅  Mass DM system with server-admin authorization          ║
║  ✅  Webhook-based join/leave & log delivery                 ║
╚══════════════════════════════════════════════════════════════╝
```

### 🖼️ Bot Preview

> **Note:** Screenshots taken from live Miko sessions. Bot appearance may vary based on server configuration.

```
┌─────────────────────────────────────────────────────────────────┐
│  🤖 Miko#0000                                          [BOT]    │
│ ─────────────────────────────────────────────────────────────── │
│  📌 m!botinfo                                                   │
│ ─────────────────────────────────────────────────────────────── │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │  ℹ️  Miko                                               │   │
│  │  🤖 Bot Tag    │  Miko#0000    │ 🆔 Bot ID   │ [ID]   │   │
│  │  📅 Created    │  [Date]       │ ⏱️ Uptime   │ 12h    │   │
│  │  🏠 Servers    │  Active       │ 👥 Users    │ Many   │   │
│  │  💬 Commands   │  146          │ 🧠 Memory   │ ~MB    │   │
│  │  📦 Discord.js │  v14.14.1     │ 🟢 Node.js  │ v18+   │   │
│  └─────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────┐
│  🎮 /tictactoe  @user                                           │
│  ──────────────────────────────────────────────────────────     │
│  ┌─── TicTacToe: Player1 vs Player2 ──────────────────────┐   │
│  │   ⬜ │ ⬜ │ ⬜                                          │   │
│  │   ⬜ │ ⬜ │ ⬜     🔴 Player1's turn!                  │   │
│  │   ⬜ │ ⬜ │ ⬜                                          │   │
│  │  [1][2][3]  [4][5][6]  [7][8][9]                       │   │
│  └─────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────┐
│  🛡️ m!warn @user spamming                                       │
│  ──────────────────────────────────────────────────────────     │
│  ┌─── ⚠️ Warning Issued ──────────────────────────────────┐   │
│  │  User    │ @user                                        │   │
│  │  Reason  │ spamming                                     │   │
│  │  Warns   │ 1/3                                          │   │
│  │  Mod     │ @moderator                                   │   │
│  └─────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📋 Full Command List

> **Prefix:** `m!` &nbsp;|&nbsp; **Slash:** `/command` &nbsp;|&nbsp; **Total:** 146 prefix + 88 slash

### 👑 Admin Commands `(22)`

<details>
<summary>Click to expand Admin Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!announce` | Send a formatted announcement to a channel |
| `m!ar` | Manage auto-responder rules for the server |
| `m!blacklist` | Blacklist a user from using the bot |
| `m!dm` | Send a direct message to a user |
| `m!dma` | DM all members with a message (requires auth) |
| `m!ear` | Edit an existing auto-responder entry |
| `m!edit` | Edit a message sent by the bot |
| `m!em` | Send a custom embed message |
| `m!embededit` | Edit an existing embed sent by the bot |
| `m!invite` | Generate a bot invite link |
| `m!leave` | Make the bot leave a specified server |
| `m!memberlist` | List all members in the server |
| `m!sdma` | Scheduled DM to all members |
| `m!sdmaa` | Advanced scheduled mass DM |
| `m!send` | Send a plain message to any channel |
| `m!servernuke` | Emergency server nuke (owner protected) |
| `m!servers` | List all servers the bot is in |
| `m!setreportchannel` | Set the report receiving channel |
| `m!stats` | View bot usage statistics |
| `m!stealemoji` | Steal an emoji from another server |
| `m!sticky` | Set a sticky message in a channel |
| `m!unsetreportchannel` | Remove the report channel config |

</details>

### 🎉 Fun Commands `(23)`

<details>
<summary>Click to expand Fun Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!8ball` | Ask the magic 8-ball a question |
| `m!ascii` | Convert text to ASCII art |
| `m!choose` | Make Miko choose between options |
| `m!clap` | 👏 Add 👏 claps 👏 between 👏 words |
| `m!compliment` | Send a sweet compliment to a user |
| `m!dare` | Get a random dare challenge |
| `m!dice` | Roll dice with custom sides |
| `m!fact` | Get a random interesting fact |
| `m!fortune` | Read your fortune cookie |
| `m!hack` | Fake-hack a user (just for fun) |
| `m!howgay` | Check how gay someone is (fun %) |
| `m!joke` | Get a random joke |
| `m!meme` | Fetch a random meme |
| `m!mock` | MoCk TeXt LiKe ThIs |
| `m!pp` | Totally accurate pp size checker |
| `m!quote` | Get a random inspirational quote |
| `m!rate` | Rate anything out of 10 |
| `m!reverse` | Reverse any text |
| `m!roast` | Roast a user with savage lines |
| `m!ship` | Ship two users and get a % |
| `m!slots` | Pull the slot machine 🎰 |
| `m!truth` | Get a random truth question |
| `m!twotruth_dare` | Two Truths and a Dare game |

</details>

### 🎮 Games Commands `(34)`

<details>
<summary>Click to expand Games Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!akinator` | AI-powered Akinator game |
| `m!anagram` | Unscramble the anagram |
| `m!bombparty` | Multiplayer word bomb party |
| `m!challenge` | Challenge someone to a duel |
| `m!coinflip` | Flip a coin |
| `m!connect4` | Play Connect 4 with someone |
| `m!countgame` | Server counting game |
| `m!deathmatch` | Text-based PvP deathmatch |
| `m!emojiriddle` | Guess the emoji riddle |
| `m!fastmath` | Speed math challenge |
| `m!fastquiz` | Lightning fast quiz round |
| `m!geoquiz` | Geography quiz |
| `m!guess` | Number guessing game |
| `m!hangman` | Classic hangman |
| `m!math` | Math battle challenge |
| `m!mathrace` | First to solve the math wins |
| `m!memory` | Card memory matching game |
| `m!mostlikely` | Vote who is most likely to... |
| `m!numberbomb` | Don't say the bomb number! |
| `m!numguess` | Guess the random number |
| `m!quickdraw` | Western quickdraw showdown |
| `m!quiztournament` | Full quiz tournament bracket |
| `m!riddle` | Solve a riddle |
| `m!rps` | Rock, Paper, Scissors |
| `m!scramble` | Unscramble a word |
| `m!snake` | Play Snake in Discord |
| `m!tictactoe` | TicTacToe vs someone |
| `m!trivia` | Trivia question round |
| `m!triviarace` | Competitive trivia race |
| `m!twotruth` | Two truths one lie |
| `m!typerace` | Typing speed race |
| `m!wordle` | Wordle in Discord |
| `m!wordrace` | Fastest to type the word |
| `m!wouldyourather` | Would you rather...? |

</details>

### 🛡️ Moderation Commands `(22)`

<details>
<summary>Click to expand Moderation Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!autorole` | Set a role given on member join |
| `m!ban` | Ban a user from the server |
| `m!clearwarns` | Clear all warnings for a user |
| `m!deafen` | Server-deafen a member in VC |
| `m!kick` | Kick a member from the server |
| `m!lock` | Lock a channel from sending messages |
| `m!mute` | Mute a member (role-based) |
| `m!nick` | Change a member's nickname |
| `m!purge` | Bulk-delete messages in a channel |
| `m!removelogs` | Remove the log channel config |
| `m!role` | Add or remove a role from a member |
| `m!rto` | Remove timeout from a member |
| `m!setlogs` | Set the server mod-log channel |
| `m!slowmode` | Set channel slowmode delay |
| `m!softban` | Ban and immediately unban to purge messages |
| `m!timeout` | Timeout a member for a duration |
| `m!unban` | Unban a previously banned user |
| `m!unlock` | Unlock a previously locked channel |
| `m!unmute` | Unmute a muted member |
| `m!untimeoutall` | Remove timeout from all members |
| `m!warn` | Issue a warning to a member |
| `m!warnings` | View all warnings for a user |

</details>

### 🔑 Owner Commands `(20)`

<details>
<summary>Click to expand Owner Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!botstatus` | Change the bot's presence/status |
| `m!broadcast` | Broadcast a message to all servers |
| `m!cmdstats` | View per-command usage statistics |
| `m!disablecmd` | Disable a command globally |
| `m!eval` | Execute arbitrary JavaScript (owner only) |
| `m!finduser` | Find a user across all servers |
| `m!globalannounce` | Announce to every server |
| `m!globalprefix` | Change the global default prefix |
| `m!invitegen` | Generate a custom bot invite |
| `m!leaveserver` | Force the bot to leave a server |
| `m!maintenance` | Toggle maintenance mode |
| `m!noprefix` | Toggle no-prefix mode for a user |
| `m!ownercmds` | List all owner-only commands |
| `m!ownerinfo` | View owner info embed |
| `m!reboot` | Restart the bot process |
| `m!sc` | Quick server check |
| `m!serverlog` | View the server join/leave log |
| `m!spylist` | View the spy list |
| `m!trustserver` | Trust a server for advanced features |
| `m!userglobal` | Manage global user settings |

</details>

### 🔧 Utility Commands `(25)`

<details>
<summary>Click to expand Utility Commands</summary>

| Command | Description |
|:--------|:------------|
| `m!afk` | Set your AFK status with a message |
| `m!avatar` | Get a user's avatar in full size |
| `m!banner` | View a user's profile banner |
| `m!botinfo` | View detailed bot information |
| `m!calc` | Calculator for expressions |
| `m!channelinfo` | View info about a channel |
| `m!color` | Preview a HEX or RGB color |
| `m!embed_cmd` | Create custom embed messages |
| `m!firstmsg` | Jump to the first message in a channel |
| `m!help` | Full command list & help menu |
| `m!inviteinfo` | Info about a Discord invite |
| `m!math` | Solve a math expression |
| `m!ping` | Check bot latency & API ping |
| `m!poll` | Create a yes/no or custom poll |
| `m!prefix` | Change the server prefix |
| `m!remind` | Set a timed reminder |
| `m!say` | Make the bot say something |
| `m!serverinfo` | Detailed server information |
| `m!snipe` | View the last deleted message |
| `m!timer` | Start a countdown timer |
| `m!translate` | Translate text to any language |
| `m!urban` | Look up a word on Urban Dictionary |
| `m!usercheck` | Check user account details |
| `m!userinfo` | View detailed user information |
| `m!weather` | Get real-time weather for any city |

</details>

---

## 📦 About This Repository

This is the **official privacy policy repository** for **Miko V7**. This policy is required by Discord's Developer Terms of Service and is publicly accessible via GitHub Pages.

> 🔗 **Live Policy Webpage:** [MikoDev-Sd.github.io/miko-privacy](https://MikoDev-Sd.github.io/miko-privacy/)

```
miko-privacy/
├── 📄 index.html     → Full privacy policy webpage (GitHub Pages)
├── 📄 README.md      → This file — full documentation & privacy policy
└── 📄 LICENSE        → MIT License
```

---

## 📦 What Data We Collect

Miko collects **only the minimum data** required to provide its features. We believe in minimal data collection — if a feature does not need your data, we do not collect it.

<div align="center">

| Data Type | Why We Collect It | Stored Permanently? |
|:----------|:------------------|:-------------------:|
| **Discord User IDs** | Identify users across commands: warns, AFK, reminders, leaderboards | ✅ Yes |
| **Discord Server (Guild) IDs** | Per-server config: custom prefix, autorole, log channels, sticky | ✅ Yes |
| **Discord Channel IDs** | Log channels, slowmode targets, report channels, sticky | ✅ Yes |
| **Discord Role IDs** | Autorole setup and moderation role tracking | ✅ Yes |
| **Message Content** | `m!snipe` and AFK auto-detection — RAM only, cleared on restart | ❌ Temporary |
| **IGN / Tier Data** | Ranking features submitted via `/rp` command | ✅ Firebase |
| **Warn / Mod Records** | Warnings issued via `/warn` or `m!warn` per user per server | ✅ Yes |
| **AFK Status & Message** | Set via `/afk` — cleared when user sends a message or restarts | ❌ Temporary |
| **Invite Cache** | Invite tracking per server — lives in RAM, refreshed on startup | ❌ RAM Only |
| **Auto-Responder Rules** | Custom keyword triggers set by server admins | ✅ Yes |
| **Blacklist Records** | Users globally blocked from bot usage by owner | ✅ Yes |
| **DM Authorization** | Servers/users granted mass-DM permissions | ✅ Yes |

</div>

### ❌ What We Do NOT Collect

```
✗  Passwords or login credentials
✗  Payment or financial information
✗  Real names, physical addresses, or phone numbers
✗  Email addresses
✗  IP addresses or device identifiers
✗  Private messages between users
✗  Voice chat audio, video, or transcripts
✗  Browser history or cookies
✗  Location data
✗  Any data from private DMs (except DMs Miko sends via commands like m!dm)
```

---

## ⚙️ How We Use Your Data

Every single piece of data Miko collects has one specific, limited purpose:

| Data | Exact Purpose |
|:-----|:-------------|
| **User IDs** | Power `/warn`, `/afk`, `/remind`, `/userinfo`, game scores, invite tracking |
| **Server IDs** | Store per-server prefix, autorole, log channel, sticky, and report channel config |
| **Channel & Role IDs** | Enable `/lock`, `/setlogs`, `/autorole`, `/slowmode`, report systems |
| **Message Content** | RAM-only snipe cache for `m!snipe`; AFK detection when mentioned |
| **IGN / Tier Data** | Firebase Realtime DB ranking system for tier commands |
| **Warn Records** | Track, view, and clear per-server member warnings |
| **Invite Cache** | Detect which invite was used when a member joins |
| **Auto-Responder** | Match keywords and respond with configured text or embeds |
| **Blacklist Records** | Prevent abusive users from accessing bot features globally |
| **Join/Leave events** | Send webhook notifications to your configured log channel |

> **We never use your data for advertising, AI training, profiling, analytics, or any purpose beyond running Miko's features.**

---

## 🔒 Data Storage & Security

<div align="center">

| Storage Layer | What Is Stored | Access Level |
|:--------------|:---------------|:------------|
| **Firebase Realtime Database** | IGN / Tier ranking data from `/rp` | Bot owner & authorized devs only |
| **Local JSON Files** | Warns, AFK, prefixes, autoroles, log channels, sticky, blacklist, DM auth | Bot owner & authorized devs only |
| **RAM (Temporary)** | Snipe message cache, AFK status, invite cache | Cleared on every bot restart |
| **config.json** | Bot token reference (env), webhook URLs, owner IDs | Hosting server only — never exposed |

</div>

### 🔐 Security Measures

```
[✔]  Bot token stored in .env — NEVER hardcoded in any file
[✔]  Firebase credentials kept private on the hosting server only
[✔]  Webhook URLs stored in config, never logged or exposed to users
[✔]  Hosting via Orihost / Pterodactyl panel with restricted panel access
[✔]  Data accessible only to bot owner (levi_ackerman.09) and authorized devs
[✔]  No third-party analytics, tracking scripts, or ad networks used anywhere
[✔]  Global uncaught exception handler prevents accidental data exposure via crashes
[✔]  All eval and owner commands are gated behind owner-ID verification
```

---

## 🚫 Data Sharing

**We do not sell, trade, rent, or share your data with any third parties — period.**

<div align="center">

| Third Party | Used For | What Is Shared |
|:------------|:---------|:--------------|
| **Firebase (by Google)** | Ranking data storage for tier system | IGN, Tier level, User ID only |
| **Discord API** | Core bot functionality | Standard Discord API scope |
| **Orihost / Pterodactyl** | Bot hosting infrastructure | No user data — server files only |
| **No one else** | — | Absolutely nothing |

</div>

```
✗  We do NOT sell data to advertisers or data brokers
✗  We do NOT share data with other Discord bots
✗  We do NOT use data for cross-platform tracking
✗  We do NOT share data with any government entities unless legally compelled
✓  Firebase is the ONLY external data service — used solely for ranking features
```

---

## 🗑️ Data Deletion

You have the full right to request deletion of your data at any time.

### ♻️ Automatic Deletion
- Temporary data (AFK status, snipe cache, invite cache) clears **every time the bot restarts**
- Removing Miko from your server **immediately stops** all new data collection for that server

### 📝 Manual Deletion — What You Can Request
- All warning records for a specific user in a specific server
- IGN / Tier ranking data linked to your Discord User ID
- Your server's complete configuration data (prefix, logs, autorole, sticky)
- Any stored reminders or AFK entries
- Auto-responder rules set for your server
- Your blacklist record (if applicable)
- DM authorization entries

**To request data deletion**, contact the developer via the methods listed in [Contact](#-contact). All requests are processed within **48 hours**.

---

## 👶 Users Under 13

Miko operates fully within **Discord's Terms of Service**, which requires all users to be **at least 13 years old** (or the minimum age required in their country).

- We do **not** knowingly collect data from users under 13
- If a user under 13 has submitted data (e.g. via `/rp` ranking), we will delete it immediately upon becoming aware
- Parents or legal guardians may contact us directly to request removal of a minor's data
- If you suspect a minor is using Miko inappropriately, please report it via our [Support Server](https://discord.gg/DUKpjHJtj3)

---

## ⚖️ Your Rights

As a user or server administrator, you hold the following rights:

| Right | What It Means |
|:------|:-------------|
| **Right to Access** | Request a full summary of what data Miko holds about you or your server |
| **Right to Deletion** | Request complete and permanent removal of your data |
| **Right to Opt-Out** | Stop using Miko commands at any time to stop new data from being collected |
| **Right to Know** | Know exactly what data is collected, why, and how — this document covers it all |
| **Right to Portability** | Request a copy of your stored data in a readable format |
| **Right to Correction** | Request correction of inaccurate stored data |

To exercise any of these rights, contact the developer directly via [Support Server](https://discord.gg/DUKpjHJtj3) or Discord DM.

---

## 📜 Changelog

<details>
<summary><b>V7 — Current (June 2026)</b> — Click to expand</summary>

```
╔══════════════════════════════════════════════════════╗
║             MIKO V7 — MAJOR RELEASE                 ║
╠══════════════════════════════════════════════════════╣
║  ✅  Complete discord.js v14 rewrite                 ║
║  ✅  Global crash guard — bot never goes down        ║
║  ✅  146 prefix commands fully categorized           ║
║  ✅  88+ slash commands deployed                     ║
║  ✅  Firebase Realtime DB integration (/rp system)   ║
║  ✅  Express API server with webhook dashboard       ║
║  ✅  Per-server config via JSON                      ║
║  ✅  Invite tracking with cache system               ║
║  ✅  Auto-responder & embed autoresponder            ║
║  ✅  Owner guard system (ownerGuard utility)         ║
║  ✅  34 games added (Connect4, Snake, Wordle, etc.)  ║
║  ✅  Mass DM system with authorization               ║
║  ✅  Pterodactyl / Orihost deployment                ║
║  ✅  Privacy Policy published (June 2026)            ║
╚══════════════════════════════════════════════════════╝
```

</details>

<details>
<summary><b>V6 — Previous Major Version</b></summary>

```
- Base command handler with prefix support
- Core moderation: ban, kick, warn, mute, timeout
- Initial fun & utility commands
- Basic per-server prefix customization
- Log channel setup system
```

</details>

<details>
<summary><b>V1 → V5 — Early Versions</b></summary>

```
- V1: Initial bot release with basic commands
- V2: Added games (TicTacToe, Connect4)
- V3: Moderation expansion (softban, deafen, role)
- V4: Utility commands (weather, translate, remind)
- V5: Owner panel and broadcast system
```

</details>

---

## ❓ FAQ

<details>
<summary><b>Q: Is Miko free to use?</b></summary>

> **Yes!** Miko is completely free. Just add it to your server and all 146+ commands are available instantly with no paywalls or premium tiers.

</details>

<details>
<summary><b>Q: How do I add Miko to my server?</b></summary>

> Click the button below or use the link: [Add Miko](https://discord.com/oauth2/authorize?client_id=1477957460575649903&scope=bot%20applications.commands&permissions=0)
> You need `Manage Server` permission in the Discord server to add bots.

</details>

<details>
<summary><b>Q: What is the default prefix?</b></summary>

> The default prefix is `m!`. You can change it per-server using `m!prefix <newprefix>`. Slash commands (`/`) work globally without any prefix setup.

</details>

<details>
<summary><b>Q: Miko is offline / not responding. What do I do?</b></summary>

> Join our [Support Server](https://discord.gg/DUKpjHJtj3) and let us know. Miko is built with a crash-resistant architecture, so outages are rare. If it's not responding to slash commands, try `m!ping` first to check if the prefix system is active.

</details>

<details>
<summary><b>Q: How do I set up mod logs?</b></summary>

> Use `m!setlogs #channel` or `/setlogs` to configure your moderation log channel. All bans, kicks, warns, mutes, and other mod actions will be posted there automatically.

</details>

<details>
<summary><b>Q: How do I set up autorole?</b></summary>

> Use `m!autorole @role` or `/autorole` to set a role that gets automatically given to members when they join your server.

</details>

<details>
<summary><b>Q: Can Miko delete my server data?</b></summary>

> Yes — just contact the developer via the [Support Server](https://discord.gg/DUKpjHJtj3) or DM `levi_ackerman.09` on Discord. All deletion requests are processed within 48 hours.

</details>

<details>
<summary><b>Q: Is Miko's code open source?</b></summary>

> The privacy policy repository is public. The main bot codebase is privately hosted. If you have questions about the code or architecture, contact the developer directly.

</details>

<details>
<summary><b>Q: Does Miko store voice chat data?</b></summary>

> **No.** Miko does not listen to, record, or store any voice chat audio, video, or transcripts. Voice state events are used only for moderation commands like deafen/undeafen.

</details>

<details>
<summary><b>Q: How do I report a bug or suggest a feature?</b></summary>

> Join our [Support Server](https://discord.gg/DUKpjHJtj3) and open a ticket or post in the relevant channel. You can also DM `levi_ackerman.09` directly on Discord.

</details>

---

## 🔄 Policy Updates

This privacy policy may be updated as Miko adds new features or as legal requirements change.

- The **"Last Updated"** badge at the top of this README and on the live page will always reflect the current version date
- Significant changes will be announced in the [Miko Support Server](https://discord.gg/DUKpjHJtj3)
- Continued use of Miko after any policy update constitutes acceptance of the revised policy
- Previous versions of this policy are not archived publicly — the current version is always the active one

**Current Version:** June 2026  
**Bot Version:** Miko V7  
**Policy Status:** ✅ Active & Compliant with Discord Developer ToS

---

## 📬 Contact

If you have questions, want to request data deletion, report a concern, or need support:

<div align="center">

| Method | Details |
|:------:|:--------|
| 💬 **Discord DM** | `levi_ackerman.09` |
| 🏠 **Support Server** | [discord.gg/DUKpjHJtj3](https://discord.gg/DUKpjHJtj3) |
| 🤖 **Bot ID** | `1477957460575649903` |
| 📄 **Policy Webpage** | [MikoDev-Sd.github.io/miko-privacy](https://MikoDev-Sd.github.io/miko-privacy/) |

</div>

> We aim to respond to **all** privacy-related inquiries within **48 hours**.

---


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,50:8B0000,100:1a0000&height=160&section=footer&text=Miko%20V7%20%F0%9F%8C%B8%20%E2%80%94%20Privacy%20First&fontSize=28&fontColor=fff&animation=twinkling&fontAlignY=65" width="100%"/>

**This policy complies with Discord's [Developer Terms of Service](https://discord.com/developers/docs/policies-and-agreements/developer-terms-of-service).**

Made with ❤️ by **[MikoDev-Sd](https://github.com/MikoDev-Sd)** · Pakistan 🇵🇰

[![Add Miko](https://img.shields.io/badge/➕%20Add%20Miko%20to%20Your%20Server-CC0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1477957460575649903&scope=bot%20applications.commands&permissions=0)
[![Support Server](https://img.shields.io/badge/💬%20Join%20Support%20Server-8B0000?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/DUKpjHJtj3)

![Views](https://komarev.com/ghpvc/?username=MikoDev-Sd&color=CC0000&style=flat-square&label=Repo+Views)

</div>
