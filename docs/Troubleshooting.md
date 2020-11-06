---
id: basic_troubleshooting
title: Basic Troubleshooting
---

## Inviting Troubleshooting
### When adding Rythm, I can't see my server in the list!
#### Are you signed into the correct account?

If you can't find your server in the drop-down section, this can be caused by various reasons. First, you should make sure that you're signed into the correct account. If you're not, then press the blue **Not you?** button.

![Signed in as User#5119 Not you?](/img/docs/adding/signed-in-as-example.png)

#### Do you have permissions in the server you want to add Rythm to?

If you're **100%** sure that you're signed into the correct account, then you should make sure that you have the correct permissions. In order to add a bot, you need to have a role with the `Manage Server` or `Administrator` permission. If you're the server owner, you have those regardless, of course.

:::tip note 
If you are able to change the name of the server, you have the required permissions!
:::

#### Open an incognito tab and invite Rythm from there.

If you're sure that **you're signed into the correct account** and **you have permissions on the server that you'd like to add Rythm to**, then you should open an incognito tab and invite Rythm from there. You can find instructions in the table below, if you don't know how to do that.
  
| Browser  | Windows/Linux | MacOS       |
|:--------:|:-------------:|:-----------:|
| Chrome   | CTRL+Shift+N  | CMD+Shift+N |
| Firefox  | CTRL+Shift+P  | CMD+Shift+P |
| Opera    | CTRL+Shift+N  | CMD+Shift+N |
| MS Edge  | CTRL+Shift+N  | CMD+Shift+N |
| Explorer | CTRL+Shift+P  | N/A         |
| Safari   | N/A           | CMD+SHIFT+N |

##### Why is this necessary?

Because Discord caches data into cookies, it retains old account information and glitches out the bot invite screen. By using an incognito/private browsing window, it forces Discord to use a fresh session which fixes the glitch and allows you to select a server from the drop-down menu.

### When adding Rythm, Discord asks me to verify my e-mail address.

[Unverified Discord account](/img/docs/basic-troubleshooting/unverified.png)

Discord requires you to verify your e-mail account to add bots into your servers. Head to the User Settings and verify your e-mail there.

### I can't invite Rythm on my mobile!
For any issue with inviting Rythm on mobile, see the [Mobile Troubleshooting](https://rythmbot.co/docs/mobile_troubleshooting) section.

## Rythm won't play my playlist
Make sure the playlist is either `Unlisted` or `Public`. If it is set to `Private` Rythm won't be able to play that specific playlist.

If you recently made a private playlist public or unlisted, you should wait a short while until Rythm realizes that it is public.

## Rythm left the voice channel while not playing anything
For performance reasons, Rythm leaves after a while of being alone or unused in a voice channel.
This helps Rythm save resources while no one is listening to it and keeps the music quality consistent for all users at any given time!

Don't worry though, as long as you are in a voice channel, just type !summon to make Rythm rejoin your channel!

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
1. Make sure Rythm is showing as online.
  + If Rythm is offline, try kicking the bot out of your server and inviting it again. If after doing that Rythm is still showing as offline, you may skip to step 4.
  
2. Make sure you're using the correct prefix. You can mention Rythm to get the prefix.<br/>

  ![Mention to get prefix](/img/docs/settings/prefix.png)
  
  ![Mention to get prefix 2](/img/docs/settings/prefix2.png)
  
  + You can learn how to change Rythm's prefix by heading to the [Prefix Setting](/settings#prefix) section!
  
3. Make sure Rythm has the permissions to read and send messages in the channel.
  + You can give the `Administrator` permission to Rythm to make this easier.
  
4. Take a look at our [#outages](https://discord.com/channels/231471142685245440/359311833653313546) channel on our [official Rythm Bot Discord server](https://rythmbot.co/support) to see if there are any issues going on.

5. If the above methods do not work, please choose option 6 in our [#help-desk](https://discord.com/channels/231471142685245440/359355279004925954) channel on the Rythm Bot Discord server to receive assistance from a member of our Support Team.

[Click here to join the official Rythm Bot Discord server](https://rythmbot.co/support)

## Rythm is responding to commands but not joining the voice channel
If you find that Rythm is responding to your commands but not joining a voice channel use the following method:

1. Move to a different voice channel.
2. `!summon` the bot into that voice channel.
3. Move back to the original voice channel.
4. `!summon` the bot back into the original voice channel.

If the above method does not work, try changing the server region of your server or kicking & reinviting Rythm to your Discord server.

## I've read everything above but none fixed my issue. What do I do?

In case nothing from the list above has helped you, please go to [Miscellaneous Help](/misc_help).
