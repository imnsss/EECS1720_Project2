# Lab2 -- Discord bot
- A discord bot made by Yizhi Zhou!
- This is a simple robot that involves some basic functions
- I find that making a bot on social media is quite interesting, and I will keep updating this until its functions are perfected! 

## Requirement (Some of them I may have forgotten how to install...)
  - Download Python
  - Main part
    - import discord (pip install discord)
    - from discord.ext import commands
    - import requests (pip install requests)
    - import json 
    - import random (pip install random)
  - Keep Online part 
    - from flask import Flask (pip install flask)
    - from threading import Thread 
  - Music Part
    - Add ffmpeg environment varible in the local
    - Add PyNacl (pip install PyNacl)
    - import discord (pip install discord)
    - import youtube_dl (pip install youtube_dl)
    - from discord.ext import commands


## Information about the bot
- Invite link
    - https://discord.com/api/oauth2/authorize?client_id=947577545451249664&permissions=391232&scope=bot
    
- Simple functions (still updating)
  - You can get a random joke from the bot by typing **-joke**
  - You can get a random quote from the bot by typing **-quote**
  - Type **-help** to view the guide of the bot
  - Type **-info** to view related information about me and the bot
  - Type **!ping** to see the current ping
  - The bot will repeat what you said by typing **!repeat [...]** Example: !repeat I am smart
  - Type **!rn/!ln** To get a random/lucky number (0-100)
  - Play rock-paper-scissors with the bot → **!rps [rock/paper/scissors]** 
  - Listen to music (type **-music** to view all the commands)
    - **!join**, **!leave**, **!play**, **!pause**, **!resume**
  - ...
  
- I use the following sites to keep the bot alive
  - https://replit.com/ (code)
  - https://uptimerobot.com/ (to keep the bot online)

- If you cannot use the robot, please join my testing discord server to experience its functions.
  - https://discord.gg/G2GFGqzW
  - And don't worry, my bot will keep online most of the time because I have set them up already! You can just use the invite link above to let the bot join your server and enjoy it lol!!

## Updates
- Feb 23, 2022 > Lab2 Project first draft 
- Feb 24, 2022 > Add -help command by using 'Embed' and try to add music function....
- Feb 27, 2022 > Improve the code and still working on the music part, but there's something wrong with the discord.ext???
- Feb 28, 2022 > Improve the code
- Mar 2, 2022 > Fix the music part eventually!!! It is difficult to handle the trouble from ffmpeg...
 Now, people can listen to music by using my bot!!

    
## References
- Video Tutorial
    - https://www.youtube.com/watch?v=SPTfmiYiuok&t
- API
    - https://zenquotes.io/api/quotes
    - https://geek-jokes.sameerkumar.website/api?format=json
- Related Discord Documents
    - https://discord.com/developers/docs/interactions/application-commands
    - https://discordpy.readthedocs.io/en/stable/
- Related documents
    - https://github.com/sameerkumar18/geek-joke-api

