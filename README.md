# Quantum ʀᴏʙᴏᴛ

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

Welcome aboard the Quantum Robot—a trailblazing ally for your Telegram group management adventures, brought to you in collaboration with BaBa! 🌟 Dive into an exhilarating demo of its dynamic features and capabilities. Remember, this demo is your passport to a temporary thrill, so make sure to explore and enjoy every innovation it offers while it’s here! 😄
---

## ʀᴇǫᴜɪʀᴇᴍᴇɴᴛs

- [Python 3.11.5](https://www.python.org/downloads/release/python-3115/)
- [Telegram API Key](https://docs.pyrogram.org/intro/setup#api-keys)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://telegra.ph/How-To-get-Mongodb-URI-04-06)

---

## ᴅᴇᴘʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 🚀

The easiest way to deploy the Group Controller:

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/noob-mukesh/advance-repo"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45" alt="Deploy to Heroku"></a></p>

---

## ʜᴏᴡ ᴛᴏ ᴍᴀᴋᴇ ʏᴏᴜʀ ᴏᴡɴ ɢʀᴏᴜᴘ ᴍᴀɴᴀɢᴇᴍᴇɴᴛ ʙᴏᴛ

Discover the secrets by following our [video tutorial on YouTube](https://youtu.be/#):

![YouTube Video Views](https://img.shields.io/youtube/views/YT_nYVb0OxI?style=social)

---

## ᴅᴇᴩʟᴏʏ ᴏɴ ᴠᴘs/ʟᴏᴄᴀʟ

### ᴠᴘs/ʟᴏᴄᴀʟ ᴅᴇᴘʟᴏʏᴍᴇɴᴛ ᴍᴇᴛʜᴏᴅ

1. Obtain your [Necessary Variables](https://github.com/Noob-Quantum/advance-repo/blob/main/Quantum/config.py).
2. Upgrade and Update:
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
8. Fill your variables in `config.py`:
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

## ᴡʀɪᴛᴇ ɴᴇᴡ ᴍᴏᴅᴜʟᴇs

Add license text here; get it from below.

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

Massive thanks to the Quantum project and all [contributors](https://github.com/Noob-Quantum/Quantum/graphs/contributors) who helped make this group controller both powerful and useful ❤️.

[QUANTUM](https://t.me/quantumbytesai)


This version uses standard elements like headers, lists, and code blocks that should render consistently across different GitHub markdown viewers, ensuring clarity and readability. Remember to preview the changes on GitHub to ensure everything appears as expected.


# 🎩✨ Quantum Bot Documentation  

Welcome to the enchanted world of **Quantum Bot**—your ultimate guide to mastering group dynamics in a magical and efficient way! With a spellbinding array of features and commands, Quantum Bot is your trusty companion, developed in a collaboration of brilliance among **BaBa**, **Quantum's visionary Head Developer Mukesh**, and the ingenious **developer Chikuu**. This documentation is your map to navigate these features, whether you're leading as an admin, supporting as a trusted user, or participating as an enthusiastic member.  

## Table of Contents  

- [🌟 Modules Overview](#modules-overview)  
- [👮‍♂️ Admin Commands](#admin-commands)  
- [🙌 Approval System](#approval-system)  
- [❌ Ban Commands](#ban-commands)  
- [📝 Blacklist Commands](#blacklist-commands)  
- [⚙️ Clean Commands](#clean-commands)  
- [🔗 Connection Commands](#connection-commands)  
- [🔦 Filter Commands](#filter-commands)  
- [🚫 Disable Commands](#disable-commands)  
- [🛠 Developer Commands](#developer-commands)  
- [📊 Eval Commands](#eval-commands)  
- [🌐 Federation Commands](#federation-commands)  
- [🚱 Flood Control](#flood-control)  
- [📢 Force Subscribe](#force-subscribe)  
- [🔒 Lock Commands](#lock-commands)  
- [🛑 Log Commands](#log-commands)  
- [🔕 Mute Commands](#mute-commands)  
- [🌙 Night Mode Commands](#night-mode-commands)  
- [🗒 Notes Commands](#notes-commands)  
- [📣 Tag All Commands](#tag-all-commands)  
- [⚠️ Warn Commands](#warn-commands)  
- [👋 Welcome Commands](#welcome-commands)  
- [👻 Zombie Commands](#zombie-commands)  
- [📜 Categories and Quick Links](#categories-and-quick-links)  

### Discover the Magic Within: Modules Overview  

[🔝 Back to Top](#-quantum-bot-documentation)  

The Quantum Bot is designed like a wizard's toolkit, jam-packed with enchanting modules tailor-made for every conceivable need. Each module unveils a treasure trove of specialized commands that empower you to manage and optimize your group with the elegance of magic. Whether it's seamlessly executing administrative tasks or weaving intricate user interactions, Quantum Bot provides the charms necessary—all at the flick of a command.  

🔹 **Captivating Features Await:** Delve deeper to discover how each module can elevate your group experience to mythical heights. Be prepared to unleash the full potential of your community with Quantum Bot as your guide!

---  

## 👮‍♂️ Admin Commands   

[🔝 Back to Top](#table-of-contents)  

Admin tools to manage your group effortlessly:  

- **Pin/Unpin Commands**:   
  - `/pin` - Silently pins a message. Use `'loud'` or `'notify'` for notifications.  
  - `/unpin` - Unpins the current pinned message.  
- **Invite and Promotion**:   
  - `/invitelink` - Retrieves the group's invite link.  
  - `/promote` - Promotes a user with standard rights.  
  - `/lowpromote` - Promotes a user with limited rights.  
  - `/fullpromote` - Grants full rights to a user.  
  - `/demote` - Demotes a user from their admin position.  
- **Title and Admin List**:  
  - `/title <title>` - Sets a custom title for a promoted admin.  
  - `/admincache` - Refreshes the list of admins.  
- **Message Management**:   
  - `/del` - Deletes a specific message.  
  - `/purge` - Deletes messages in bulk between two points.  
  - `/spurge` - Deletes all messages between two specified messages.  
- **Group Settings**:  
  - `/setgtitle <title>` - Updates the group title.  
  - `/setgpic` - Updates the group photo (reply with an image).  
  - `/setdesc` - Sets a group description.  
  - `/setsticker` - Sets the group sticker.  

---  

## 🙌 Approval System  

[🔝 Back to Top](#table-of-contents)  

Manage trusted users with approval commands:  

- `/approval`: Check a user's approval status in the chat.  
- `/approve`: Exempt a user from locks and blacklists.  
- `/unapprove`: Revoke approval for a user, reapplying restrictions.  
- `/approved`: List all approved users.  
- `/unapproveall`: Remove approval for all users.  

---  

## ❌ Ban Commands  

[🔝 Back to Top](#table-of-contents)  

Efficiently manage who can stay in your group:  

- **Self-Kick**:  
  - `/kickme`: Kick yourself from the group.  
- **Admin Only**:  
  - `/ban <user>`: Bans a user.  
  - `/sban <user>`: Silently bans a user, removing visibility of command/reply.  
  - `/tban <user> <time>`: Temporarily bans a user (`m` for minutes, `h` for hours, `d` for days).  
  - `/unban <user>`: Unbans a previously banned user.  
  - `/kick <user>`: Kicks a user from the group.  
  
---  

## 📝 Blacklist Commands  

[🔝 Back to Top](#table-of-contents)  

Automate deletion of unwanted messages:  

- `/blacklist`: Shows the list of blacklisted words.  
- **Admin Only**:  
  - `/addblacklist <triggers>`: Add new triggers to the blacklist.  
  - `/unblacklist <triggers>`: Remove triggers from the blacklist.  
  - `/blacklistmode <action>`: Set an action (e.g., `off`, `del`, `warn`, `ban`) when a blacklisted word is detected.  

---  

## ⚙️ Clean Commands  

[🔝 Back to Top](#table-of-contents)  

Keep your group decluttered by managing blue text messages:  

- `/cleanblue <on/off>`: Enable or disable cleaning of blue text.  
- `/ignoreblue <word>`: Exclude specific words from being cleaned.  
- `/unignoreblue <word>`: Re-enable cleaning for specific words.  
- `/listblue`: List all currently ignored words.  

---  

## 🔗 Connection Commands  

[🔝 Back to Top](#table-of-contents)  

Connect to another chat’s database to manage shared notes and filters:  

- `/connect`: Establish a connection to another chat.  
- `/connection`: Display the list of connected chats.  
- `/disconnect`: End a connection with a chat.  
- `/helpconnect`: Access comprehensive command help for remote management.  

---  

## 🔦 Filter Commands  

[🔝 Back to Top](#table-of-contents)  

Set automated responses when certain keywords are triggered:  

- `/filters`: List all current filters.  
- **Admin Only**:  
  - `/filter <keyword> <reply>`: Create a new filter.  
  - `/stop <keyword>`: Remove an existing filter.  
- **Chat Creator Only**:  
  - `/removeallfilters`: Clear all filters in the chat.  

---  

## 🚫 Disable Commands  

[🔝 Back to Top](#table-of-contents)  

Control the activation of commands:  

- `/cmds`: Display status of active/disabled commands.  
- **Admins Only**:  
  - `/enable <command>`: Enable a previously disabled command.  
  - `/disable <command>`: Disable a command.  
  - `/enablemodule <module>`: Enable all commands in a module.  
  - `/disablemodule <module>`: Disable all commands in a module.  
  - `/listcmds`: Show all toggleable commands.  

---  

## 🛠 Developer Commands  

[🔝 Back to Top](#table-of-contents)  

A set of advanced commands for developers and bot maintainers:  

- `/sudolist`: List all sudo users.  
- `/supportlist`: Display all support users.  
- `/ping`: Test bot's response time.  
- **Broadcast (Bot Owner Only)**:  
  - `/broadcastusers`: Send a message to all users.  
  - `/broadcastgroups`: Send a message to all groups.  

---  

## 📊 Eval Commands  

[🔝 Back to Top](#table-of-contents)  

Owner-exclusive set of commands for advanced operations:  

- `/eval`: Evaluate code snippets directly in the bot environment.  
- `/ex`: Execute a system command.  
- `/clear`: Clear the result of executed commands.  
- `/unbanall`: Remove bans on all users.  
- `/unmuteall`: Unmute all users.  
- `/users`: List members in current group.  

---  

## 🌐 Federation Commands  

[🔝 Back to Top](#table-of-contents)  

Impose bans across multiple groups with federations:  

- `/fedownerhelp`: Guidance for Federation Owners.  
- `/fedadminhelp`: Assistance for Federation Administrators.  
- `/feduserhelp`: Information for general Federation Users.  
  
---  

## 🚱 Flood Control  

[🔝 Back to Top](#table-of-contents)  

Configure how the bot handles message flooding:  

- `/flood`: View current flood control settings.  
- **Admin Only**:  
  - `/setflood <int/'no'/'off'>`: Define message limits or disable flood control.  
  - `/setfloodmode <action> <value>`: Choose the action when limits are exceeded (e.g., `ban`, `kick`, `mute`).  

---  

## 📢 Force Subscribe  

[🔝 Back to Top](#table-of-contents)  

Ensure new users subscribe to your designated channel:  

- `/fsub <channel>`: Enable and configure forced subscriptions.  
- `/fsub off`: Disable forced subscription requirement.  

---  

## 🔒 Lock Commands  

[🔝 Back to Top](#table-of-contents)  

Control what types of messages can be shared in the group:  

- `/locktypes`: Get a list of all lockable content types.  
- **Admin Only**:  
  - `/lock <type>`: Prevent sending a specific message type.  
  - `/unlock <type>`: Allow a locked type.  
  - `/locks`: Show current locked types in the group.  

---  

## 🛑 Log Commands  

[🔝 Back to Top](#table-of-contents)  

Enable logging for monitoring group activities:  

- **Admin Only**:  
  - `/logchannel`: Get information about current log channel.  
  - `/setlog`: Assign a channel for logs.  
  - `/unsetlog`: Remove the logging channel setup.  

---  

## 🔕 Mute Commands  

[🔝 Back to Top](#table-of-contents)  

Control who can speak in the group:  

- **Admin Only**:  
  - `/mute <user>`: Mute a specific user.  
  - `/tmute <user> <time>`: Temporarily mute a user.  
  - `/unmute <user>`: Unmute a user previously muted.  

---  

## 🌙 Night Mode Commands  

[🔝 Back to Top](#table-of-contents)  

Automate group management during night hours:  

- **Admins Only**:  
  - `/nightmode`: Add group to night mode.  
  - `/rmnight`: Remove group from night mode.  

---  

## 🗒 Notes Commands  

[🔝 Back to Top](#table-of-contents)  

Facilitate group communication with notes:  

- Retrieve and list actions:  
  - `/get <note>`: Retrieve a pre-saved note.  
  - `/notes`: List all saved notes.  
- **Admins Only**:  
  - `/save <note> <data>`: Save a new note.  
  - `/clear <note>`: Delete a specific note.  
  - `/removeallnotes`: Delete all notes.  

---  

## 📣 Tag All Commands  

[🔝 Back to Top](#table-of-contents)  

For emergency messaging to all group members:  

- **Only for admins**:  
  - `/tagall` or `@all`: Tag every member in the group.  

---  

## ⚠️ Warn Commands  

[🔝 Back to Top](#table-of-contents)  

Manage user behavior with automated warnings:  

- `/warns <user>`: View number of warnings a user has.  
- `/warnlist`: Current list of warning triggers.  
- **Admins Only**:  
  - `/warn <user>`: Issue a warning to a user.  
  - `/resetwarn <user>`: Reset warning count to zero.  
  - `/addwarn <keyword> <reply>`: Add a keyword trigger for warnings.  
  - `/nowarn <keyword>`: Remove a warning trigger.  
  - `/warnlimit <num>`: Set a maximum number of warnings before action is taken.  
  - `/strongwarn <on/off>`: Toggle severe actions for warning breaches.  

---  

## 👋 Welcome Commands  

[🔝 Back to Top](#table-of-contents)  

Craft your group's first impression with custom welcome messages:  

- Toggle and display options:  
  - `/welcome <on/off>`: Turn welcome messages on or off.  
  - `/welcome`: Show current welcome configuration.  
- **Setting Custom Messages**:  
  - `/setwelcome <text>`: Set a custom welcome message.  
  - `/setgoodbye <text>`: Set a custom goodbye message.  
  - `/resetwelcome`: Revert to default welcome message.  
  - `/resetgoodbye`: Return to default goodbye settings.  
  - `/cleanwelcome <on/off>`: Manage older welcome messages for clutter reduction.  

---  

## 👻 Zombie Commands  

[🔝 Back to Top](#table-of-contents)  

Quickly identify and remove inactive accounts:  

- `/zombies`: Identify accounts that are deleted or inactive.  
- `/zombies clean`: Remove all identified inactive accounts from the group.  

---  

## 📜 Categories and Quick Links  

[🔝 Back to Top](#table-of-contents)  

Navigate through these commands effortlessly using the bot interface buttons:  

- 🖱️ **Modules**: Click specific module buttons to view command details.  
- 🔄 **Help Back**: Use the back button to navigate back or explore different modules.  

For further inquiries, contact our support team or reach out to special group members using commands like `/devs` for developers or `/supportlist` for supporters.  

*Tip: Frequently update the bot's version for new features and enhanced security!*  

Thank you for choosing Quantum Bot and Baba, ensuring smooth and enjoyable group management! 🎉
