---
id: commands
title: Commands
---

:::info Note
### Always remember the following!
- The default prefix of Rythm is `;;`. If you have changed your prefix to something else, please use your prefix instead of `;;`. If you forget your prefix, mention Rythm (`@Rythm#3722`).
- **Never include `<>` in your messages when using a command!**
- Time can be in different formats
   + Example: `100`, `1:50`, `2m30s`
:::

## Song
---
<!-- Song-related commands -->
- **`;;join`** - Summons the bot to the voice channel you are in.
    - **Aliases:** `summon`
---
- **`;;play`** - Plays a song with the given name or url. [**More Info**](/play_song)
    - **Usage:** `;;play <link/query>`
    - **Alias:** `p`
---
- **`;;playtop`** - Adds a song with the given name/url __on the top of the queue__.
    - **Usage:** `;;playtop <link/query>`
    - **Aliases:** `pt`, `ptop`
---
- **`;;playskip`** - Skips the current song and plays the song you requested.
    - **Usage:** `;;playskip <link/query>`
    - **Aliases:** `ps`, `pskip`, `playnow`, `pn`
---
- **`;;search`** - Searches from [Youtube](https://www.youtube.com) for a song via your query and returns the top 10 results.
    - **Usage:** `;;search <query>`
    - **Alias:** `find`
---
- **`;;soundcloud`** - Plays a song from [SoundCloud](https://www.soundcloud.com)  with the given name/url
    - **Usage:** `;;soundcloud <link/query>`
    - **Alias:** `sc`
---
- **`;;nowplaying`** - Shows what song Rythm is currently playing.
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
- **`!voteskip`** - Votes to skip the current playing song. **[More Info](/voteskip#how-many-votes-are-required-for-a-song-to-be-vote-skipped)**
    - **Alias:** `skip`, `next`, `s`
---
- **`!forceskip`** - Skips the current playing song immediately.
    - **Other Usage:** `!forceskip <number>` - Skip a certain amount of songs.
    - **Aliases:** `fs`, `fskip`
    - **Note:** `DJ` role/`Manage Channels` permission required.
---
- **`!pause`** - Pauses the current playing track.
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
    - **Aliases:** `dc`, `leave`, `dis`
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
    - **Usage:** `!move <old positon> <new position>`
    - **Aliases:** `m`, `mv`
    - **Note:** If the `<new position>` is not specified, the song will be moved to the first position of the queue
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
- **`!sotd`** - Shows the song of the day. [More Info](/koodos#song-of-the-day)
---
- **`!playsotd`** - Queue the song of the day.
    - **Alias:** `psotd`
---
- **`!sotw`** - Shows the songs of the week. [More Info](/koodos#song-of-the-week)
---
- **`!playsotw`** - Queue the songs of the week.
    - **Alias:** `psotw`
---
- **`!sotm`** - Shows the songs of the month. [More Info](/koodos#song-of-the-month)
---
- **`!playsotm`** - Queue the songs of the month.
    - **Alias:** `psotm`
---

## Settings
---
- **`!settings`** - Use the command format `!settings <option>` to view more info about an option. [More Info](/settings)
    - **Alias:** `setting`
    - **List of options:**
      - [**`prefix`**](/settings#prefix) - Changes Rythm's prefix.
      - [**`announcesongs`**](/settings#announce-songs) - Allows the bot to announce every new song playing.
      - [**`preventduplicates`**](/settings#duplicate-song-prevention) - Prevents users from adding songs to the queue that are already in the queue.
      - [**`blacklist`**](/settings#blacklist)- Allows you to blacklist channels you **don't** want Rythm to respond in.
      - [**`maxqueuelength`**](/settings#max-queue-length) - Limits how many songs the queue can store.
      - [**`maxusersongs`**](/settings#max-user-songs) - Limits how many songs the user can queue at one time.
      - [**`djonly`**](/settings#dj-only-mode) - Sets the server to run in DJ only mode.
      - [**`djrole`**](/settings#dj-role) - Changes which role is considered DJ. Roles named `DJ` will still work.
      - [**`djplaylists`**](/settings#dj-only-playlists) - Allows only DJs to queue playlists.
      - [**`reset`**](/settings#reset) - Resets all Rythm settings.
    - **[Premium Only](https://rythm.fm/premium):**
      - [**`defaultvolume`**](/settings#default-volume) - Sets the default volume that the bot will always start at.
      - [**`autoplay`**](/settings#autoplay) - Toggles auto-playing songs from playlist when nothing else playing.
      - [**`alwaysplaying`**](/settings#always-playing) - Sets Rythm to stay in your voice channel 24/7.



---

## [Premium](https://rythm.fm/premium)
---
- **`!effects`** - Shows current audio effects.  [**Premium Only**](https://rythm.fm/premium?do)
    - **Other Usages**:
        - `!effects help` - Shows all available audio effects.
        - `!effects clear` - Clears all audio effects.
    - **Alias:** `effect`
---
- **`!speed`** - Shows information about the current speed effect.  [**Premium Only**](https://rythm.fm/premium?do)
    - **Other Usage**: `!speed <0.1 - 3>` - Modifies the playback speed.
---
- **`!bass`** - Shows information about the current bass-boost effect.  [**Premium Only**](https://rythm.fm/premium?do)
    - **Other Usage**: `!bass <1 - 5>` - Bass-boosts the current song.
---
- **`!nightcore`** - Toggles nightcore effect.  [**Premium Only**](https://rythm.fm/premium?do)
---
- **`!slowed`** - Toggles slowed effect.  [**Premium Only**](https://rythm.fm/premium?do)
---
- **`!volume`** - Outputs the current volume.   [**Premium Only**](https://rythm.fm/premium?do)
    - **Other Usage:** `!volume <1-200>` - Changes the current volume.
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
- **`!shard`** - Checks the server shard your server is in.
    - **Alias:** `debug`
---
- **`!ping`** - Checks the bot's response time to Discord.
---
- **`!aliases`** - Lists all command aliases.
---
