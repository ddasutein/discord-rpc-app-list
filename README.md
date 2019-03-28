# Discord Rich Presence Supported Applications
This repository contains a JSON listing all available Android games, which will sync with the [Discord RPC C# client.](https://github.com/ddasutein/Discord-RPC-csharp)
Please note that this would only display the current game you are playing. No in-game status, invite, or spectate player are available.

## Can I add my own game to this list?
Absolutely! In order to add your own game to the list, you need two things. One, the process name of your game. You can check this by looking
in your Application Manager. Two, you need to create an application on the
[Discord Developer Portal](https://discordapp.com/developers/applications/). 

## JSON object structure 

`app_name`: Name of your application. Note, this would not be displayed on Discord Clients. Your application name will depend on what you entered
in the Discord Developer Portal.

`process_id`: The process name of your application. You can get this by looking into your Application Manager. (e.g, com.nianticlabs.pokemongo)

`discord_application_id`: The Client ID number from the Discord Developer Portal.

`large_image_key`: Large thumbnail of your game icon. Preferably that you use the same icon as your game.

`large_image_text`: What text will be displayed when a user hovers over the large image on the Discord client. 

`small_image_key`: (Optional)

`small_image_text`: (Optional)
