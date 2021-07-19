---
id: basic_troubleshooting
title: Basic Troubleshooting
---

Encountering freaky problems? Look them up here!

### I don't know Rythm's prefix. What should I do?
If you don't know or forget Rythm's prefix, don't stress. We have you covered. You can view the prefix simply by mentioning the bot.

![MentionRythm](/img/docs/basic-troubleshooting/mention-rythm.png)

:::tip
The prefixes in the image above are the bots' default prefixes. You can learn how to change prefix [here](/settings#prefix)
:::

You can also mention Rythm as a prefix.

![MentionPrefix](/img/docs/basic-troubleshooting/mention-as-prefix.png)

Or you can use Slash commands. More information about Slash commands can be found [here](https://rythm.fm/docs/slash_commands).

![SlashCommands](/img/docs/slash-commands/slash-commands-example.png)

## Rythm won't play my playlist
Make sure the playlist is either `Unlisted` or `Public`. If it is set to `Private` Rythm won't be able to play that specific playlist.

If you recently made a private playlist public or unlisted, you should wait a short while until Rythm realizes that it is public.

## Rythm left the voice channel while not playing anything
For performance reasons, Rythm leaves after a while of being alone or unused in a voice channel.
This helps Rythm save resources while no one is listening to it and keeps the music quality consistent for all users at any given time!

Don't worry though, as long as you are in a voice channel, just type `!summon` to make Rythm rejoin your channel!

## Rythm forgets the playlist I queued after it leaves
For performance reasons, Rythm will clear/reset the queue when it leaves the voice channel.

To get around this we suggest creating a YouTube/Spotify playlist of the songs you wish to re-queue.

## Rythm sends blank messages
Rythm uses embeds to post messages. You might have disabled website previews on your client. Please make sure you enable it!

1. Go to your user settings, which is the gear in the bottom left corner.
2. Click **Text & Images**.
3. Enable **Show website preview info from links pasted into chat**.

![Embeds](/img/docs/basic-troubleshooting/embeds.png)

## Rythm isn't responding to my commands!
*If Rythm isn't responding to commands, try the following:*

### 1. Make sure Rythm is showing as online.

  - If Rythm is offline, try kicking the bot out of your server and inviting it again. If after doing that Rythm is still showing as offline, you may skip to step 4.

### 2. Make sure you're using the correct prefix.

  - You can mention Rythm to get the current prefix in your server:

  ![Mention to get prefix](/img/docs/basic-troubleshooting/prefix.png) ![Mention to get prefix 2](/img/docs/basic-troubleshooting/prefix-2.png)

  - You can learn how to change Rythm's prefix by heading to the [Prefix Setting](/settings#prefix) section!

### 3. Make sure Rythm has the permissions to read and send messages in the channel.

  - You can give the `Administrator` permission to Rythm to make this easier.

### 4. Nothing above helped!

  - First, take a look at our [#outage](https://discord.com/channels/231471142685245440/359311833653313546) channel on our [Rythm Bot Discord server](https://rythm.fm/support) to see if there are any issues going on.

  - If nothing related is there, please mention your issue in our [#help-desk](https://discord.com/channels/231471142685245440/359355279004925954) channel on the Rythm Bot Discord server to receive assistance from a member of our Support Team.

[Click here to join the official Rythm Bot Discord server](https://rythm.fm/support)

## Rythm is responding to commands but not joining the voice channel
If you find that Rythm is responding to your commands but not joining a voice channel use the following method:

1. Move to a different voice channel.
2. `!summon` the bot into that voice channel.
3. Move back to the original voice channel.
4. `!summon` the bot back into the original voice channel.

If the above method does not work, try changing the server region of your server or kicking & reinviting Rythm to your Discord server.

## I've read everything above but none fixed my issue. What do I do?

In case nothing from the list above has helped you, please go to [Get Support](/get_support) section.
