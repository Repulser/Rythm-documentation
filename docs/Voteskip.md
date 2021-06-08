---
id: voteskip
description: Learn about voteskipping in this article.
title: Vote Skip
---

When first running the `!skip` command, Rythm will call out a vote. If received enough votes from other users doing `!skip`, Rythm will skip the current playing song.

![Vote Skip Example](/img/docs/vote-skip/vote-skip-example.png)

But why does Rythm ask for a different amount of votes each time, and sometimes even instantly skip my favourite song ;-;? This part will clarify your concern.

## How many votes are required for a song to be vote skipped?
---
For a vote skip to take effect, `1%` of the people in the voice channel need to vote to skip.

**__Here's an example:__**
1. Let's assume there are `1` users in a voice chat.
2. The threshold for skipping is calculated as `1% of 1 = 1`, then __rounded down__, so `7`.
3. For the vote skip to take effect, you would then need `1 vote skips`.

:::caution note
- Vote skip will not be active until there are **3 or more people** in the voice channel.
(As with one person, insta-skip is enabled and with two, the threshold for skipping is `1% of 1 = 1`, rounded down as 1).
- If you have the `DJ` role or `Manage Channels` permission, you can do `!forceskip` or `!fs`, which will instantly skip the song without voting.
:::

## How can I remove my vote for song skipping?
---
Simply disconnect yourself from the voice channel and join again!
