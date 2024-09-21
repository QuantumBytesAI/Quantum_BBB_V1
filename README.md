# 📖 Quantum Bot Documentation

Welcome to the comprehensive guide for Quantum Bot! This documentation is designed to help you seamlessly navigate through the wide array of features and commands that Quantum Bot offers. Whether you are an admin, a trusted user, or simply a member of a group, you’ll find all the necessary information to make the most out of Quantum Bot here.

## 🌟 Modules Overview

Quantum Bot is packed with modules suited for different needs. Each module contains specific commands tailored to perform various actions to manage and optimize your group. Here's a detailed look at each module:

---

## 👮‍♂️ Admin Commands 

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

Manage trusted users with approval commands:

- `/approval`: Check a user's approval status in the chat.
- `/approve`: Exempt a user from locks and blacklists.
- `/unapprove`: Revoke approval for a user, reapplying restrictions.
- `/approved`: List all approved users.
- `/unapproveall`: Remove approval for all users.

---

## ❌ Ban Commands

Efficiently manage who can stay in your group:

- **Self-Kick**:
  - `/kickme`: Kick yourself from the group.
- **Admin Only**:
  - `/ban <user>`: Bans a user.
  - `/sban <user>`: Silently bans a user, removes command/reply visibility.
  - `/tban <user> <time>`: Temporarily bans a user (`m` for minutes, `h` for hours, `d` for days).
  - `/unban <user>`: Lifts a ban on a user.
  - `/kick <user>`: Kicks a user from the group.
  
---

## 📝 Blacklist Commands

Automate deletion of unwanted messages:

- `/blacklist`: Shows the list of blacklisted words.
- **Admin Only**:
  - `/addblacklist <triggers>`: Add triggers to the blacklist.
  - `/unblacklist <triggers>`: Remove triggers from the blacklist.
  - `/blacklistmode <action>`: Set an action (e.g., `off`, `del`, `warn`, `ban`, etc.) when a blacklisted word is detected.

---

## ⚙️ Clean Commands

Keep your group free from unwanted blue text:

- `/cleanblue <on/off>`: Enable blue text cleaning.
- `/ignoreblue <word>`: Exclude certain words from auto-cleaning.
- `/unignoreblue <word>`: Re-enable auto-cleaning for certain words.
- `/listblue`: List currently whitelisted commands.

---

## 🔗 Connection Commands

Connect to another chat’s database to manage notes and filters:

- `/connect`: Connect to a chat.
- `/connection`: List connected chats.
- `/disconnect`: Disconnect from a chat.
- `/helpconnect`: Access remote management command list.

---

## 🔦 Filter Commands

Set automated responses based on certain keywords:

- `/filters`: Lists all active filters.
- **Admin Only**:
  - `/filter <keyword> <reply>`: Adds a filter in the chat.
  - `/stop <keyword>`: Stops a specific filter.
- **Chat Creator Only**:
  - `/removeallfilters`: Clears all filters in the chat.

---

## 🚫 Disable Commands

Manage command availability:

- `/cmds`: Check the status of disabled commands.
- **Admins Only**:
  - `/enable <command>`: Reactivate a command.
  - `/disable <command>`: Disable a specific command.
  - `/enablemodule <module>`: Reactivate all commands in a module.
  - `/disablemodule <module>`: Disable all commands in a module.
  - `/listcmds`: List all toggleable commands.

---

## 🛠 Developer Commands

Restricted to select users for advanced troubleshooting:

- `/sudolist`: Lists all sudo users.
- `/supportlist`: List all support users.
- `/ping`: Check bot ping response time.
- **Broadcast (Bot Owner Only)**:
  - `/broadcastusers`: Send a message to all users.
  - `/broadcastgroups`: Send a message to all groups.

---

## 📊 Eval Commands

Owner-only commands for technical operations:

- `/eval`: Evaluate code snippets.
- `/ex`: Execute a command.
- `/clear`: Clear executed command.
- `/unbanall`: Unban all members.
- `/unmuteall`: Unmute all members.
- `/users`: List group members.

---

## 🌐 Federation Commands

Ban users across multiple groups:

- `/fedownerhelp`: Help for Federation Owners.
- `/fedadminhelp`: Help for Federation Admins.
- `/feduserhelp`: Help for general Federation Users.
  
---

## 🚱 Flood Control

Manage flood settings:

- `/flood`: Get current flood control setting.
- **Admin Only**:
  - `/setflood <int/'no'/'off'>`: Enable or disable flood control.
  - `/setfloodmode <action> <value>`: Set action for exceeding flood limit (`ban`, `kick`, `mute`, etc.)

---

## 📢 Force Subscribe

Ensure users are subscribed to your channel:

- `/fsub <channel>`: Enable and configure force subscribe.
- `/fsub off`: Disable force subscribe.

---

## 🔒 Lock Commands

Restrict types of media and messages in your group:

- `/locktypes`: View all lockable types.
- **Admin Only**:
  - `/lock <type>`: Lock a certain type of message.
  - `/unlock <type>`: Remove a lock.
  - `/locks`: View current locks in the group.
- **Note**: Unlock permissions only for `info` and `pin`.

---

## 🛑 Log Commands

Keep track of group activities with logs:

- **Admin Only**:
  - `/logchannel`: Get log channel info.
  - `/setlog`: Set up the log channel.
  - `/unsetlog`: Remove the log channel.

---

## 🔕 Mute Commands

Prevent users from sending messages:

- **Admin Only**:
  - `/mute <user>`: Mute a user.
  - `/tmute <user> <time>`: Temporarily mute a user (`m` for minutes, `h` for hours, `d` for days).
  - `/unmute <user>`: Unmute a user.

---

## 🌙 Night Mode Commands

Automatically manage messages during night hours:

- **Admins Only**:
  - `/nightmode`: Add group to night mode.
  - `/rmnight`: Remove group from night mode.
- **Note**: Night mode closes chats at 12 AM and opens at 6 AM (IST).

---

## 🗒 Notes Commands

Manage informative messages for your group:

- Get and list notes:
  - `/get <note>`: Retrieve a specific note.
  - `/notes`: List all saved notes.
- **Admins Only**:
  - `/save <note> <data>`: Save a new note.
  - `/clear <note>`: Remove a specific note.
  - `/removeallnotes`: Clear all notes.

---

## 📣 Tag All Commands

Mention all members for important messages:

- **Only for admins**:
  - `/tagall` or `@all`: Mention all group members.

---

## ⚠️ Warn Commands

Automate warnings for rule violations:

- `/warns <user>`: View a user’s warnings.
- `/warnlist`: List of all current warning filters.
- **Admins Only**:
  - `/warn <user>`: Issue a warning.
  - `/resetwarn <user>`: Reset a user’s warnings.
  - `/addwarn <keyword> <reply>`: Set a warning filter.
  - `/nowarn <keyword>`: Stop a warning filter.
  - `/warnlimit <num>`: Set warning limit.
  - `/strongwarn <on/off>`: Decide severe actions on warning limit breach.

---

## 👋 Welcome Commands

Customize welcome messages for your group:

- Toggle and view settings:
  - `/welcome <on/off>`: Enable or disable welcome messages.
  - `/welcome`: Show current welcome settings.
- **Customize Welcome/Goodbye**:
  - `/setwelcome <text>`: Set a custom welcome message.
  - `/setgoodbye <text>`: Set a custom goodbye message.
  - `/resetwelcome`: Reset to default welcome message.
  - `/resetgoodbye`: Reset to default goodbye message.
  - `/cleanwelcome <on/off>`: Attempt to delete previous welcome messages to reduce clutter.
- **Additional Commands**:
  - `/cleanservice <on/off>`: Delete Telegram’s welcome/left messages.
  - `/welcomehelp`: Detailed info on welcome message formatting.

---

## 👻 Zombie Commands

Identify and remove inactive users:

- `/zombies`: Start searching for deleted accounts.
- `/zombies clean`: Remove deleted accounts from the group.

---

## 📜 Categories and Quick Links

We know this is a lot to take in, but don't worry! Simply use the buttons provided in the bot interface to quickly navigate between these commands and get direct help based on the category you're interested in. Here's how:

- 🖱️ **Modules**: Tap on specific module buttons to expand detailed command info.
- 🔄 **Help Back**: Tap on the back button to navigate through modules.

For any assistance, feel free to reach out to the support groups or contact a team member who's part of the special access groups, like `/devs` for Developer Commands or `/supportlist` for support users.

*Tip: Always keep your bot version up to date to enjoy the latest features and security enhancements!*

Thank you for choosing Quantum Bot, where managing your group becomes not just easy, but also fun! 🎉
