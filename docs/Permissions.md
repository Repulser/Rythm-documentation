---
id: permissions
title: Understanding Rythm's Permissions
---

## What users can use what command?

Rythm's built-in permission system can be divided into the following groups:

### Normal user without any special roles
 - Is able to add songs to the queue but can't remove other users' songs (can remove their own)
 - Is able to use commands that don't interfere with other people's music.
   - `lyrics`, `np`, `queue`, etc.
 - Can't skip a song without voting.
 - Doesn't have access to control the music in any way.

### User alone with Rythm/User with a `DJ` role or the `Manage Channels` permission
:::info note
Rythm still count you as alone with the bot if all other users are deafened.
:::
 - Has full access to all music commands.
 - Bypasses `maxusersongs` setting limit. [**More Info**](/settings#max-user-songs)
 - Can't change Rythm's settings.

### User with `Manage Server` permission
 - Is able to change Rythm's settings.
 - Is limited to normal user's music commands, unless they have `Manage Channels` permission or `DJ` role.

### User with `Administrator` permission
 - Is able to change Rythm's settings.
 - Has full access to all music commands.

## How can I make Rythm only respond to Admins/specific roles?
In order to make Rythm commands just available to specific roles, you can do one of the following:

### DJ Only Mode
 1. Give users you want to have access a role named `DJ` or a role which is considered as DJ from the `!settings djrole` command. ([More info on DJ Role setting](/settings#dj-role))
 2. Run `!settings djonly on` ([More info on DJ Only mode](/settings#dj-only-mode))

### Blacklisting Channels
 1. Make a channel that can only be seen by users with the specific role.
    <details>
        <summary>Click here for how.</summary>
        <ol>
            <li><img src="/docs/img/docs/perms/role-1.png" alt="role 1"/></li>
            <li><img src="/docs/img/docs/perms/role-2.png" alt="role 2"/></li>
        </ol>
        <ul>
            <li>More information on how to do this can be found at <a href="https://support.discord.com/hc/en-us/articles/206029707">Discord's support page.</a></li>
        </ul>
    </details>
 2. Blacklist other text channels by following [here](/permissions#how-do-i-restrict-rythm-from-being-used-in-a-specific-textvoice-channel)

## How can I give all users access to all music commands?
There is currently no setting that will apply DJ to all users. You will have to either give them the `Manage Channels` permission or the DJ role manually.

If every member in your server has a common role, you can use the following settings command to set that role to be DJ Role: `!settings djrole <Role name> / <@Role>`. To learn more, head to the [DJ Role section](/dj_role).

## How do I restrict Rythm from being used in a specific text/voice channel?
### Block music commands from specific text channels.
You can use `!settings blacklist #channels` to blacklist specific text channels.

**Example**: `!settings blacklist #chat #gaming #international...`

![Blacklist example](/img/docs/settings/blacklist-text-channel-example.png)

If you don't want Rythm respond with the blacklist message, you can follow the guide below.

### Block Rythm completely from text/voice channels.
To disallow Rythm from being used within certain text/voice channels, you must use the Discord's permission system as described below:
1. Go to your server's settings and select `Roles`.
2. Find Rythm, revoke its `Administrator` permission and grant the `Read Text Channels & See Voice Channels`, `Send Messages`, `Manage Messages`, `Embed Links`, `Add Reactions`, `Connect` and `Speak` permissions.
   - If you have any other roles Rythm is assigned to, repeat this step for each role.
3. Save and close out of server settings.
4. Go to each text/voice channel settings you want to restrict Rythm from responding (text channel) or connecting (voice channel) to.
5. Head to the `Permissions` section ➠ Click `+` ➠ `Rythm`
6. On the Rythm override:
   - **For text channel:** Deny the `Read Messages` and `Send Messages` permissions.
   - **For voice channel:** Deny the `Connect` permission.
7. Save and close out of channel settings.
