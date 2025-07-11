# MusicBot

[![GitHub stars](https://img.shields.io/github/stars/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/network)
[![Python version](https://img.shields.io/badge/python-3.8%2C%203.7%2C%203.6-blue.svg)](https://python.org)
[![Discord](https://discordapp.com/api/guilds/129489631539494912/widget.png?style=shield)](https://discord.gg/bots)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

MusicBot is the original Discord music bot written for [Python](https://www.python.org "Python homepage") 3.8+, using the [discord.py](https://github.com/Rapptz/discord.py) library. It plays requested songs from YouTube and other services into a Discord server (or multiple servers). If the queue is empty, MusicBot will play a list of existing songs that is configurable. The bot features a permission system, allowing owners to restrict commands to certain people. MusicBot is capable of streaming live media into a voice channel (experimental).

![Main](https://i.imgur.com/FWcHtcS.png)

## Setup
Setting up the MusicBot is relatively painless - just follow one of the [guides](https://just-some-bots.github.io/MusicBot/). After that, configure the bot to ensure its connection to Discord.

The main configuration file is `config/options.ini`, but it is not included by default. Simply make a copy of `example_options.ini` and rename it to `options.ini`. See [`example_options.ini`](./config/example_options.ini) for more information about configurations.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix), which will download, process, and play a song from YouTube or a similar site. A full list of commands is available [here](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

### Further reading

* [Support Discord server](https://discord.gg/bots)
* [Project license](LICENSE)
みうちよう
