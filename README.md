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

For support, contact our team or special members using commands like `/devs` for developers or `/supportlist` for supporters.

> **Tip**: Regularly update your bot for new features and security!

Thank you for choosing Quantum Bot and Baba, simplifying group management with style! 🎉
