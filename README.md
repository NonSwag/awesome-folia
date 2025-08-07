# Awesome Folia

[Folia](https://papermc.io/software/folia) is a fork of [Paper](https://papermc.io/software/paper) that divides the
world into separate regions, each running on its own thread.
This significantly improves performance by utilizing more CPU cores.
Since a standard Minecraft world can only use one thread, Folia allows for much larger worlds with more players, making
it perfect for big servers like SMPs or SkyBlock.

However, many plugins are designed to run on a single thread and, as a result, won't work on Folia.
This list aims to highlight plugins and projects specifically made, optimized, or targeted for Folia servers,
developers, and administrators.
The goal is to bring attention to both these projects and to Folia itself.

_This list is inspired by [BlockhostOfficial/folia-plugins](https://github.com/BlockhostOfficial/folia-plugins),
which has been unmaintained for a while._

---

## Plugins

Here is a list of plugins that actively support Folia

### Utility

| Name               | Source                                                          | Download                                                           | Official | Description                                                                                                                  |
|--------------------|-----------------------------------------------------------------|--------------------------------------------------------------------|----------|------------------------------------------------------------------------------------------------------------------------------|
| AdvancedServerList | [Codeberg](https://codeberg.org/Andre601/AdvancedServerList)    | [Modrinth](https://modrinth.com/project/xss83sOY)                  | ✅        | A plugin to display a custom MOTD, Player count text, player count hover and Favicon using conditions and priorities.        |
| BetterBoard        | [GitHub](https://github.com/HSGamer/BetterBoard)                | [SpigotMC](https://www.spigotmc.org/resources/betterboard.96393/)  | ✅        | A simple scoreboard plugin that is not dummy                                                                                 |
| BetterGUI          | [GitHub](https://github.com/BetterGUI-MC/BetterGUI)             | [Modrinth](https://modrinth.com/project/SekuiXMA)                  | ✅        | An animated menu, a simple menu-designing tool, or just a better GUI plugin                                                  |
| BlueMap            | [GitHub](https://github.com/BlueMap-Minecraft/BlueMap)          | [Modrinth](https://modrinth.com/project/swbUV1cr)                  | ✅        | A Minecraft mapping tool that creates 3D models of your Minecraft worlds and displays them in a web viewer.                  |
| Chunky             | [GitHub](https://github.com/pop4959/Chunky)                     | [Modrinth](https://modrinth.com/project/fALzjamp)                  | ✅        | Pre-generates chunks, quickly and efficiently                                                                                |
| DiscordSRV         | [GitHub](https://github.com/DiscordSRV/DiscordSRV)              | [Modrinth](https://modrinth.com/project/UmLGoGij)                  | ✅        | The most powerful, configurable, open-source Discord to Minecraft bridging plugin available.                                 |
| FancyHolograms     | [GitHub](https://github.com/FancyInnovations/FancyPlugins)      | [Modrinth](https://modrinth.com/project/5QNgOj66)                  | ✅        | Create fancy looking text, item or block holograms with the new 1.19.4 text display entities                                 |
| FancyNpcs          | [GitHub](https://github.com/FancyInnovations/FancyPlugins)      | [Modrinth](https://modrinth.com/project/EeyAn23L)                  | ✅        | Simple, lightweight and fast NPC plugin using packets                                                                        |
| Floodgate          | [GitHub](https://github.com/GeyserMC/Floodgate)                 | [Homepage](https://geysermc.org/download?project=floodgate)        | ✅        | Hybrid mode plugin to allow for connections from Geyser to join online mode servers.                                         |
| Geyser             | [GitHub](https://github.com/GeyserMC/Geyser)                    | [Modrinth](https://modrinth.com/project/wKkoqHrH)                  | ✅        | A bridge/proxy allowing you to connect to Minecraft: Java Edition servers with Minecraft: Bedrock Edition.                   |
| HuskSync           | [GitHub](https://github.com/WiIIiam278/HuskSync)                | [Homepage](https://william278.net/project/husksync)                | ✅        | A modern, cross-server player data synchronisation system                                                                    |
| LibertyBans        | [GitHub](https://github.com/A248/LibertyBans)                   | [Modrinth](https://modrinth.com/project/PgXAUxLZ)                  | ✅        | Obedience is liberating                                                                                                      |
| Maintenance        | [GitHub](https://github.com/kennytv/Maintenance)                | [Modrinth](https://modrinth.com/project/VCAqN1ln)                  | ✅        | Enable maintenance mode on your Minecraft server                                                                             |
| MineStore          | [GitHub](https://github.com/ChromMob/MineStoreRecode)           | [SpigotMC](https://www.spigotmc.org/resources/minestore.109419/)   | ✅        | Plugin for MineStoreCMS working on Sponge, Bukkit, Spigot, Paper, Folia, Bungee and Velocity                                 |
| MiniMOTD           | [GitHub](https://github.com/jpenilla/MiniMOTD)                  | [Modrinth](https://modrinth.com/project/16vhQOQN)                  | ✅        | Minecraft server/proxy plugin to set the server list MOTD using MiniMessage for formatting, supporting RGB colors.           |
| MiniPlaceholders   | [GitHub](https://github.com/MiniPlaceholders/MiniPlaceholders/) | [Modrinth](https://modrinth.com/project/HQyibRsN)                  | ✅        | MiniMessage Component-based Placeholders API for Minecraft Platforms                                                         |
| Pl3xMap            | [GitHub](https://github.com/granny/Pl3xMap)                     | [Modrinth](https://modrinth.com/project/34T8oVNY)                  | ✅        | Pl3xMap is a minimalistic and lightweight world map viewer for Minecraft servers using the vanilla Minecraft rendering style |
| Plasmo-voice       | [GitHub](https://github.com/plasmoapp/plasmo-voice)             | [Modrinth](https://modrinth.com/project/1bZhdhsH)                  | ✅        | Proximity voice chat mod for Minecraft                                                                                       |
| ProtocolLib        | [GitHub](https://github.com/dmulloy2/ProtocolLib)               | [SpigotMC](https://www.spigotmc.org/resources/protocollib.1997/)   | ✅        | Provides read and write access to the Minecraft protocol with Bukkit.                                                        |
| SayanVanish        | [GitHub](https://github.com/Syrent/SayanVanish)                 | [Modrinth](https://modrinth.com/project/hkzyeLcD)                  | ✅        | A modular vanish system for Minecraft servers                                                                                |
| SimpleVoiceChat    | [GitHub](https://github.com/henkelmax/simple-voice-chat)        | [Modrinth](https://modrinth.com/project/9eGKb6K1)                  | ✅        | A working voice chat in Minecraft!                                                                                           |
| SkinOverlay        | [GitHub](https://github.com/GeorgeV220/SkinOverlay)             | [Polymart](https://polymart.org/product/3607/skinoverlay)          | ✅        | Change your skin's clothes (overlay) without opening a graphic editor and rejoining!                                         |
| TAB                | [GitHub](https://github.com/NEZNAMY/TAB)                        | [Modrinth](https://modrinth.com/project/gG7VFbG0)                  | ✅        | TAB is an all-in-one plugin for displaying information in various places                                                     |
| TAB-Bridge         | [GitHub](https://github.com/NEZNAMY/TAB-Bridge)                 | [Modrinth](https://modrinth.com/project/kG3hVbBX)                  | ✅        | An addon for TAB when it is installed on a proxy.                                                                            |
| ViaBackwards       | [GitHub](https://github.com/ViaVersion/ViaBackwards)            | [Modrinth](https://modrinth.com/project/NpvuJQoq)                  | ✅        | Allows the connection of older clients to newer server versions for Minecraft servers.                                       |
| ViaRewind          | [GitHub](https://github.com/ViaVersion/ViaRewind)               | [Modrinth](https://modrinth.com/project/TbHIxhx5)                  | ✅        | ViaVersion addon to allow 1.8.x and 1.7.x clients on newer server versions.                                                  |
| ViaVersion         | [GitHub](https://github.com/ViaVersion/ViaVersion)              | [Modrinth](https://modrinth.com/project/P1OZGk5p)                  | ✅        | Allows the connection of newer clients to older server versions for Minecraft servers.                                       |
| VotingPlugin       | [GitHub](https://github.com/BenCodez/VotingPlugin)              | [SpigotMC](https://www.spigotmc.org/resources/votingplugin.15358/) | ✅        | Most highly featured votifier listener! BungeeCord & Velocity Support! Multi-proxy support!                                  |
| WorldEdit-Folia    | [GitHub](https://github.com/Euphillya/WorldEdit-Folia)          | [GitHub](https://github.com/Euphillya/WorldEdit-Folia/releases)    | ❌        | Minecraft map editor and mod                                                                                                 |
| Worlds             | [GitHub](https://github.com/TheNextLvl-net/worlds)              | [Modrinth](https://modrinth.com/project/gBIw3Gvy)                  | ✅        | World management plugin for modern Paper and Folia servers                                                                   |
| mclo.gs            | [GitHub](https://github.com/aternosorg/mclogs-integration)      | [Modrinth](https://modrinth.com/project/6DdCzpTL)                  | ✅        | A mod/plugin to easily share and analyse your server logs with mclo.gs                                                       |
| motd.gg            | [GitHub](https://github.com/aternosorg/motdgg-bukkit/)          | [Modrinth](https://modrinth.com/project/VPo0otUH)                  | ✅        | Quickly upload your current MOTD and server icon to motd.gg to edit or share them.                                           |

### Security & Anti-Cheat

| Name                   | Source                                                       | Download                                                                         | Official | Description                                                                                                                               |
|------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------|
| CleanScreenShare       | [GitHub](https://github.com/frafol/CleanScreenShare/)        | [Modrinth](https://modrinth.com/project/KSHzrYFK)                                | ✅        | Proxy based ScreenShare plugin. Fast and network ready.                                                                                   |
| Coordinates Obfuscator | [GitHub](https://github.com/cavallium/CoordinatesObfuscator) | [Modrinth](https://modrinth.com/project/Tl1Qr93A)                                | ✅        | Hide the real coordinates to the players.                                                                                                 |
| Freeze                 | [GitHub](https://github.com/SirBlobman/Freeze)               | [Hangar](https://hangar.papermc.io/SirBlobman/Freeze)                            | ✅        | A moderation plugin that prevents players from moving and doing certain actions.                                                          |
| Grim                   | [GitHub](https://github.com/GrimAnticheat/Grim)              | [Modrinth](https://modrinth.com/project/LJNGWSvH)                                | ✅        | Fully async, multithreaded, predictive, open source, 3.01 reach, 1.005 timer, 0.01% speed, 99.99% antikb, "bypassable" 1.8-1.21 anticheat |
| InvSee++               | [GitHub](https://github.com/Jannyboy11/InvSee-plus-plus)     | [Modrinth](https://modrinth.com/project/bYazc7fd)                                | ✅        | A bukkit plugin for manipulating player inventories.                                                                                      |
| NoCheatPlus            | [GitHub](https://github.com/Updated-NoCheatPlus/NoCheatPlus) | [Jenkins](https://ci.codemc.io/job/Updated-NoCheatPlus/job/Updated-NoCheatPlus/) | ❌        | Anti-cheating plugin for Minecraft (1.5-1.21, Bukkit/Spigot)                                                                              |
| Panilla                | [GitHub](https://github.com/ds58/Panilla)                    | [SpigotMC](https://www.spigotmc.org/resources/65694/)                            | ✅        | Prevent abusive NBT and crash packets on a Minecraft server                                                                               |

## Alternative Plugins

Here is a list of alternatives or forks of well-known plugins that officially do not support Folia,
that I deem mentionable.

| Plugin                                         | Alternative      | Source                                                  | Download                                                         | 
|------------------------------------------------|------------------|---------------------------------------------------------|------------------------------------------------------------------|
| [EssentialsX](https://essentialsx.net/)        | Tweaks           | [GitHub](https://github.com/TheNextLvl-net/tweaks)      | [Modrinth](https://modrinth.com/project/HLkJsjy0)                |
| [Multiverse-Core](https://mvplugins.org/core/) | Worlds           | [GitHub](https://github.com/TheNextLvl-net/worlds)      | [Modrinth](https://modrinth.com/project/gBIw3Gvy)                |
| [Vault](https://github.com/milkbowl/Vault)     | ServiceIO        | [GitHub](https://github.com/TheNextLvl-net/service-io)  | [Modrinth](https://modrinth.com/project/MNPyHOe7)                |
| [WorldEdit](https://enginehub.org/worldedit)   | WorldEdit-Folia  | [GitHub](https://github.com/Euphillya/WorldEdit-Folia)  | [GitHub](https://github.com/Euphillya/WorldEdit-Folia/releases)  |
| [WorldGuard](https://enginehub.org/worldguard) | WorldGuard-Folia | [GitHub](https://github.com/Euphillya/WorldGuard-Folia) | [GitHub](https://github.com/Euphillya/WorldGuard-Folia/releases) |

## Libraries

| Name          | Source                                                | Download                                                     | Description                                                                                        |
|---------------|-------------------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| BlueSlimeCore | [GitHub](https://github.com/SirBlobman/BlueSlimeCore) | [Hangar](https://hangar.papermc.io/SirBlobman/BlueSlimeCore) | A useful library plugin that includes lots of helpful code and API features.                       |
| FurnitureLib  | [GitHub](https://github.com/Ste3et/FurnitureLib)      | [Modrinth](https://modrinth.com/project/DqcgUFzu)            | FurnitureLib is a library for Spigot Servers to handle 3d modeling with armor-stands over packets. |
| Item-NBT-API  | [GitHub](https://github.com/tr7zw/Item-NBT-API)       | [Modrinth](https://modrinth.com/project/nfGCP9fk)            | Add custom NBT tags to Items/Tiles/Entities without NMS!                                           |
| PacketEvents  | [GitHub](https://github.com/retrooper/packetevents)   | [Modrinth](https://modrinth.com/project/HYKaKraK)            | A powerful networking library for Minecraft packet processing and manipulation.                    |

## Find more Folia plugins

- [Modrinth](https://modrinth.com/plugins?g=categories:folia)
- [Hangar](https://hangar.papermc.io/?tag=SUPPORTS_FOLIA&sort=-stars)