# Tangerine Rust Server - Plugins

This document provides an overview of the plugins that power the Tangerine Rust Server, enhancing gameplay, moderation, and server functionality. Each plugin has been carefully selected to offer a balance of engaging events, Bitcoin integration, and administrative tools to ensure smooth operations. Whether it’s creating dynamic PvP zones, enabling Bitcoin mining, or managing in-game events like Raidable Bases and Sputnik, these plugins are vital to our unique server experience.

For details on how each plugin is configured, you can view the [Plugin Configurations](/plugins/config/) for an in-depth look at the settings that tailor our server to its current setup.

## Plugins List

### Gameplay Enhancements

- [AlphaLoot.cs](https://chaoscode.io/resources/alphaloot.13/): Modifies loot tables and spawn rates, allowing for customized loot distribution in crates and barrels.
- [DynamicPVP.cs](https://umod.org/plugins/dynamic-pvp): Handles our dynamicPVP zones at monuments
- [RemoverTool.cs](https://umod.org/plugins/remover-tool): Allows players or admins to remove placed structures or objects for a fee or free.
- [SkinBox.cs](https://chaoscode.io/resources/skinbox.17/): Provides players with access to skins for their items via the SkinBox plugin.
- [WarMode.cs](https://codefling.com/plugins/war-mode-pvppve): Enables PvE/PVP split environment on server.

### Events & Challenges

- [ClaimPlayerRewards.cs](https://github.com/goodmorningbitcoin/Claim-Player-Rewards): Handles the /claim command for players to claim blood or other rewards based on performance in the wipe.
- [Convoy.cs](https://codefling.com/plugins/convoy-reforged): A plugin for spawning Convoys of NPCs on the roads
- [DepositBox.cs](https://github.com/goodmorningbitcoin/DepositBox): Manages the deposit of hash (represented as paper) into specific boxes for rewards and events.
- [DungeonBases.cs](https://codefling.com/plugins/dungeon-bases): Dungeons are bases with puzzles, NPC defenders, turrets and more. 
- [MiningFarm.cs](https://codefling.com/plugins/miningfarm): Manages Bitcoin mining for the server
- [RaidableBases.cs](https://lone.design/product/raidable-bases-rust-plugin/): Adds bases to the game that players can raid, either as pre-built locations or admin-spawned events.
- [Sputnik.cs](https://lone.design/product/sputnik/): A plugin for spawning satellite-like objects in-game, offering high-value loot guarded by defenses.

### Utility Plugins

- [Battlepass.cs](https://codefling.com/plugins/battlepass): Creates new daily challenges for players to earn rewards.
- [BetterChat.cs](): Manage chat groups, customize colors, and add titles.
- [BetterChatFilter.cs](): Chat filter based on keywords for Better Chat.
- [BetterChatMute.cs](): A simple chat mute system, for use with Better Chat or standalone.
- [BiPlane.cs](https://lone.design/product/biplane-rust-plugin/): Allows the creation and deployment of simple in-game aircraft for enhanced mobility.
- [BuyableTugboats.cs](): This plugin adds an option to purchase Tugboats from Fishing Village.
- [CopyPaste.cs](https://umod.org/plugins/copy-paste): Enables admins to copy and paste structures in the game world, useful for building event arenas or saving player builds.
- [CupboardLimiters.cs](https://umod.org/plugins/cupboard-limiter): Limits the number of tool cupboards a player or team can place, balancing building control.
- [CustomVendingSetup.cs](https://umod.org/plugins/custom-vending-setup): Customizes vending machines to sell specific items or services.
- [DefaultRadioStation.cs](https://umod.org/plugins/default-radio-station): Sets up default radio stations for players to tune into in their bases or vehicles.
- [DiscordChat.cs](): Allows players to chat between discord and the game server.
- [DiscordCore.cs](): Creates a link between a player and a Discord server.
- [DiscordLogger.cs](): Logs events to Discord channels using webhooks.
- [DiscordMessages.cs](): Sends report and ban messages straight to Discord.
- [DiscordPresence.cs](): Shows server status in Discord.
- [MonumentAddons.cs](https://umod.org/plugins/monument-addons): Enhances or modifies the standard monuments with new features or interactions.
- [Orangemart.cs](https://github.com/rustysats/orangemart.cs): Handles Bitcoin payment integration
- [RadioStationManager.cs](https://umod.org/plugins/radio-station-manager): Manages in-game radio stations.
- [SignArtist.cs](https://umod.org/plugins/sign-artist): Allows players to upload custom images to in-game signs, useful for personalizing bases.
- [StackModifier.cs](): Enables editing of stack sizes.
- [TwigDecay.cs](): Forces twig to decay regardless if a TC has wood in it.
- [WarModeSpawnUI.cs](): First spawn prompt for users to choose if they want to be PVP or PVE

### Server Information

- [DiscordAuth.cs](https://umod.org/plugins/discord-auth): Connects players’ in-game profiles to Discord for easier verification and integration with the community.
- [GoodMorningBitcoin.cs](): Displays 'Now Playing' information for GoodMorningBitcoin.com.
- [ServerInfo.cs](https://umod.org/plugins/server-info): Provides players with essential server information, such as rules, commands, or event schedules.
- [ServerPop.cs](https://codefling.com/plugins/server-pop): Tracks and displays server population statistics in real-time, helping admins gauge player activity.
- [VendingMachineLogs.cs](https://umod.org/plugins/vending-machine-logs): Logs all transactions made at vending machines for tracking and balancing the in-game economy.
- [WarModeRulesUI.cs](): Allows players to see what restrictions they have for their mode

### Administration & Moderation

- [AdminPanel.cs](https://umod.org/plugins/admin-panel): Provides an administrative panel for in-game server management.
- [AdminRadar.cs](https://umod.org/plugins/admin-radar): An admin tool to track players and items on the map for rule enforcement.
- [InventoryViewer.cs](https://umod.org/plugins/inventory-viewer): Allows admins to view and manage players’ inventories for moderation and rule enforcement.
- [NoGiveNotices.cs](https://umod.org/plugins/no-give-notices): Suppresses notifications in the chat when players are given items.
- [PermissionsManager.cs](https://codefling.com/plugins/permissions-manager): Allows admins to easily manage player permissions and access.
- [PlayerAdministration.cs](https://umod.org/plugins/player-administration): A suite of tools for managing player accounts, bans, and other admin-related tasks.
- [Vanish.cs](https://umod.org/plugins/vanish): Allows admins to vanish from player view for covert moderation.
- [WarModeAdminPanel.cs](): Allows admins to update mode rules

### Miscellaneous

- [ChaosExtensionDownloader.cs](https://chaoscode.io/resources/chaos.321/): A utility to download and manage Chaos extensions for customizable mods.
- [ImageLibrary.cs](https://umod.org/plugins/image-library): A library that helps render custom user interfaces for plugins.
- [MonumentFinder.cs](https://umod.org/plugins/monument-finder): Helps plugins locate monuments on the map, making it easier to find key locations.
- [NpcSpawn.cs](https://codefling.com/extensions/npc-spawn): Manages the spawning of NPCs at monuments or around the map.
- [PlaceholderAPI.cs](): Centralized location to query data from other plugins.
- [UpdateChecker.cs](https://codefling.com/plugins/update-checker): Automatically checks for updates to installed plugins, ensuring the server is running the latest versions.
- [WarModeBadges.cs](): Customizable UI elements that display PVE/PVP
- [ZoneManager.cs](https://umod.org/plugins/zone-manager): Manages different zones on the map, such as safe zones or PvP zones, with different rules.
