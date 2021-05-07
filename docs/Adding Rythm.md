---
id: adding_rythm
title: Adding Rythm
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import { Button } from '../Buttons/button';

Ready to start listening with Rythm? We currently offer 2 bots for free and 3 bots for premium users!

## Rythm releases
---
These are all official releases of Rythm Bot:

export const Highlight = ({children, color}) => (
  <span
    style={{
      borderRadius: '2px',
      color: color,
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

<table>
  <tr>
    <th>
      <img src="/docs/img/rythmlogosmall.png" alt="rythm"/>
      <Button onClick = {() => window.open('http://rythm.fm/invite','_blank')} buttonStyle = "btn--rythm--1">Invite  </Button>
    </th>
    <td>
      <ul>
        <h2><Highlight color="#fb0f32">Rythm</Highlight> (<code>Rythm#3722</code>)</h2>
        <li>Prefix: <code>!</code></li>
        <li>Rythm is our main bot used by the most servers. This bot and most of its features are available to the public <b>for free</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>
      <img src="/docs/img/docs/adding/rythm-2.png" alt="rythm-2"/>
      <Button onClick = {() => window.open('http://rythm.fm/invite2','_blank')} buttonStyle = "btn--rythm--2">Invite  </Button>
    </th>
    <td>
      <ul>
        <h2><Highlight color="#0070ff">Rythm 2</Highlight> (<code>Rythm 2#2000</code>)</h2>
        <li>Prefix: <code>></code></li>
        <li>Rythm 2 is the secondary Rythm bot, used by the second most number of servers. It is identical in functionality to Rythm 1, the only difference being the prefix. This bot and most of its features are available to the public <b>for free</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>
      <img src="/docs/img/docs/adding/rythm-3.png" alt="rythm-3"/>
      <Button onClick = {() => window.open('http://rythm.fm/invite3','_blank')} buttonStyle = "btn--rythm--3">Invite  </Button>
    </th>
    <td>
      <ul>
        <h2><Highlight color="#db00ff">Rythm 3</Highlight> (<code>Rythm 3#0817</code>)</h2>
        <li>Prefix: <code>&</code></li>
        <li>Rythm 3 is the third Rythm. While you can still invite Rythm 3, you need to <a href="https://rythm.fm/premium">activate Premium</a> for your server to use it.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>
      <img src="/docs/img/docs/adding/rythm-4.png" alt="rythm-4"/>
      <Button onClick = {() => window.open('http://rythm.fm/invite4','_blank')} buttonStyle = "btn--rythm--4">Invite  </Button>
    </th>
    <td>
      <ul>
        <h2><Highlight color="#46af2c">Rythm 4</Highlight> (<code>Rythm 4#0952</code>)</h2>
        <li>Prefix: <code>%</code></li>
        <li>Rythm 4 is the fourth Rythm. While you can still invite Rythm 4, you need to <a href="https://rythm.fm/premium">activate Premium</a> for your server to use it.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>
      <img src="/docs/img/docs/adding/rythm-5.png" alt="rythm-5"/><br/>
      <Button onClick = {() => window.open('http://rythm.fm/invite5','_blank')} buttonStyle = "btn--rythm--5">Invite  </Button>
    </th>
    <td>
      <ul>
        <h2><Highlight color="#33bed1">Rythm 5</Highlight> (<code>Rythm 5#6171</code>)</h2>
        <li>Prefix: <code>-</code></li>
        <li>Rythm 5 is the fifth Rythm. While you can still invite Rythm 5, you need to <a href="https://rythm.fm/premium">activate Premium</a> for your server to use it.</li>
      </ul>
    </td>
  </tr>
</table>



## The Authorization process
---
### Step one

Once you've chosen the release of Rythm that you would like to invite. and you are logged into the correct Discord account, you should now see a menu like this:

![Discord Authorization Screen](/img/docs/adding/discord-oauth2-1.png)

Tap or click the `Select a server` button. A pop-up should appear that will let you select where you'd like to add Rythm. In this case, we'll add the bot to `Music Lovers ❤`.

![Choose the server that you'd like and continue](/img/docs/adding/discord-oauth2-2.gif)

:::note Note
If you don't see your server in this drop-down, [click here!](/invite_troubleshooting#when-adding-rythm-i-cant-see-my-server-in-the-list)
:::

### Step two

Once you've selected the server that you'd like to add Rythm to, you can press the `Continue` button on the bottom right of the menu.

You should now see something similar to this:

![Press authorize and you'll be good to go!](/img/docs/adding/discord-oauth2-3.png)

:::caution Note
If you want to disable `Administrator` permission from Rythm, make sure you enable all other permissions. They are necessary for Rythm to work properly!
:::

### Final Step

Once you press the `Authorize` button and complete the Captcha, you should be redirected [here](https://rythm.fm/app?thanks). In addition, you'll also see a message like the one below in your Discord server. **Amazing!**

![A message sent by Rythm upon joining a Discord server](/img/docs/adding/thank-you-message.png)

Now let's get the party started by [playing some songs](/play_song)!

## I have problems with inviting Rythm!
---
For any issues with inviting Rythm, check out the [Invite Troubleshooting](/invite_troubleshooting) section.
