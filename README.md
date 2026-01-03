<h3 align="center">
    <br />
    Alt-farm detector
</h3>

<div align="center">

[![In-game bans](https://img.shields.io/badge/bans-400+-red?style=for-the-badge&logo=roblox&logoColor=d9e0ee)](https://www.roblox.com/games/6872265039)
![Tracked players](https://img.shields.io/badge/tracked%20players-375+-green?style=for-the-badge)
![Python version](https://img.shields.io/badge/py%20version-3.12.6-blue?style=for-the-badge&logo=python&logoColor=d9e0ee)

</div>
---


## What is alt-farm?

Alt-farm is when a group of players queue with their alts to get
RP faster and with no effort, this is not allowed in Roblox BedWars

## Commands

- ### Friends
    - added `[target, usernames]`
    - ingame `[username, sameserver]`

- ### List
    - get 
    - group `[group_name]`

- ### Reports
    - add
        - player `[username, alt_account, group_name]`
    - mute `[mute_online, mute_offline, other_game]`
    - notifications
    - resume
    - stop

- ### Snipe
    - joinsoff
        - player `[username, force_update]`

    - player `[usernames]`

- ### Track
    - player `[username]`
    - stop `[username]`

> [!NOTE]
> `snipe joinsoff` command only works with the GAME_ID from 
> your [.env file](.env.example)

## Channels

This bot follows the next channels structure:

- REPORTS
    - users-status
        > Notifies you when any account is online
    - ingame-alts
        > Notifies you when an alt is online
    - gameids
        > Sends all the gameIds the players are in
    - gameids-with-alts
        > Sends all the gameIds where at least 1 alt is in

- TRACKING
    > In this category you will find all the tracking channels you made using `/track player`

> [!NOTE]
> The bot will only send a notification if the player is playing the specified game in your [.env file](.env.example) or
> if you want it to send for every game you can use
> `/reports mute other_game:False` 


## How to start
> Install [Botsblox.exe](https://github.com/DaD-exe/botsbloxs/releases/download/botsblox/Botsblox.exe).
