---
id: commands
title: Commands

## Song
--
<!-- Song-related commands -->
- **`!join`** - Summons the bot to the voice channel you are in.
---
- **`!play`** - Plays a song with the given name or url.
- 
- **`!playtop`** - Adds a song with the given name/url __on the top of the queue__.

- **`!playskip`** - Skips the current song and plays the song you requested.

- **`!search`** - Searches from [Youtube](https://www.youtube.com) for a song via your query and returns the top 10 results.

- **`!soundcloud`** - Plays a song from [SoundCloud](https://www.soundcloud.com)  with the given name/url

- **`!nowplaying`** - Shows what song Rythm is currently playing.

- **`!grab`** - Saves the current playing song to your Direct Messages.

- **`!seek`** - Seeks to a certain point in the current track.

- **`!rewind`** - Rewinds by a certain amount of time in the current track.

- **`!forward`** - Forwards by a certain amount of time in the current track.

- **`!replay`** - Resets the progress of the current song.

- **`!loop`** - Toggles looping for the current playing song.

- **`!voteskip`** - Votes to skip the current playing song. **[More Info](/voteskip#how-many-votes-are-required-for-a-song-to-be-vote-skipped)**
    
- **`!forceskip`** - Skips the current playing song immediately.
    - **Other Usage:** `!forceskip <number>` - Skip a certain amount of songs
    - **Note:** `DJ` role/`Manage Channels` permission required
    
- **`!pause`** - Pauses the current playing track.

- **`!resume`** - Resumes paused music.
 
- **`!lyrics`** - Gets the lyrics of the current playing song.

- **`!disconnect`** - Disconnects the bot from the voice channel it is in.


## Queue
- **`!queue`** - Shows the first page of the queue.
    - **Other Usage:** `!queue <page>`: Shows the specified page number.

- **`!loopqueue`** - Toggles looping for the whole queue.

- **`!move`** - Moves a certain song to a chosen position in the queue.
    - **Usage:** `!move <old positon> <new position>`
    - **Note:** If the `<new position>` is not specified, the song will be moved to the first position of the queue

- **`!skipto`** - Skips to a certain position in the queue

- **`!shuffle`** -  Shuffles the entire queue.

- **`!remove`** - Removes a certain entry from the queue.
    - **Usage:** `!remove <numbers>`
---
- **`!clear`** - Clears the whole queue.
    - **Other Usage:** `!clear <@user>` - Clears all songs requested by the mentioned user.
    
- **`!leavecleanup`** - Removes absent user's songs from the queue.
 
- **`!removedupes`** - Removes duplicate songs from the queue.


## koodos
---
- **`!sotd`** - Shows the song of the day. [More Info](/koodos#song-of-the-day)

- **`!playsotd`** - Queue the song of the day.

- **`!sotw`** - Shows the songs of the week. [More Info](/koodos#song-of-the-week)

- **`!playsotw`** - Queue the songs of the week.

- **`!sotm`** - Shows the songs of the month. [More Info](/koodos#song-of-the-month)

- **`!playsotm`** - Queue the songs of the month.

- **`!shard`** - Checks the server shard your server is in.

- **`!aliases`** - Lists all command aliases.
