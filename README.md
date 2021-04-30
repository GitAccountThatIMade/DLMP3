# DLMP3 Bot (Discord.JS Local MP3)
A Discord bot that plays local mp3 audio tracks. Written in Discord.JS.

[Video Tutorial](https://www.youtube.com/watch?v=7X3FAhYW31I)

Forked from https://github.com/Alee14/DLMP3

# Configuration
Make a new file called `config.json`.
```
{
    "token": "token_here",
    "prefix": "dl:",
    "botOwner": "your_user_id_here",
    "statusChannel": "channel_id",
    "voiceChannel": "voice_channel_id"
}
```

Add your own audio files using the mp3 file extension to the `music` folder.

Launch the bot using `node bot.js` in terminal.

# Help Command
```
Public Only
-----------
help - Displays commands.
playing - Tells you what it's playing at the moment.
about - About the bot.
resume - Resumes music.
pause - Pauses music.
skip - Skips the audio track.

Bot Owner Only
--------------
join - Joins voice chat.
leave - Leaves voice chat.
stop - Stops bot.
```
