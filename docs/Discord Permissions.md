---
id: discord_permissions
description: Setting up Rythm in your server with the help of Discord permissions.
title: Mixing Discord's permissions
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

Here are some frequent questions related to Discord's permissions system.

## Why does Rythm ask for the `Administrator` permission when I invite the bot?
---
Upon inviting, Rythm asks for the `Administrator` permission because it will make things easier for you to use the bot without any setup required. Make sure Rythm has all of these permissions to work properly if you revoke its `Administrator` permission:
- `View Channels`
- `Send Messages`
- `Embed Links`
- `Add Reactions`
- `Use External Emoji`
- `Manage Messages`
- `Connect`
- `Speak`

## How can I make Rythm only respond to Admins/specific roles?
---
In order to lock Rythm's commands to a specific role, you can try one of the following:

### DJ Only Mode
 1. Give users you want to have access a role named `DJ` or a role which is considered as DJ from the `!settings djrole` command.
 2. Run `!settings djonly on`.

After so, Rythm will only be used by users with DJ permissions. More information about DJ role and setting up DJ role can be found [here](/dj_role).

### Blacklisting Channels
 1. Make a channel that can only be seen by users with the specific role(s).<br/>
    ![Disable Role Everyone](/img/docs/perms/role-everyone.png)
    ![Enable Specific Role](/img/docs/perms/role.png)
    - More information on how to do this can be found at [Discord's support page](https://support.discord.com/hc/en-us/articles/206029707).
 2. Blacklist other text channels by following [here](/permissions#how-do-i-restrict-rythm-from-being-used-in-a-specific-textvoice-channel)

After so, only users with access to the mentioned channel can use Rythm.
:::caution Note   
WIth this method, users are still able to queue songs via the web dashboard.
:::

## How do I restrict Rythm from being used in a specific text/voice channel?
---
### Method 1: Block music commands from specific text channels.
You can use `!settings blacklist #channels` to blacklist specific text channels.

**Example**: `!settings blacklist #chat #share-your-songs`

![Blacklist example](/img/docs/settings/blacklist-text-channel-example.png)

:::caution Note
   - This only prevents music commands from being used. Other non-music commands such as `!ping` still work normally.
   - This can't be applied to voice channels.
   - The message `This channel cannot be used for music commands` will appear every time a music command is used.
:::
To resolve these, you can use Discord's permission system as explained above.

### Method 2: Block Rythm completely from text/voice channels using Discord's permission system.
First you will need to disable Rythm's `Administrator` permission:

1. Go to your server's settings and select <code>Roles</code>.
2. Find Rythm, revoke its <code>Administrator</code> permission and grant the <code>View Channels</code>, <code>Send Messages</code>, <code>Embed Links</code>, <code>Add Reactions</code>, <code>Use External Emoji</code>, <code>Manage Messages</code>, <code>Connect</code> and <code>Speak</code> permissions.
3. If you have any other roles Rythm is assigned to, repeat this step for each role.
4. Save and close out of server settings.

After that, you can "blacklist" channels of your choices. By denying Rythm's permission to access the channels, Rythm can't be used there.
<Tabs
  defaultValue="text"
  values={[
    {label: 'Text Channels', value: 'text'},
    {label: 'Voice Channels', value: 'voice'},
  ]}>
  <TabItem value="text">
    <ol type="1">
      <li>Go to each text channel settings you want to restrict Rythm from responding in.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, deny the <code>Read Messages</code> and <code>Send Messages</code> permissions.</li>
      <li>Save and close out of channel settings.</li>
      <li>Repeat step 1 to 4 for other text channels.</li>
    </ol>
  </TabItem>
  <TabItem value="voice">
    <ol type="1">
      <li>Go to each voice channel settings you want to restrict Rythm from connecting to.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, deny the <code>Connect</code> permissions.</li>
      <li>Save and close out of channel settings.</li>
      <li>Repeat step 1 to 4 for other voice channels.</li>
    </ol>
  </TabItem>
</Tabs>

---
"But what if my server has a lot of channels and I just want Rythm to stay in a single channel. Do I need to blacklist every other channel? 😩😩😩"

If you have the same idea as the question above, you can use this trick to "whitelist" a channel: Denying Rythm's permissions for a whole category then deciding which channel to allow Rythm to access 😉
<Tabs
  defaultValue="text"
  values={[
    {label: 'Text Channels', value: 'text'},
    {label: 'Voice Channels', value: 'voice'},
  ]}>
  <TabItem value="text">
    <ol type="1">
      <li>Go to the category settings where you want to restrict Rythm from responding in.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, deny the <code>Read Messages</code> and <code>Send Messages</code> permissions.</li>
      <li>Save and close out of category settings.</li>
      <li>Repeat step 1 to 4 for other categories.</li>
      <li>Go to the text channel where you let Rythm be able to respond in.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, enable the <code>Read Messages</code> and <code>Send Messages</code> permissions.</li>
      <li>Save and close out of text channel settings.</li>
      <li>Repeat step 6 to 9 for other text channels.</li>
    </ol>
  </TabItem>
  <TabItem value="voice">
    <ol type="1">
      <li>Go to the category settings where you want to restrict Rythm from joining in.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, deny the <code>Connect</code> permission.</li>
      <li>Save and close out of category settings.</li>
      <li>Repeat step 1 to 4 for other categories.</li>
      <li>Go to the voice channel where you let Rythm be able to connect.</li>
      <li>Head to the <code>Permissions</code> section ➠ Click <code>+</code> ➠ <code>Rythm</code></li>
      <li>On the Rythm override, enable the <code>Connect</code> permission.</li>
      <li>Save and close out of voice channel settings.</li>
      <li>Repeat step 6 to 9 for other voice channels.</li>
    </ol>
  </TabItem>
</Tabs>
