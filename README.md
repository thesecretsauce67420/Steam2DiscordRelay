# Steam 2 Discord Relay

A shitty FOSS Relay for steam, relays to discord,

dunno what else to put here, got nothing else to say

## How to use it
1. Clone the repo (```git clone https://github.com/thesecretsauce67420/Steam2DiscordRelay.git```)
2. CD into the directory (```cd Steam2DiscordRelay```)
3. Create a file called config.json
4. Paste this text into the config, replace the shit, spy is whether its oneway (true) or twoway (false):
   ```
   {
     "user": "<STEAM_USERNAME>",
     "pass": "<STEAM_PASSWORD>",
     "webhook": "<DISCORD_WEBHOOK_URL>",
     "spy": "<false_OR_true>",
     "bot": "<DISCORD_BOT_TOKEN_FOR_NO_SPY>"
     "channel": "<DISCORD_CHANNEL_ID_FOR_NO_SPY>"
   }
   ```
5. Go to how to setup the bot
6. Profit!!!
## How to setup the bot
1. Enable developer mode on discord
2. Make a bot in the developer portal
3. Setup the intents with the read messages intent
4. Copy the bot token and paste it into config.json
5. Get the bot into the server
6. Copy the channel id of the channel you want the relay to listen to and paste it into config.json
7. Profit once again!!
## TODO!!!
1. You need epsteam kneeguard off on the acc (steam guard), bot doesnt have support yet
