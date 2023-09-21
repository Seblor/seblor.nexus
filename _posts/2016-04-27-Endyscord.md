---
title: Endyscord
date: 2016-04-27 00:00:00 +/-TTTT
categories: [Discord Bot, Backend, Frontend]
technologies: [Node, Discord.JS, Budibase, Redit, Prisma]
---

![Alt text](/assets/img/posts/endyscord/logo.webp){: w="200" }

Endyscord is a multi-purpose bot for [Minecraft-France](https://minecraft-france.fr/), a french Minecraft community.

This bot has started in 2016, has been remade a couple times, and was migrated from JavaScript to TypeScript in 2022

# Features

Here is a list of features:

- Blacklist (for words and invites)
- Bulk message deletion
- Eval command
- Automatic recreation of LFG threads when the limit of members has been reached
- Message content caching with Redis
- Nickname sanitizer (removes special characters in usernames and attempts to convert fancy text ot regular ASCII characters)
- NLP (Natural Language Processing) for identifying messages from hacked accounts and for off-topic messages
- Voice mute preserval
- Raid identification (alerts the admins when a lot of users join at the same time, and displays the options to ban or kick the raiding accounts, or ignore the raid)
- RSS Feed for Minecraft-France to send a message each time an article is published
- Status rotation (customizable status)
- Stream preview logging
- Temporary voice mute and voice ban with a modal to select the duration and fill the reason
- Automatic message deletion in command-only threads
- Automatic renewal of threads to avoid being archived
- Preservation of attachments sent in tickets
- Logs the timeouts of users with the reasons
- Logs all edited and deleted messages
- Wiki lookups (sends a wiki link with a user sends a message with the format `{seearch term}`)

This bot is private and will not be open sourced.