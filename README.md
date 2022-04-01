# Extractions-Bot
A bot to extract a random person from the server

# Dependencies
This bot depends on [discord-bot](https://www.npmjs.com/package/discord-bot)

# Commands
### Note: Parameters contained within square brackets (i.e. "\[role\]") are optional
| Command               	| Parameters   	| Description                                                                                                 	| Aliases             	|
|-----------------------	|--------------	|-------------------------------------------------------------------------------------------------------------	|---------------------	|
| /extraction random    	| \[Role\]       	| Extracts a random person (bots excluded). If a role is specified only people with said role will be picked. 	| /extraction extract 	|
| /extraction block     	| <Role\|User> 	| Adds a role or a user to the blocklist.                                                                     	|                     	|
| /extraction unblock   	| <Role\|User> 	| Removes a role or a user from the blocklist.                                                                	|                     	|
| /extraction blocklist 	|              	| Displays a list of blocked users and roles.                                                                 	|                     	|
