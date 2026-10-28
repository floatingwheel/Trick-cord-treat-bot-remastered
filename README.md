# Trick-cord-treat-bot-remastered
A Discord bot similar to the 2020 Trick'ord treat bot made by Discord with some improvements.
These include:
- Buttons instead of commands to answer the door
- Discord applications commands instead of special character command
- better interface?

Future improvements may include:
- Directly add a character from Discord
- Easier setup 

# Installation
Note that this repo does not come with any characters (due to the fact that the characters I used may or may not be copyrighted). As such, you must insert your own characters in the sqlite database. Placeholder characters may be provided in the future to make the setup easier. 
## Using docker compose
To install using docker compose, clone this repo and import your sqlite db file and `.env` file contaning your `discord_token` into the folder. Now run `docker compose up -d` and it should automatically start building and deploying the discord bot. 
# Usage
`/configure enable {True|False} [channel] <channel name>`: configures whether the bot is enabled or not, and what channel the bot will send the guests to.
e.g. : `/configure enable True channel #entrance-door`

`/leaderboard`: Get the server's leaderboard of the players points

`/pie`: Get the server's pie chart of the players points

`/ping`: Get the bot's latency

`/plot`: Plot and display a graph of the server's player points over time
