# Extractions-Bot
A bot to extract a random person from the server

# Dependencies
This bot depends on [discord.js](https://github.com/discordjs/discord.js)

# Commands
### Note: Parameters contained within square brackets (i.e. "\[role\]") are optional

| Command               	| Parameters   	| Description                                                                                                 	| Aliases             	|
|-----------------------	|--------------	|-------------------------------------------------------------------------------------------------------------	|---------------------	|
| /extraction random    	| \[Role\]     	| Extracts a random person (bots excluded). If a role is specified only people with said role will be picked. 	| /extraction extract 	|
| /extraction block     	| <Role\|User> 	| Adds a role or a user to the blocklist.                                                                     	|                     	|
| /extraction unblock   	| <Role\|User> 	| Removes a role or a user from the blocklist.                                                                	|                     	|
| /extraction blocklist 	|              	| Displays a list of blocked users and roles.                                                                 	|                     	|

---
# Setup
## Creating the Discord bot
1) Create a Discord Application (https://discord.com/developers/applications/)
2) Head over to the "Bot" section of your application
3) Hit "Add a bot"
4) Copy the token

## Setting up permissions
Give the bot the following permissions:
* Send Messages
* Manage Messages
* Mention Everyone
* Add Reactions
![permissions](https://user-images.githubusercontent.com/40493890/161252030-f0e4286d-72fc-405f-a566-2b1b73c02187.png)

## Configure
1) Clone the repository
2) Open the config.json file
3) Paste the bot's token

## Starting
To start the bot simply type "npm start" in the console and press enter.
