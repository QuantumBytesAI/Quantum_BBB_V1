# Quantum Robot

<p align="center">
  <img src="https://i.ibb.co/bP4GnJ5/Black-Blue-Modern-Minimalist-Minutes-With-AI-Youtube-Thumbnail.png" alt="Quantum Robot">
</p>

<p align="center">
  <a href="https://github.com/Noob-Quantum/Quantum/stargazers"><img src="https://img.shields.io/github/stars/Noob-Quantum/Quantum?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Stars"></a>
  <a href="https://github.com/Noob-Quantum/Quantum/network/members"><img src="https://img.shields.io/github/forks/Noob-Quantum/Quantum?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/Noob-Quantum/Quantum/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blueviolet?style=for-the-badge" alt="License"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Written%20in-Python-skyblue?style=for-the-badge&logo=python" alt="Python"></a>
  <a href="https://pypi.org/project/Telethon/"><img src="https://img.shields.io/pypi/v/telethon?color=white&label=telethon&logo=python&logoColor=blue&style=for-the-badge" alt="Telethon"></a>
  <a href="https://pypi.org/project/Pyrogram/"><img src="https://img.shields.io/pypi/v/pyrogram?color=white&label=pyrogram&logo=python&logoColor=blue&style=for-the-badge" alt="Pyrogram"></a>
  <a href="https://github.com/Noob-Quantum/Quantum"><img src="https://img.shields.io/github/repo-size/Noob-Quantum/Quantum?color=skyblue&logo=github&logoColor=blue&style=for-the-badge" alt="Repo Size"></a>
  <a href="https://github.com/Noob-Quantum/Quantum/commits/Noob-Quantum"><img src="https://img.shields.io/github/last-commit/Noob-Quantum/Quantum?color=black&logo=github&logoColor=black&style=for-the-badge" alt="Last Commit"></a>
</p>

---

### 🚀 Quantum Group Controller

<h3>Welcome! Meet your new Telegram group management companion, Quantum Robot. Created collaboratively with BaBa, this bot simplifies your group management tasks. Enjoy exploring its many features and have a great time using it!</h3>

####Final Count
####Admin Commands: 121
####User Commands: 148

---

## Requirements

- [Python 3.11.5](https://www.python.org/downloads/release/python-3115/)
- [Telegram API Key](https://docs.pyrogram.org/intro/setup#api-keys)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://telegra.ph/How-To-get-Mongodb-URI-04-06)

---

## Deploy on Heroku 🚀

Deploying the Group Controller is easiest via Heroku:

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/quantum/#"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45" alt="Deploy to Heroku"></a></p>

---

## How to Make Your Own Group Management Bot

Discover the secrets by following our [YouTube video tutorial](https://youtu.be/#).

![YouTube Video Views](https://img.shields.io/youtube/views/YT_nYVb0OxI?style=social)

---

## Deploy on VPS/Local

### VPS/Local Deployment Method

1. Obtain your [Necessary Variables](https://github.com/#).
2. Perform an upgrade and update:
   ```bash
   sudo apt-get update && sudo apt-get upgrade -y
   ```
3. Install required packages:
   ```bash
   sudo apt-get install python3-pip -y
   ```
4. Install pip:
   ```bash
   sudo pip3 install -U pip
   ```
5. Clone the repository:
   ```bash
   git clone https://github.com/Noob-Quantum/advance-repo && cd Quantum
   ```
6. Install/Upgrade setuptools:
   ```bash
   pip3 install --upgrade pip setuptools
   ```
7. Install requirements:
   ```bash
   pip3 install -U -r requirements.txt
   ```
8. Fill in your variables in `config.py`:
   ```bash
   vi Quantum/config.py
   ```
   - Press `I` to edit, `Esc` to stop, and `:wq` to save.
9. Install tmux to keep the bot running:
   ```bash
   sudo apt install tmux && tmux
   ```
10. Run the bot:
    ```bash
    python3 -m Quantum
    ```
11. Exit from tmux: Press `Ctrl+b` then `d`.

---

## Write New Modules

Add license text here; obtain it from below.

```python
from Quantum import pbot, quantum  # This is bot's client
from pyrogram import filters  # Pyrogram filters

# Module information
__mod_name__ = "Module Name"
__help__ = "Module help message"

@quantum.on_message(filters.command("start"))
async def some_function(_, message):
    await message.reply_text("ɪ'ᴍ.ᴀʟɪᴠᴇ ʙᴀʙʏ❣️!!")

# Many useful functions are in Quantum/utils/, Quantum, and Quantum/modules/
```

Place this file in `Quantum/modules/`, restart, and test your bot.

---

## Credits

Special thanks to the Quantum project and all [contributors](https://github.com/Noob-Quantum/Quantum/graphs/contributors) for making this group controller both powerful and useful ❤️.

---

# 🎩✨ Quantum Bot Documentation  

Embark on an epic journey with **Quantum Bot**, your magical guide to mastering group dynamics! With a broad array of features and commands, it's the perfect solution to efficiently manage your Telegram groups. Developed through a brilliant collaboration among **BaBa**, **Quantum**, **Quantums Head Developer Mukesh**, and the ingenious **developer Chikuu**, Quantum Bot is designed to guide admins, support users, and engage members effectively. This documentation is your roadmap to explore Quantum Bot's capabilities.

## Table of Contents  

- [Modules Overview](#modules-overview)
- [Admin Commands](#admin-commands)  
- [Approval System](#approval-system)  
- [Ban Commands](#ban-commands)  
- [Blacklist Commands](#blacklist-commands)  
- [Clean Commands](#clean-commands)  
- [Connection Commands](#connection-commands)  
- [Filter Commands](#filter-commands)  
- [Disable Commands](#disable-commands)  
- [Developer Commands](#developer-commands)  
- [Eval Commands](#eval-commands)  
- [Federation Commands](#federation-commands)  
- [Flood Control](#flood-control)  
- [Force Subscribe](#force-subscribe)  
- [Lock Commands](#lock-commands)  
- [Log Commands](#log-commands)  
- [Mute Commands](#mute-commands)  
- [Night Mode Commands](#night-mode-commands)  
- [Notes Commands](#notes-commands)  
- [Tag All Commands](#tag-all-commands)  
- [Warn Commands](#warn-commands)  
- [Welcome Commands](#welcome-commands)  
- [Zombie Commands](#zombie-commands)  
- [Categories and Quick Links](#categories-and-quick-links)  

### Modules Overview  

[🔝 Back to Top](#table-of-contents)  

Quantum Bot is designed like a wizard's toolkit, filled with modules perfect for every need. Each module offers a suite of commands to enhance your group management seamlessly. Experience administrative efficiency or enhance user interactions—all at the command of Quantum Bot.  

🔹 **Explore Abundant Features:** Delve deeper and discover how each module can transform your group experience. Prepare to unlock your community's potential with Quantum Bot as your guide!

---

## Admin Commands  

[🔝 Back to Top](#table-of-contents)  

Effortlessly manage your group with these admin tools:  

- **Pin/Unpin Commands**:   
  - `/pin` - Silently pin a message, or use `'loud'` for notifications.  
  - `/unpin` - Unpin the current pinned message.  
- **Promotion & Invitation**:   
  - `/invitelink` - Get the group's invite link.  
  - `/promote` - Promote a user with standard rights.  
  - `/lowpromote` - Promote a user with limited rights.  
  - `/fullpromote` - Grant full rights to a user.  
  - `/demote` - Demote a user from their admin role.  
- **Title & Admin List**:  
  - `/title <title>` - Set a custom title for a promoted admin.  
  - `/admincache` - Refresh the list of admins.  
- **Message Management**:   
  - `/del` - Delete a specific message.  
  - `/purge` - Delete messages between two points.  
  - `/spurge` - Clear messages between two specific messages.  
- **Group Settings**:  
  - `/setgtitle <title>` - Change the group title.  
  - `/setgpic` - Change the group photo (reply with an image).  
  - `/setdesc` - Set a group description.  
  - `/setsticker` - Set the group sticker.  

---

## Approval System  

[🔝 Back to Top](#table-of-contents)  

Manage trusted users with these commands:  

- `/approval`: Check a user's approval status.  
- `/approve`: Exempt a user from restrictions.  
- `/unapprove`: Revoke a user's approved status.  
- `/approved`: List all approved users.  
- `/unapproveall`: Remove approval for all users.  

---

## Ban Commands  

[🔝 Back to Top](#table-of-contents)  

Manage group participation effectively:  

- **Self-Kick**:  
  - `/kickme`: Remove yourself from the group.  
- **Admin Commands**:  
  - `/ban <user>`: Ban a user.  
  - `/sban <user>`: Silently ban a user.  
  - `/tban <user> <time>`: Temporarily ban a user.  
  - `/unban <user>`: Unban a user.  
  - `/kick <user>`: Kick a user from the group.  
  
---

## Blacklist Commands  

[🔝 Back to Top](#table-of-contents)  

Automate the removal of unwanted messages:  

- `/blacklist`: View blacklisted words.  
- **Admin Commands**:  
  - `/addblacklist <triggers>`: Add triggers to the blacklist.  
  - `/unblacklist <triggers>`: Remove blacklist triggers.  
  - `/blacklistmode <action>`: Define action for blacklisted words.  

---

## Clean Commands  

[🔝 Back to Top](#table-of-contents)  

Declutter your group by managing messages:  

- `/cleanblue <on/off>`: Toggle cleaning of 'blue text'.  
- `/ignoreblue <word>`: Exclude specific words from cleaning.  
- `/unignoreblue <word>`: Remove word exclusion.  
- `/listblue`: View ignored words list.  

---

## Connection Commands  

[🔝 Back to Top](#table-of-contents)  

Manage shared notes and filters across chats:  

- `/connect`: Connect to another chat's database.  
- `/connection`: View connected chats.  
- `/disconnect`: Disconnect from a chat.  
- `/helpconnect`: Get help on managing connections.  

---

## Filter Commands  

[🔝 Back to Top](#table-of-contents)  

Create automated responses for specific keywords:  

- `/filters`: View all filters.  
- **Admin Commands**:  
  - `/filter <keyword> <reply>`: Create a new filter.  
  - `/stop <keyword>`: Remove a filter.  
- **Chat Creator Only**:  
  - `/removeallfilters`: Clear all filters.  

---

## Disable Commands  

[🔝 Back to Top](#table-of-contents)  

Control the activation of commands:  

- `/cmds`: Check active/disabled commands.  
- **Admin Commands**:  
  - `/enable <command>`: Activate a command.  
  - `/disable <command>`: Deactivate a command.  
  - `/enablemodule <module>`: Activate all commands in a module.  
  - `/disablemodule <module>`: Deactivate all commands in a module.  
  - `/listcmds`: List all toggleable commands.  

---

## Developer Commands  

[🔝 Back to Top](#table-of-contents)  

Advanced functions for developers:  

- `/sudolist`: List sudo users.  
- `/supportlist`: View support users.  
- `/ping`: Check bot response time.  
- **Broadcast (Owner Only)**:  
  - `/broadcastusers`: Message all users.  
  - `/broadcastgroups`: Message all groups.  

---

## Eval Commands  

[🔝 Back to Top](#table-of-contents)  

Owner-exclusive commands for advanced operations:  

- `/eval`: Run code snippets.  
- `/ex`: Execute system commands.  
- `/clear`: Clear command results.  
- `/unbanall`: Lift bans on all users.  
- `/unmuteall`: Unmute all users.  
- `/users`: List group members.  

---

## Federation Commands  

[🔝 Back to Top](#table-of-contents)  

Enforce bans across joined groups:  

- `/fedownerhelp`: Help for federation owners.  
- `/fedadminhelp`: Help for federation admins.  
- `/feduserhelp`: Help for federation users.  

---

## Flood Control  

[🔝 Back to Top](#table-of-contents)  

Manage message flooding:  

- `/flood`: View current flood control settings.  
- **Admin Commands**:  
  - `/setflood <int/'no'/'off'>`: Set limits or disable flood control.  
  - `/setfloodmode <action> <value>`: Define action when limits are exceeded.  

---

## Force Subscribe  

[🔝 Back to Top](#table-of-contents)  

Control user subscriptions via channels:  

- `/fsub <channel>`: Activate forced subscriptions.  
- `/fsub off`: Disable forced subscriptions.  

---

## Lock Commands  

[🔝 Back to Top](#table-of-contents)  

Restrict specific content types:  

- `/locktypes`: List all lockable content.  
- **Admin Commands**:  
  - `/lock <type>`: Restrict a content type.  
  - `/unlock <type>`: Allow a restricted type.  
  - `/locks`: View current restrictions.  

---

## Log Commands  

[🔝 Back to Top](#table-of-contents)  

Enable activity logging:  

- **Admin Commands**:  
  - `/logchannel`: Get current log channel info.  
  - `/setlog`: Set log channel.  
  - `/unsetlog`: Remove log setup.  

---

## Mute Commands  

[🔝 Back to Top](#table-of-contents)  

Manage speaking permissions:  

- **Admin Commands**:  
  - `/mute <user>`: Mute a user.  
  - `/tmute <user> <time>`: Temporarily mute a user.  
  - `/unmute <user>`: Unmute a user.  

---

## Night Mode Commands  

[🔝 Back to Top](#table-of-contents)  

Automate night management:  

- **Admin Commands**:  
  - `/nightmode`: Add group to night mode.  
  - `/rmnight`: Remove group from night mode.  

---

## Notes Commands  

[🔝 Back to Top](#table-of-contents)  

Facilitate group communication:  

- Retrieve and manage notes:  
  - `/get <note>`: Get a note.  
  - `/notes`: List notes.  
- **Admin Commands**:  
  - `/save <note> <data>`: Save a note.  
  - `/clear <note>`: Delete a note.  
  - `/removeallnotes`: Clear all notes.  

---

## Tag All Commands  

[🔝 Back to Top](#table-of-contents)  

Urgent communication to all members:  

- **Admin Commands**:  
  - `/tagall` or `@all`: Tag all members.  

---

## Warn Commands  

[🔝 Back to Top](#table-of-contents)  

Manage user behavior with warnings:  

- `/warns <user>`: View user warnings.  
- `/warnlist`: Current warning triggers.  
- **Admin Commands**:  
  - `/warn <user>`: Warn a user.  
  - `/resetwarn <user>`: Reset warnings.  
  - `/addwarn <keyword> <reply>`: Add warning trigger.  
  - `/nowarn <keyword>`: Remove trigger.  
  - `/warnlimit <num>`: Set warning threshold.  
  - `/strongwarn <on/off>`: Toggle strong actions.  

---

## Welcome Commands  

[🔝 Back to Top](#table-of-contents)  

Set custom welcome messages:  

- Toggle and display options:  
  - `/welcome <on/off>`: Control welcome messages.  
  - `/welcome`: Show current setup.  
- **Setting Messages**:  
  - `/setwelcome <text>`: Customize welcome message.  
  - `/setgoodbye <text>`: Set goodbye message.  
  - `/resetwelcome`: Reset welcome message.  
  - `/resetgoodbye`: Reset goodbye message.  
  - `/cleanwelcome <on/off>`: Manage old welcome messages.  

---

## Zombie Commands  

[🔝 Back to Top](#table-of-contents)  

Remove inactive members:  

- `/zombies`: Identify inactive accounts.  
- `/zombies clean`: Remove inactive accounts.  

---

## Categories and Quick Links  

[🔝 Back to Top](#table-of-contents)  

Navigate commands with ease using bot buttons:  

- 🖱️ **Modules**: Button guides for command details.  
- 🔄 **Help Back**: Navigation to explore modules or return.

---

---

---


# 📚 User Commands Help Document 📚

Welcome to BaBa's User Command guide! This document is your gateway to understanding all the amazing things BaBa can do. From text transformations to interactive games, it's all here for you to explore. Enjoy the journey! 🎉

[🔝 Back to Top](#user-commands-help-document)  

---

## Categories and Quick Links

Easily explore sections using quick links:

- [📝 Text and Fun Commands](#-text-and-fun-commands)
- [🎉 Interactive Games and Fun](#-interactive-games-and-fun)
- [📌 Creative Features](#-creative-features)
- [🔍 Information and Learning](#-information-and-learning)
- [🚦 Utility Features](#-utility-features)
- [⚽ Social and Youth Features](#-social-and-youth-features)
- [🖼️ Image Editing Commands](#-image-editing-commands)
- [🎥 Video Editing Commands](#-video-editing-commands)
- [🌟 Image and Media Search](#-image-and-media-search)
- [🎭 Meme and Fun Features](#-meme-and-fun-features)
- [🎞️ Movie and Entertainment](#-movie-and-entertainment)
- [🎴 Pokémon and Trivia](#-pokedex)
- [🗨️ Social and Interactive Commands](#-social-and-interactive-commands)
- [✂️ URL Shortening](#-url-shortening)
- [☁️ Weather and Time](#-weather-and-time)
- [🌐 Search and Research](#-search-and-research)
- [✏️ Writing and Documentation](#-writing-and-documentation)
- [🦘 Kang (Sticker Management and Fun)](#-kang-sticker-management-and-fun)
- [🔖 Tᴀɢᴀʟʟ (Admin Only Group Mentions)](#-tagall-admin-only-group-mentions)
- [📊 T-Gʀᴀᴘʜ (Telegraph Uploader)](#-t-gʀᴀᴘʜ-telegraph-uploader)
- [🐜 TINY (Miniaturize Stickers)](#-tiny-miniaturize-stickers)
- [📈 Rankings](#-rankings)
- [🔎 Google and 🔖 Hashtag](#-google-and-hashtag)
- [🎯 Match and 💸 Cash](#-match-and-cash)
- [🔊 BabaAI and 📺 Anime](#-babai-and-anime)

Navigate commands with ease using bot buttons:

- 🖱️ **Modules**: Button guides for command details.
- 🔄 **Help Back**: Navigation to explore modules or return.

---

## 📝 Text and Fun Commands

| Command | Description |
|---------|-------------|
| `/google 🕵️ <text>` | Conduct a Google search with BaBa's help. |
| `/img 🖼️ <text>` | Search Google for images. |
| `/app 📱 <appname>` | Search the Play Store for app details. |
| `/reverse 🔍` | Reverse search an image by replying to it. |
| `/time ⌛ <query>` | Get current time for a specified location. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎉 Interactive Games and Fun

| Command | Description |
|---------|-------------|
| `/dice 🎲` | Thrilling dice game with BaBa. |
| `/dart 🎯` | Engage in a dart competition with BaBa. |
| `/basket 🏀` | Virtual basketball game. |
| `/ball 🎳` | Bowl virtually with BaBa. |
| `/football ⚽` | Play an exciting football match. |
| `/jackpot 🎰` | Try your luck with a slot machine. |
| `/coinflip 🪙` | Flip a coin and see the result. |
| `/rockpaperscissors 🪨📄✂️` | Play Rock-Paper-Scissors with BaBa. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 📌 Creative Features

### 🖌️ Text Art and Formatting 

| Command | Description |
|---------|-------------|
| `/figlet 📝` | Create Figlet artwork from text. |
| `/fonts 🖋️ <text>` | Transform text into various fonts. |

### 🎨 Logo and Image Creation

| Command | Description |
|---------|-------------|
| `/logo 🎨` | Create an eye-catching logo. |
| `/babaimageai <prompt>` | Generate an artistic image based on text prompt. |

[🔝 Back to Top](#user-commands-help-document)

---

## 🔍 Information and Learning

### 🌐 Country Information

| Command | Description |
|---------|-------------|
| `/country 🌍 <country>` | Get detailed information about a country. |

### 📚 Language and Grammar

| Command | Description |
|---------|-------------|
| `/define 📚 <word>` | Get the definition of a word or phrase. |
| `/spell ✍️` | Suggest corrections to a text. |
| `/synonyms 💭 <word>` | Find synonyms for a word. |
| `/antonyms 🔀 <word>` | Find antonyms for a word. |
| `/pronounce 🔊 <word>` | Get the pronunciation of a word. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🚦 Utility Features

### 🚀 Speed and Technical Utilities

| Command | Description |
|---------|-------------|
| `/speedtest 🚀` | Perform a speed test for server speed. |
| `/carbon` | Create a carbon visual copy of text. |

### 🗃️ Text Conversion

| Command | Description |
|---------|-------------|
| `/encrypt 🔒` | Encrypt text. |
| `/decrypt 🔓` | Decrypt previously encrypted text. |
| `/hash 🔑` | Generate a SHA-256 hash of the text. |

### 🗺️ Location Utilities

| Command | Description |
|---------|-------------|
| `/gps 🌍 <location>` | Get GPS coordinates of a place. |
| `/distance 📏` | Measure distance between two places. |
| `/address 🏠 <location>` | Get address from GPS coordinates. |

[🔝 Back to Top](#user-commands-help-document)

---

## ⚽ Social and Youth Features

### 💬 Games and Social Interactive

| Command | Description |
|---------|-------------|
| `/couples 💑` | Randomly pick two users as a couple. |
| `/animequotes 🎎` | Fetch a random anime quote. |
| `/quote 🖋️` | Get traditional quotes. |

### 🌟 Entertainment and Humor

| Command | Description |
|---------|-------------|
| `/runs 💫` | Receive a random pre-programmed message. |
| `/slap 👋` | Slap or get slapped playfully. |

[🔝 Back to Top](#user-commands-help-document)

---

## 🎬 Image Editing Commands

| Command | Description |
|---------|-------------|
| `/upscale 🎆` | Upscale an image for better quality. |
| `/rotate 🔄` | Rotate an image by the desired angle. |
| `/resize 📏` | Change the dimensions of an image. |
| `/filter 🎨` | Apply filters like Blur, Grayscale, etc. |
| `/crop ✂️` | Crop an image to your specified size. |
| `/convert 🔄` | Convert image format. |
| `/rmbg 🪄` | Remove the background from an image. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎥 Video Editing Commands

| Command | Description |
|---------|-------------|
| `/vtxt 🎥📝` | Convert video content to text. |
| `/remove 🎬🔇` | Remove audio or video from media. |
| `/extract_audio 🎥🎶` | Extract audio from video files. |
| `/convert_audio 🎵🔄` | Change the audio format. |
| `/merge_audio 🎶➕🎶` | Merge multiple audio files. |
| `/trim_video 🎥✂️` | Trim a video to your specified duration. |
| `/resize_video 📏🎥` | Alter the dimensions of a video. |
| `/rotate_video 🔄🎥` | Rotate video by a specific degree. |
| `/change_speed ⏩⏪` | Adjust the speed of a video. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🌟 Image and Media Search

| Command | Description |
|---------|-------------|
| `/bimg 📌` | Fetch Pinterest images. |
| `/img 🌐` | Search for images via Google. |
| `/rp 🖼️` | Get a random wallpaper image. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎭 Meme and Fun Features

| Command | Description |
|---------|-------------|
| `/mmf 🧩` | Create humorous memes with text. |
| `/echo 📢` | Have BaBa echo a message in a group. |
| `/report 📢` | Report a message to group admins. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎞️ Movie and Entertainment

| Command | Description |
|---------|-------------|
| `/movie ✨` | Search for movies in the database. |
| `/paste 📋` | Display content of a text file. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎴 Pokémon and Trivia

| Command | Description |
|---------|-------------|
| `/pokemon <name>` | Search for Pokémon details. |
| `/berries`, `/contests`, etc. | Explore various Pokémon categories. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🗨️ Social and Interactive Commands

| Command | Description |
|---------|-------------|
| `/quote 💬` | Create a quote from a message. |
| `/ranking 📈` | Check different user rankings. |
| `/id`, `/bio` | Fetch user or group details. |

[🔝 Back to Top](#user-commands-help-document)  

---

## ✂️ URL Shortening

| Command | Description |
|---------|-------------|
| `/short` | Shorten a URL for easier sharing. |
| `/unshort` | Expand a shortened URL. |

[🔝 Back to Top](#user-commands-help-document)  

---

## ☁️ Weather and Time 

| Command | Description |
|---------|-------------|
| `/weather` | Get weather updates for a location. |
| `/time` | Check the current time in a timezone. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🌐 Search and Research 

| Command | Description |
|---------|-------------|
| `/wiki 📚` | Search for articles on Wikipedia. |
| `/webshot 🌐` | Capture screenshots of webpages. |

[🔝 Back to Top](#user-commands-help-document)  

---

## ✏️ Writing and Documentation 

| Command | Description |
|---------|-------------|
| `/write` | Write text beautifully on a virtual paper. |
| `/translate 🌐` | Translate text between languages. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🦘 Kang (Sticker Management and Fun)

| Command | Description |
|---------|-------------|
| `/stickerid` | Reply to a sticker to get its file ID. |
| `/getsticker` | Reply to a sticker to get the raw PNG file. |
| `/kang` | Add a sticker to your personal pack. |
| `/stickers` | Search for stickers related to a term in the combot sticker catalogue. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🔖 Tᴀɢᴀʟʟ (Admin Only Group Mentions)

| Command | Description |
|---------|-------------|
| `/tagall` or `@all` | Mention all members in your group. Only usable by admins. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 📊 T-Gʀᴀᴘʜ (Telegraph Uploader)

| Command | Description |
|---------|-------------|
| `/tgm` | Upload a media file to Telegraph and get a link. |
| `/tgt` | Upload text to Telegraph. |
| `/tgt [custom name]` | Upload text with a custom name. |
| `/tgd` | Delete the last uploaded file. |
| `/tgl` | List all uploaded files on Telegraph. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🐜 TINY (Miniaturize Stickers)

| Command | Description |
|---------|-------------|
| `/tiny` | Reply to a sticker to create a mini version. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 📈 Rankings

| Command | Description |
|---------|-------------|
| `/overall` | Check the overall leaderboard based on user messages. |
| `/today` | View today's leaderboard. |
| `/weekly` | See the leaderboard for the current week. |
| `/monthly` | Check this month's leaderboard. |
| `/ranking` | Access the overall user ranking system. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎴 Pokédex

| Command | Description |
|---------|-------------|
| `/pokemon <name>` | Search for details about a specific Pokémon. |
| `/berries` | List Pokémon berries. |
| `/contests` | Get info on Pokémon contests. |
| `/encounters` | Explore Pokémon encounter details. |
| `/evolution` | Learn about Pokémon evolutions. |
| `/games` | Discover various Pokémon games. |
| `/items` | View a catalog of Pokémon items. |
| `/locations` | Find Pokémon locations. |
| `/machines` | See a list of Pokémon machines. |
| `/moves` | Explore Pokémon moves. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🖼️ Movie

| Command | Description |
|---------|-------------|
| `/movie` | Search the Movie database for film information. |

[🔝 Back to Top](#user-commands-help-document)  

---

## ✨ Image Search

| Command | Description |
|---------|-------------|
| `/bimg` | Fetch a collection of Pinterest images. |
| `/img` | Search for a collection of Google images. |
| `/rp` | Get a random wallpaper image. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎥 Editor and 🖼️ Image Editor

| Command | Description |
|---------|-------------|
| `/vtxt` | Convert video to text. |
| `/remove` | Remove audio or video from a media file. |
| `/extract_audio` | Extract audio from a video. |
| `/convert_audio` | Convert audio format. |
| `/merge_audio` | Merge two audio files. |
| `/trim_video` | Trim a video to a specific duration. |
| `/resize_video` | Resize video dimensions. |
| `/rotate_video` | Rotate a video by a specified angle. |
| `/change_speed` | Change video speed. |
| `/upscale` | Upscale an image. |
| `/rotate` | Rotate an image. |
| `/resize` | Resize an image. |
| `/filter` | Apply filters to an image. |
| `/crop` | Crop an image. |
| `/convert` | Change the image format. |
| `/rmbg` | Remove background from an image. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🖼️ BabaAI

| Command | Description |
|---------|-------------|
| `/imageai <prompt>` | Generate a unique artistic image based on a text prompt. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🔎 Google and 🔖 Hashtag

| Command | Description |
|---------|-------------|
| `/google` | Conduct a Google search. |
| `/img` | Search Google for images. |
| `/app` | Search the Play Store for app details. |
| `/reverse` | Perform a reverse image search. |
| `/hashtag <word>` | Generate top hashtags for a keyword. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🎯 Match and 💸 Cash

| Command | Description |
|---------|-------------|
| `/dice` | Play dice game. |
| `/dart` | Play dart game. |
| `/basket` | Shoot basketball. |
| `/ball` | Bowl virtually. |
| `/football` | Play football. |
| `/jackpot` | Spin the slot machine. |
| `/coinflip` | Flip a coin. |
| `/rockpaperscissors` | Play Rock-Paper-Scissors. |
| `/cash <amount> <from> <to>` | Convert currency. |
| `/currency` | List supported currencies. |

[🔝 Back to Top](#user-commands-help-document)  

---

## 🔊 BabaAI and 📺 Anime

| Command | Description |
|---------|-------------|
| `/audioai <prompt>` | Generate audio from a prompt. |
| `/anime <anime>` | Get anime details from AniList. |
| `/character <character>` | Fetch character info. |
| `/manga <manga>` | Obtain manga details. |
| `/user <user>` | Learn about a user on MyAnimeList.net. |
| `/airing <anime>` | Get anime airing info. |

[🔝 Back to Top](#user-commands-help-document)  

---

**Feel free to explore and enjoy using BaBa! 🥳**
*Note: Always ensure to follow community guidelines while interacting with the commands provided.*

---

For support, contact our team or special members using commands like `/devs` for developers or `/supportlist` for supporters.

> **Tip**: Regularly update your bot for new features and security!

---

Thank you for choosing Quantum Bot and Baba, simplifying group management with style! 🎉

Developers ( BABAV1, Quantum, Muk, Chik )
