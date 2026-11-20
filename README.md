# FosKai bot

Free OpenSource alternative for entertainment bots. For example: TonzBot, AniSmiBot.

# Table of contents

1. [Setup for your profile](#setup-for-your-profile)
2. [Commands](#commands)
3. [Forking and modifing](#forking-and-making-your-own-bot)

## Setup in your profile

1. Go to your profile
2. Settings ->
3. Chat automatisation ->
4. Start typing "foskai_bot"
5. Press "add" on @foskai_bot
6. Configure which chats are alowed for bot
7. Give access for messages, changing name and bio
8. Press save
9. Done

*Screenshosts soon*

## Commands

They all are started with ```.``` (dot)

Future commands:
- .tt https://www.tiktok.com/... - download TikTok video
- .mute/unmute - Mute/Unmute user in PM
- .tr [reply] - transcrypt voice message in reply
- .spam [number] [text] - spam with message "[text]" [number] times
- .calc {expression} - calculate mathematic expression
- .rand [number 1] [number 2] - get random number betwen these two
- .type [seconds] - always send "typing" in this chat, even if you leaved chat
- .anim [text] - send text like you're typing it
- [formated text - see more about](#formated-text)

There may be commands like:
- .fetch - send info about your phone/

### Formated text
- .b - **bold**
- .i - *cursive*
- .m - `monospace`
- .s - ```spoiler```
- .r - strikethrough

Also you can combine them like this:
- .is ```*cursive spoiler*```
- .bm ***bold monospace***
And so on

## Forking and making your own bot

So, if you want to modificate/fork the code, share it for free, under MIT license, and keep it open.
Also put thanks to @foskai_bot and @kag9s. <3

## Setup your own bot

If your clearly want to run this bot at your own server, do next steps.

1. Install dependencies with your package manager:
  - python >= 3.11
  - pip >= 2.0
  - curl
  - ffmpeg
  - git
2. Clone this repo: ```$ git clone https://github.com/KaG9S/foskai_bot.git```
3. Install pip depends.: ```$ pip install -r requiments.txt```
4. Configure your start.env file (or start.cmd on windows): add next things
  - bot token
  - threads
  - activate V.Env.
  - settings path
  - type: private or public
  - blacklist/whilelist
  - admin user ID
5. Run it: ```$ ./start.env``` (or start.cmd)
