
![Logo](https://i.imgur.com/dYwFnhH.png)


## Limitless cloud storage for free.

This project works using discord as storage provider.

How does it work?

video soon

## What about other projects?

| Feature | Disbox ☁️| Unlimited Share ☁️ |
| ------------- | ------------- | ------------- |
| Size of chunk (more is better)  | 8 MB ❌ | 24,9 MB ✔️ |
| Encryption  | No ❌ | Yes ✔️ |
| Better config  | No ❌ | Yes ✔️ |
| Working now  | Download is broken ❌ | Yes ✔️ |
| Encrypted / Original size ratio  | Doesn´t have encryption ❌ | aprox. 1.3:1 ✔️ |
| Faster upload  | webapp (slower) ❌ | app (faster) ✔️ |
| Faster download  | webapp (slower) ❌ | app (faster) ✔️ |
| GUI  | Yes ✔️ | No (soon will be) ❌ |
| Upload technology  | Discord Webhook  | Discord Bot  |
| Free | Yes ✔️ | Yes ✔️ |
| Unlimited | Yes ✔️ | Yes ✔️ |
| Secure | Not enough ❌ | Encryption ✔️ |
| Simple | Setup is bit confusing ❌ | Not enough ❌ |
| Forever | Yes ✔️ | Yes ✔️ |
| Upload folders | Must be zipped (not supported) ❌ | Must be zipped (not supported) ❌ |
| **Result** | Worse ❌ | Better ✔️ |

## So what's holding you back?

Start using Unlimited Share today!


## Setup

Project is written in python 3.x., but soon will be compiled.

**If using version 0.2 and above, you don´t need python, because releases are compiled:**
Skip python download step.

**If you are using version 0.1. or are you using files from repozitory, you need python:**
Download python 3.x with pip.

Download latest zip from releases.

Go to https://discord.com/developers/applications and create new bot.

Follow this instructions: https://discordpy.readthedocs.io/en/stable/discord.html

Copy bot token and paste it into config.py:
```bash
  bot_token = "(here)"
```

Create new discord server (only for you and your bot) and copy guild id:

https://www.alphr.com/discord-find-server-id/

Paste it into config.py:
```bash
  guild = "(here)"
```

Then run setup.bat (setup will install all dependencies, run setup only first time.).

If terminal window after setup isn´t shown, run main.py (if something goes wrong, run it as admin).

### Upload:

```bash
  Upload or Download(u/d): 
  > u (upload)
```
    Enter file directory (file will be copied): 
    > (C:\Users\user\Desktop\this.file)

```bash
  Save file as: (unlimited share dictionary):
  > (this_file.dictionary (All needed data to download this file will be stored here.))
```
    Continue? (y/n): 
    > y (yes)

And thats all about uploading. (Dictionary file will be stored in project folder.)

### Download

```bash
  Upload or Download(u/d): 
  > d (download)
```
    Enter input file (directory): 
    > (C:\Users\user\Desktop\this_file.dictionary)

```bash
  Continue? (y/n): 
  > y (yes)
```

And thats all about downloading. (File will be downloaded into project folder.)
