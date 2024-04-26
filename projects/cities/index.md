---
layout: page
title: Cities Python Telegram bot
---
### Description
Telegram bot plays game of "Cities" and implements basic functionality:
- Player says some city
- Bot replies with the city which starts with the last letter of the previous city
- If there are no cities starting with this letter then it is allowed to skip to the next letter 
(from right to left)
- First who fails to reply loses the game.

Since the bot uses database of the russian Tax Office it plays in russian language only.
You can feed him any list of cities by your choice in order to customize UX. 
Just change letters (LOCAL_A, LOCAL_Z) in settings.py specific to your alphabet and list of cities.

### Tech. stack:
- Python
- [AIOGRAM](https://docs.aiogram.dev/en/latest/) asynchronous framework for Telegram Bot API

### Github
[https://github.com/polo7/tgb-aiogram-cities/](https://github.com/polo7/tgb-aiogram-cities/)

### Bot on Telegram
[PlayGoroda_bot](https://t.me/PlayGoroda_bot)

*bot has been deployed using free Python-hosting, that is why it is not available 24/7.