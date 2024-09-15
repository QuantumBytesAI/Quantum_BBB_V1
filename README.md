# babav1
Sure! Here's a clear and structured guide for your Telegram functions:

---

## Admin Commands

### Pinning Messages
- **/pin**: Silently pins the message replied to. Add `'loud'` or `'notify'` to notify users.
- **/unpin**: Unpins the currently pinned message.

### Group Management
- **/invitelink**: Gets the invite link for the group.
- **/setgtitle <text>**: Sets the group title.
- **/setgpic**: Reply to an image to set it as the group photo.
- **/setdesc**: Sets the group description.
- **/setsticker**: Sets the group sticker.

### Admin Management
- **/promote**: Promotes the user replied to.
- **/lowpromote**: Promotes the user replied to with limited rights.
- **/fullpromote**: Promotes the user replied to with full rights.
- **/demote**: Demotes the user replied to.
- **/title <title here>**: Sets a custom title for an admin promoted by the bot.
- **/admincache**: Force refreshes the admins list.

### Message Management
- **/del**: Deletes the message you replied to.
- **/purge**: Deletes all messages between this and the replied-to message.
- **/purge <integer X>**: Deletes the replied message and X messages following it.
- **/spurge**: Deletes all messages between this and the replied-to message.

---

## Approval Commands

### Approving Users
- **/approval**: Checks a user's approval status in this chat.
- **/approve**: Approves a user, exempting them from locks, blacklists, and antiflood.
- **/unapprove**: Unapproves a user, subjecting them to locks, blacklists, and antiflood again.
- **/approved**: Lists all approved users.
- **/unapproveall**: Unapproves all users in a chat (cannot be undone).

---

## Ban Commands

### User Management
- **/kickme**: Kicks the user who issued the command.

### Admin Only
- **/ban <userhandle>**: Bans a user (via handle or reply).
- **/sban <userhandle>**: Silently bans a user, deleting the command and replied message without replying.
- **/tban <userhandle> x(m/h/d)**: Bans a user for `x` time (minutes, hours, days).
- **/unban <userhandle>**: Unbans a user (via handle or reply).
- **/kick <userhandle>**: Kicks a user out of the group (via handle or reply).

---

## Blacklist Commands

### Managing Blacklists
- **/blacklist**: View the current blacklisted words.

### Admin Only
- **/addblacklist <triggers>**: Adds a trigger to the blacklist. Each line is considered one trigger.
- **/unblacklist <triggers>**: Removes triggers from the blacklist. Each line is considered one trigger.
- **/blacklistmode <off/del/warn/ban/kick/mute/tban/tmute>**: Sets the action to perform when someone sends blacklisted words.

---

## Blue Text Cleaner

### Cleaning Commands
- **/cleanblue <on/off/yes/no>**: Cleans commands after sending.
- **/ignoreblue <word>**: Prevents auto-cleaning of the command.
- **/unignoreblue <word>**: Removes the prevention of auto-cleaning of the command.
- **/listblue**: Lists currently whitelisted commands.

---

## Connection Commands

### Managing Connections
- **/connect**: Connects to chat (can be done in a group by /connect or /connect <chat ID> in PM).
- **/connection**: Lists connected chats.
- **/disconnect**: Disconnects from a chat.
- **/helpconnect**: Lists available commands that can be used remotely.

### Admin Only
- **/allowconnect <yes/no>**: Allows a user to connect to a chat.

---

## Filter Commands

### Managing Filters
- **/filters**: Lists all active filters saved in the chat.

### Admin Only
- **/filter <keyword> <reply message>**: Adds a filter to this chat. The bot will reply with the message whenever the keyword is mentioned.
- **/stop <filter keyword>**: Stops that filter.
- **/removeallfilters**: Removes all chat filters at once.

---

## Disable Commands

### Checking and Managing Commands
- **/cmds**: Checks the current status of disabled commands.

### Admin Only
- **/enable <cmd name>**: Enables that command.
- **/disable <cmd name>**: Disables that command.
- **/enablemodule <module name>**: Enables all commands in that module.
- **/disablemodule <module name>**: Disables all commands in that module.
- **/listcmds**: Lists all possible toggleable commands.

---

## Developer Commands

### Special Access Commands
- **/sudolist**: Lists all special users.
- **/supportlist**: Lists all support users.
- **/tigers**: Lists all tiger users.
- **/wolves**: Lists all wolf users.
- **/devlist**: Lists all developer users.
- **/snipe <chatID> <string>**: Sends a message to a specific chat.

### Ping and Broadcast
- **/ping**: Gets the ping time of the bot to the Telegram server.
- **/broadcastusers or /buser**: Broadcasts to all users.
- **/broadcastgroups or /bchat**: Broadcasts to all groups.

---

## Evaluation Commands

### Owner Commands
- **/eval**: Evaluates simple code.
- **/ex**: Executes code.
- **/clear**: Runs clear command.
- **/unbanall**: Unbans all members.
- **/unmuteall**: Unmutes all members.
- **/users**: Gets the group users list.

---

## Federation Commands

### Managing Federations
- **/fedownerhelp**: Provides help for federation creation and owner-only commands.
- **/fedadminhelp**: Provides help for federation administration commands.
- **/feduserhelp**: Provides help for commands anyone can use.

---

I hope this helps! Let me know if you need any more assistance. 😊
