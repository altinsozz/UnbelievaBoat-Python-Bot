# **UnbelievaBoat-like Discord Bot in python**
### For questions about the bot and how to set it up: ask me on Discord at *<Kendrik 2.0#7373>*

Code is finished and will be published here asap.

### - Info
The Bot uses most of UnbelievaBoat's commands for minigames and economy (not moderation tho). 
#### For a full list, see `src/command_list.txt`.
It emerged from the problem of UB having a balance ceiling and no automated role-income increasing to user's balances.

### - Goal
The goal was to make a easily customizable Template of a discord bot, also fixing the issues stated above.
You can use and adjust the code as you want so it fits your needs.

### - Install & Use
1. Create a Discord Application for your bot (see https://youtu.be/b61kcgfOm_4, https://discord.com/developers/applications)
2. In the Discord Dev Portal, in the "Bot" tab of your application, **enable presence intent and server members intent**.
3. Download the code, structured as in this repo.
4. Open the `main.py` file, line 40 and change the **token** to the one of your created bot.
5. If you want log info : In `main.py`, go to line 88 and put a channel ID of the server you want to use the bot in. (Activate Developer Mode Discord to copy channel IDs). This channel will be used to send information about the bot status. Also uncomment line 88, 93, 94, 100 and 109
6. In the `database/database.json` file: scroll down to the symbols part and put a *custom emoji name* in the "symbol_emoji" variable. - for example if you have a bitcoin emoji called "btc". It must be an emoji you uploaded to the server, not a discord-wide one.
7. Invite the bot to your server as shown in https://youtu.be/b61kcgfOm_4
8. Install python3 if you dont have it
9. Install the Discord Api for python3 using pip (`pip install discord.py`)
10. In your server, create a role named "botmaster" and give it to people who should be bot admins.
11. Launch main.py with **python3**.
You should be good to go!
