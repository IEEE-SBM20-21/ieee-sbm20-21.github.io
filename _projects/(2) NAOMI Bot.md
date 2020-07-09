---
name: NAOMI
tools: [Node JS, Postgresql]
image:
description: Telegram bot built in node.js to perform event registrations for Navigare (Techweek 19-20)
---

# NAOMI Telegram Bot

Telegram bot built using [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api) to provide event details and facilitate event registrations for all the events of Navigare, Techweek '20 of IEEE Manipal.

## Features
 - Show event details
 - Individually register
 - Event register fot both individual and team based events

Uses the postgres addon of Heroku (where the bot was hosted) to maintain the db. A simple script was written to import all data from the db to the local machine which allowed the Management team to send reminder emails.

## Contributors
 - Anant Verma
 - Shubham Sachdeva
 - Kishor (Mentor)
