---
id: queue
description: In this section, we will learn about Rythm's queue.
title: Queue
---

## Rythm's Queue
---
  - If you try to play songs while another song is playing, or you try to play a playlist, Rythm will add those into a waiting queue. The order of the songs in queue is the order you requested them.

  ![AddingToQueue](/img/docs/queue/add-to-queue.png)

## Viewing the Queue
---
  - To view the queue, simply run `!queue` or `!q`. A nice-looking embed will pop up and list the songs you have added into the queue.

  ![ViewingQueue](/img/docs/queue/view-queue.png)

  - If there are multiple queue pages, you can either:
    + Do `!queue <Page Number>` to view that specific page. Example: `!queue 4`

    ![ViewingQueue2](/img/docs/queue/view-queue-2.png)

    + Use the reactions given to switch between pages.

    ![ViewingQueue3](/img/docs/queue/view-queue-3.gif)

## Managing the Queue
  - You can organize and manage your queue using commands. [Check here](/commands#queue) to view the list of queue commands.

:::info note
Rythm's maximum queue length is **10,000 songs**. This is adjustable via `MaxQueueLength` setting ([**More Info**](/settings#max-queue-length))
:::
