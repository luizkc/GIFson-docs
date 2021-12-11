# [GIFson](https://discord.com/oauth2/authorize?client_id=918004394337906738&permissions=0&scope=bot%20applications.commands)

A GIFs only conversation in your Discord server. Click [here](https://discord.com/oauth2/authorize?client_id=918004394337906738&permissions=0&scope=bot%20applications.commands) to invite GIFson to your server.

# Commands

## `!set-gif-channel <channel>`

Use this command to select a channel to be a GIFs only channel. The bot will detect messages in this channel and delete all non GIF messages. The bot will also reply to the user and will let them know they can only send GIFs in the channel.

Alternatively, you may use the `!add-gif <GIF URL>` command to set GIFs that the bot will reply with instead.

This command will not work if the argument passed to it is not a channel mention.

**Note:** The bot only replies if the message sent _is not_ a GIF. Otherwise, it will react to the message with a ✅.

### Example Usage

`!set-gif-channel #my-channel`

## `!remove-gif-channel`

This command will make your GIFs only channel a normal channel again. This command will only work if you have a GIFs only channel set.

### Example Usage

`!remove-gif-channel`

## `!add-gif <GIF URL>`

This command lets you add a GIF that the bot will use to reply to non GIF messages in you GIFs only channel. The bot will choose randomly from one of the added GIFs that are saved in your guild's database entry.

### Example Usage

`!add-gif https://media0.giphy.com/media/gjxBlCDjiyEbb60sFZ/giphy.mp4`

## `!delete-gif <GIF URL>`

This command lets you remove a GIF you previously added from your guild's database entry. This GIF will be deleted from your guild's database entry and the bot will no longer use it to reply to non GIF messages in your GIFs only channel.

### Example Usage

`!delete-gif https://media0.giphy.com/media/gjxBlCDjiyEbb60sFZ/giphy.mp4`

# Issues/Features

Report bugs or request features to `lu#7819`.
