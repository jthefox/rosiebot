# Rosiebot

1. [Features](#current-features)
2. [Commands](#commands)
3. [Future Updates](#future-updates)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Discord](https://img.shields.io/badge/discord.js-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

Rosiebot is a personal use discord bot- created with NodeJS, using AWS RDS for the database, and hosted on Heroku- based on the template I created. I do not have any current plans to make the bot public so there is no invite link, but I may make a public bot in the future.

## Current Features
- Slash commands
- Bot management operations CLI
- Persistent data
  - Per-guild user profiles
  - Betting with per-guild score data

## Commands
`help` - Displays all commands or shows details for a specific command<br>
![Basic usage of the help command](./assets/cmd-help1.png)
![Usage of the help command for a specific command](./assets/cmd-help2.png)

`random` - Generates a random League of Legends champion<br>
![Usage of the random command](./assets/cmd-random.png)

`/bet` - Betting feature interface<br>
![List of available bet commands](./assets/cmd-bet1.png)<br>
![Creating and placing a bet with /bet](./assets/cmd-bet2.png)
![Closing and ending a bet with /bet](./assets/cmd-bet3.png)

`/me` - Display your user profile on a server<br>
![Usage of the /me command](./assets/cmd-me.png)

## Future Updates
**Features**:
- Ability to set the bet close timer in slash command options
- Website for the bot
- Caching for third-party api data

**Commands**:
- Change bot command prefix
- Duel command between 2 users
- Rock, paper, scissors between 2 users
