# Twitch4J - Minecraft Fabric Plugin Template (WIP)

This project is using the fabric example mod as base: https://github.com/FabricMC/fabric-example-mod

For setup instructions please see the [fabric wiki page](https://fabricmc.net/wiki/tutorial:setup) that relates to the IDE that you are using.

Twitch4J Support:

[![Discord Server](https://discordapp.com/api/guilds/143001431388061696/embed.png?style=banner2)](https://discord.gg/FQ5vgW3)
[![Twitch API Server](https://discordapp.com/api/guilds/325552783787032576/embed.png?style=banner2)](https://discord.gg/8NXaEyV)

Fabric Support:

[![FabricMC Server](https://discordapp.com/api/guilds/507304429255393322/embed.png?style=banner2)](https://discord.gg/v6v4pMv)

--------

## A quick note:

This plugin is part of the [Twitch4J API](https://github.com/twitch4j/twitch4j) project.

## Twitch Developer Applications

To obtain a `client_id` and `client_secret` to populate in `config.yml`, you can create an app [here](https://dev.twitch.tv/console/apps/create).

Alternatively, you can provide `oauth_token`, which can be generated [here](https://www.twitchtokengenerator.com/) if you do not wish to host the authentication process yourself.

At least one of these must be provided to interact with the Helix API, which is used to track follows and stream state.

To read chat, no token is necessary, but in order to send messages to chat, an `oauth_token` with the `chat:edit` scope *is*.

## License

This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.
