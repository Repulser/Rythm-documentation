---
id: commands
title: Commands
---

:::info Note
### Always remember the following!
- The default prefix of Rythm is `!`. If you have changed your prefix to something else, please use your prefix instead of `!`. If you forget your prefix, mention Rythm (`@Rythm#3722`). 
- **Never include `<>` in your messages when using a command!**
- Time can be in different formats
   + Example: `100`, `1:50`, `2m30s`
:::

## Song
---
<!-- Song-related commands -->
- **`!join`** - Summons the bot to the voice channel you are in.
    - **Aliases:** `summon`, `fuckon`
--- 
- **`!play`** - Plays a song with the given name or url. [More Info](/play_song)
    - **Usage:** `!play <link/query>` 
    - **Alias:** `p`
---
- **`!playtop`** - Plays a song with the given name/url, but queues the song from the top.
    - **Usage:** `!playtop <link/query>`
    - **Aliases:** `pt`, `ptop`
--- 
- **`!playskip`** - Skips the current song and plays the song you requested.
    - **Usage:** `!playskip <link/query>`
    - **Aliases:** `ps`, `pskip`, `playnow`, `pn`
--- 
- **`!search`** - Searches YouTube for results of a URL.
    - **Usage:** `!search <query>`
    - **Alias:** `find`
--- 
- **`!soundcloud`** - Searches SoundCloud for a song.
    - **Usage:** `!soundcloud <link/query>`
    - **Alias:** `sc`
--- 
- **`!nowplaying`** - Shows what song the bot is currently playing.
    - **Alias:** `np`
--- 
- **`!grab`** - Saves the current playing song to your Direct Messages.
    - **Aliases:** `save`, `yoink`
---
- **`!seek`** - Seeks to a certain point in the current track.
    - **Usage:** `!seek <time>`
--- 
- **`!rewind`** - Rewinds by a certain amount of time in the current track. 
    - **Usage:** `!rewind <time>`
    - **Alias:** `rwd`
--- 
- **`!forward`** - Forwards by a certain amount of time in the current track.
    - **Usage:** `!forward <time>`
    - **Alias:** `fwd`
--- 
- **`!replay`** - Resets the progress of the current song.
--- 
- **`!loop`** - Toggles looping for the current playing song.
    - **Alias:** `repeat`
--- 
- **`!skip`** - Votes to skip the currently playing song. **[More Info](/faq#how-many-votes-are-required-for-a-song-to-be-vote-skipped)**
    - **Other Usage:** `!skip <number>` - Skip a certain amount of songs.
    - **Alias:** `voteskip`, `next`, `s`
--- 
- **`!forceskip`** - Skips the currently playing song immediately.
    - **Other Usage:** `!forceskip <number>` - Skip a certain amount of songs.
    - **Aliases:** `fs`, `fskip`
--- 
- **`!pause`** - Pauses the currently playing track. 
    - **Alias:** `stop`
--- 
- **`!resume`** - Resumes paused music.
    - **Aliases:** `re`, `res`, `continue`
--- 
- **`!lyrics`** - Gets the lyrics of the current playing song.
    - **Other Usage:** `!lyrics <song name>` - Gets the lyrics of the mentioned song.
    - **Aliases:** `l`, `ly`
--- 
- **`!disconnect`** - Disconnects the bot from the voice channel it is in.
    - **Aliases:** `dc`, `leave`, `dis`, `fuckoff`
---

## Queue
---
- **`!queue`** - Shows the first page of the queue. 
    - **Other Usage:** `!queue <page>`: Shows the specified page number.
    - **Alias:** `q`
--- 
- **`!loopqueue`** - Toggles looping for the whole queue.
    - **Aliases:** `qloop`, `lq`, `queueloop`
--- 
- **`!move`** - Moves a certain song to a chosen position in the queue. 
    - **Usage:** `!move <old positon> <new position>` (**Note:** If the new position is not specified, the song will be moved to the first position of the queue)
    - **Aliases:** `m`, `mv`
--- 
- **`!skipto`** - Skips to a certain position in the queue. 
    - **Usage:** `!skipto <position>`
    - **Alias:** `st`
--- 
- **`!shuffle`** -  Shuffles the entire queue.
    - **Alias:** `random`
--- 
- **`!remove`** - Removes a certain entry from the queue.
    - **Usage:** `!remove <numbers>`
    - **Alias:** `rm`
---
- **`!clear`** - Clears the whole queue. 
    - **Other Usage:** `!clear <@user>` - Clears all songs requested by the mentioned user.
    - **Alias:** `cl`
--- 
- **`!leavecleanup`** - Removes absent user's songs from the queue.
    - **Alias:** `lc`
---
- **`!removedupes`** - Removes duplicate songs from the queue.
    - **Aliases:** `rmd`, `rd`, `drm`
---

## koodos
---
- **`!sotd`** - Shows the song of the day. [More Info](/features#koodos-integration)
---
- **`!playsotd`** - Queue the song of the day.
    - **Alias:** `psotd`
---
- **`!sotw`** - Shows the songs of the week. [More Info](/features#koodos-integration)
---
- **`!playsotw`** - Queue the songs of the week.
    - **Alias:** `psotw`
---
- **`!sotm`** - Shows the songs of the month. [More Info](/features#koodos-integration)
---
- **`!playsotm`** - Queue the songs of the months.
    - **Alias:** `psotm`
---

## Settings
---
- **`!settings`** - Use the command format `!settings <option>` to view more info about an option. [More Info](/settings)

    - **`prefix`** - Changes Rythm's prefix. [More Info](/settings#prefix)
    - **`announcesongs`** - Allows the bot to announce every new song playing. [More Info](/settings#announce-songs)
    - **`preventduplicates`** - Prevents users from adding songs to the queue that are already in the queue. [More Info](/settings#duplicate-song-preventation)
    - **`blacklist`** - Allows you to blacklist channels you **don't** want Rythm to respond in. [More Info](/settings#blacklist)
    - **`maxqueuelength`** - Limits how many songs the queue can store. [More Info](/settings#max-queue-length)
    - **`maxusersongs`** - Limits how many songs the user can queue at one time. [More Info](/settings#max-user-songs)
    - **`djonly`** - Sets the server to run in DJ only mode. [More Info](/settings#dj-only-mode)
    - **`djrole`** - Changes which role is considered DJ. Roles named `DJ` will still work. [More Info](/settings#dj-role)
    - **`djplaylists`** - Allows only DJs to queue playlists. [More Info](/settings#dj-only-playlists)
    - **`defaultvolume`** - Sets the default volume that the bot will always start at. [**Donator Only**](https://rythmbot.co/donate?do). [More Info](/settings#default-volume)
    - **`autoplay`** - Toggles auto-playing songs from playlist when nothing else playing. [**Donator Only**](https://rythmbot.co/donate?do). [More Info](/settings#autoplay)
    - **`reset`** - Resets Rythm totally. [More Info](/settings#reset)
---

## [Donators](https://rythmbot.co/donate?do)
---
- **`!donate`** - Information about donating to Rythm.
    - **Alias:** `patreon`
--- 
- **`!effects`** - Shows current audio effects.  [**Donator Only**](https://rythmbot.co/donate?do)
    - **Other Usages**:
        - `!effects help` - Shows all available audio effects.
        - `!effects clear` - Clears all audio effects.
    - **Alias:** `effect`
---
- **`!speed`** - Modifies the playback speed.  [**Donator Only**](https://rythmbot.co/donate?do)
---
- **`!bass`** - Bass boosts the current song.  [**Donator Only**](https://rythmbot.co/donate?do)
---
- **`!nightcore`** - Toggles nightcore effect.  [**Donator Only**](https://rythmbot.co/donate?do)
---
- **`!slowed`** - Toggles slowed effect.  [**Donator Only**](https://rythmbot.co/donate?do)
---
- **`!volume`** - Outputs the current volume.   [**Donator Only**](https://rythmbot.co/donate?do)
    - **Other Usage:** `!volume <amount>` - Changes the current volume. (**Allowed Value:** `1-200`)
    - **Alias:** `vol`
---

## Others
---
- **`!prune`** - Deletes the bot's messages and commands.
    - **Aliases:** `purge`, `clean`
--- 
- **`!invite`** - Shows Rythm's official links! 
    - **Alias:** `links`
--- 
- **`!info`** - Shows information about Rythm!
--- 
- **`!shard`** - Checks the server shard you are in.
    - **Alias:** `debug`
--- 
- **`!ping`** - Checks the bot's response time to Discord.
---
- **`!aliases`** - Lists command aliases.
--- 
