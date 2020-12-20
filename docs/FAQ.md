---
id: faq
title: Frequently Asked Questions
---



<!-- The start of the Introduction Section -->
## Introduction
-----
### What is Rythm Bot?
[Rythm](/start) is a feature-rich, high-performance music bot for Discord, specially designed to deliver High Quality music, stability and ease of use while also providing advanced music functionality in order to create the ultimate music bot experience.

### How can I add Rythm to my Discord Server?
Please [click here](/adding_rythm) to check out our guide on adding Rythm.

### What are the differences among Rythm, Rythm 2 and Rythm Canary?
You can check out the differences on our [releases page](https://rythmbot.co/releases).

<!-- The end of the Introduction Section -->

<!-- The start of the Basic Information Section -->
## Basic Information
-----

### I don't know Rythm's prefix. What should I do?
If you don't know or forget Rythm's prefix, don't stress. We have you covered. You can view the prefix simply by mentioning the bot.

:::tip
The default prefix of Rythm is `!`, Rythm 2 is `>`, Rythm Canary is `*`.
:::

1. For Rythm:
    + **Example:** `@Rythm#3722` or `<@235088799074484224>`

![MentionPrefix](/img/docs/faq/rythm-1.png)

2. For Rythm 2:
    + **Example:** `@Rythm 2#2000` or `<@252128902418268161>`

![MentionPrefix2](/img/docs/faq/rythm-2.png)

3. For Rythm Canary:
    + **Example:** `@Rythm Canary#8406` or `<@415062217596076033>`

![MentionPrefixC](/img/docs/faq/rythm-c.png)

You can also use mention as a prefix!

![MentionAsPrefix](/img/docs/faq/mention-as-prefix.png)

### How can I change/reset Rythm's prefix in my server?
Head to the [Prefix Settings](/settings#prefix) section to learn more.

### How can I change Rythm's nickname in my server?
1. Make sure you have the `Manage Nickname` permission.
2. Then you will have to **Right Click** Rythm's name and press `Change Nickname`
3. A menu will pop up looking like this:

![NicknameMenu](/img/docs/faq/nickname-menu.png)

4. Type in your desired nickname.
5. Finally you can press `Save` and you're good to go.

### What do the 3 emojis in `!ping` mean?
    ⌛ - API response time   
    ⏱️ - Message response time
    💓 - Websocket heartbeat

### Why can some normal users access moderative music commands?
1. Normal users with no special permissions are only allowed to use the `!play` command to add songs to the queue and the `!remove` command to remove their own songs in the queue.
   They can also use other commands that don't affect the playing music or the queue in any way. Example: `!queue`, `!lyrics`, `!save`.
2. However, normal users can access ALL music commands when they are alone with Rythm in the voice channel.
   This is because their commands would not affect anyone but themselves.
  - For more information about users command permissions, refer to the **[Understanding Permissions](/permissions)** section in this documentation.

### How can I donate to Support Rythm?
Do you ❤️ Rythm? You can donate to us today by [clicking here](https://rythmbot.co/donate?do)!
  - You will get awesome perks such as **Volume control**, **Audio Effects**, **Playing songs longer than 3 hours**, **Roles in our Discord server** and more!

<!-- The end of the Basic Information Section -->

<!-- The start of the Limitations/Restrictions Section -->
## Limitations/Restrictions
-----
### Can I have more than one Rythm in the same server?
Yes! You can invite up to 3 releases by [clicking here](https://rythmbot.co/releases).

### Can I change Rythm's Profile Picture/Avatar in my server?
No, Discord does not allow bots to change their profile picture/avatar per server.

### Can I save or create playlists with Rythm?
No, unfortunately Rythm doesn't have a built-in feature to store playlists. But wait, there are a few solutions to this:
  - You can do `!grab` to save the current playing song into Rythm's direct messages.
  - You can save playlists from supported music sites and play them through Rythm. (See List of supported music sites below)

### What music sites does Rythm currently support?
These are the current sites that music can be played from.

1. [YouTube](https://www.youtube.com/)
2. [SoundCloud](https://www.soundcloud.com/)
3. [Twitch](https://www.twitch.tv/)
4. [Vimeo](https://www.vimeo.com/)
5. [BandCamp](https://www.bandcamp.com)
6. [Spotify](https://www.spotify.com/)

### How is it possible for Rythm to play music from Spotify?
Rythm finds the songs from Youtube and plays them.

You can play Spotify song/playlist through Rythm by just simply doing `!play <Song/Playlist url>`!

### Can I adjust the volume for everyone on my server for Rythm?
Yes, if you [donate](https://rythmbot.co/donate?do).

Rythm uses the default volume when using audio streams. In order to change the volume of these audio streams we need to enable encoding. As encoding requires a lot of computing resources, only donators can access this feature.

You may set the local volume of Rythm for yourself:
1. If you are on PC, you can right-click Rythm in the voice channel and adjust the user volume slider as shown below.

![VolumeMenu](/img/docs/faq/user-volume.png)

2. If you are on phone, click on the channel you are in then click on the user. A bar will appear at the bottom with their name and role, scroll down and you will see the option to change user volume.

![PhoneVolumeMenu](/img/docs/faq/phone-user-volume.png)

#### [Donators](https://rythmbot.co/donate?do)
For donators, the volume command is `!volume <1-200>`.

- **Example:** `!volume 80`

### Can I make custom commands for Rythm?
No, we do not allow custom commands/aliases. To check available aliases, just run the command `!aliases`.
You can suggest any aliases that you can think of in the [#rythm-suggestions](https://discord.com/channels/231471142685245440/679554693403639835) channel on the [Rythm Bot Discord server](https://rythmbot.co/support).

### Can Rythm stream the video of the song that is being played?
No, Discord does not allow bots to use the `Go Live` feature.

### How is it possible for Rythm to be in so many servers all in once?
Discord allows bots in over `2,000` servers to use a feature called `Sharding`.
In Rythm's case, we are known as the largest music bot on Discord, so we require lots of shards to maintain uptime.
For more detail, please [click here](https://discord.com/developers/docs/topics/gateway#sharding) to view more about Discord's Sharding feature.

### Can Rythm play 24/7 Music?
No, Rythm is not a 24/7 music bot.
The reason behind this decision is because music bots require a lot of resources.
Therefore, when the bot is by itself, and not being used by anyone, these resources are still in use, leaving less availability for other people.
If you do want a bot that plays music 24/7, you can host one with [Moosic](https://github.com/Repulser/Moosic).
Instructions on how to host this is on [Moosic's wiki](https://github.com/Repulser/Moosic/wiki).

### Can Rythm execute commands given by other bots?
No, Rythm doesn't respond to commands issued by other bots as it can be easily abused. This restriction will not be removed, nor will any exceptions be made.

## Rythm Links
-----
### I have encountered an issue with Rythm!
Encounter freaky issues? You can use the links below to help you fix any of those issues:
+ [Basic Troubleshooting](/basic_troubleshooting)
+ [Audio Troubleshooting](/audio_troubleshooting)
+ [Mobile Troubleshooting](/mobile_troubleshooting)

### None of these solutions solved my problem!
If you couldn't find an answer to your question in either this FAQ or in the troubleshooting pages, please go to [Get Support](/get_support) section for further support.

### What is Rythm's Discord Server used for?
Rythm's Discord Server is a place built for everything related to Rythm!
1. Get help and support from our lovely Support Members!
2. You will be informed about Rythm's new features and updates.
3. Stay Up-to-Date with news and announcements.
4. Hang out with our amazing growing community members and staff!
5. Join and enjoy our events that take place!
6. Make new feature suggestions for Rythm.

To join our server, click [here](https://rythmbot.co/support).
