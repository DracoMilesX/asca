# asca
Antiscam Discord Bot

Asca moderates scammers and deletes scam messages

![Profile](https://cdn.discordapp.com/attachments/933434052621512734/935356514250678292/ascaprofile.png)

*Optionally configure via slash commands*

[Add to Server](https://discord.com/api/oauth2/authorize?client_id=930922882886934588&permissions=1099511635972&scope=bot%20applications.commands)

<details>
<summary>Setup Your Own Instance</summary>

0. Create a Discord bot with
    * Scopes: `bot`, `applications.commands`
    * Permissions: `Manage Messages`, `Moderate Members`, `Ban Members`

1. Create a file `token` in the project root, which contains only your bot token from Discord.

2. Execute
```
% python3 -m pip install --requirement requirements.txt
% python3 bot.py
```
</details>

<details>
<summary>Credits</summary>

**Liz** (Lead Designer)  
**Mас** (Lead Tester)  
**Lauch** (Tester)
</details>