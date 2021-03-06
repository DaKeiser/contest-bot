# contest-bot

A simple discord bot to notify you regarding upcoming contests on Codeforces and Hackerearth. 

### Disclaimer 
The bot is still under construction, and can be buggy

## Steps to install
- `pip3 install discord.py`

## Steps to run
- `python3 bot.py`

## Features as of now
- Returns Codeforces contests in personal chat as an embed

## Folder Heirarchy
```
.
├── bot.py
├── cogs
│   ├── commands.py
│   ├── events.py
├── config.py
├── config.py.example
├── LICENSE
├── README.md
└── utils
    ├── cf.py
    ├── he.py
    └── utility.py

```

- `bot.py` consists of all the core methods to run the bot. It is just like the *main* file. 
- `cogs` folder currently consists of `events.py` and `commands.py`. All events and commands must be coded in their respective files.
- Once you clone from Github, you need to first make the config file on your own. You have to get the token from discord developer portal and replace in the `token` variable.
- Rename `config.py.example` as `config.py.example`
- `cf.py` consists of all the API related tasks/scraping to be done from CodeForces
- `he.py` needs to be made similarly so that all related tasks can be done from HackerEarth.

A small advice. While making changes, try working on a new branch.

Do check out DiscordPy [documentation](https://discordpy.readthedocs.io/) for more details.

## Contribution

In case you find any issues, feel free to add them in the [Issues](https://github.com/DaKeiser/contest-bot/issues) tab.