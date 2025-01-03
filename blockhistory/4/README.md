## Block 4 - Overview

### Key Features
- **Bitcoin Rewards**: Players can earn Bitcoin rewards by turning scrap into the deposit boxes located at Outpost or Bandit Camp
- **War Mode**: Experience the flexibility of our War Mode, where PvE and PvP players coexist seamlessly. Choose your preferred playstyle, toggle modes with a command, and explore zones with enforced gameplay modes for added variety.
- **Mine Scrap**: Find mining components and cooling equipment to mine Scrap in your base
- **Battlepass**: We've introduced a new Battlepass function that will let you complete daily tasks to earn Tangerine points to spend on new mining equipment!

### Server Environment Variables
- **Map Size**: 4500, procedurally generated.
- **Map Seed**: 1294480923.
- **PVP Server**: Base protection is enabled, with specific rules outlined below.
- **Team Limits**: Maximum of 8 players per team.
- **Tool Cupboard (TC) Limit**: 3 TCs per player.
- **Max Players**: 50 players at one time.
- **Region**: North America.
- **Gather Rate**: Vanilla.
- **Crafting Speed**: Vanilla.
- **Decay Rate**: Vanilla.

### War Mode Details

- **Dynamic Gameplay**: Players can choose between PvE and PvP modes, ensuring everyone has an experience tailored to their preferences.
- **Customizable Protections**: PvE players enjoy specific protections and restrictions to maintain a balanced gameplay environment. Going PvP removes these protections and leaves your base raidable!
- **Zone-Specific Modes**: Certain areas, such as monuments or custom zones, enforce PvP mode.
- **Toggle On-Demand**: Players can use the /flag command to switch between PvE and PvP modes, when they are in safe zones.
- **Team Dynamics**: Be cautious when forming teams. If one teammate switches to PvP mode, the entire team is automatically placed into PvP mode as well. Coordination and trust are key to maintaining your preferred playstyle.

### Server Events
- **Custom Raidable Bases**: Raidable bases are present with special loot, providing new raid challenges for players.
- **Convoy**: A group of outsiders are leading a convoy through the map. Stop them and steal their loot for a chance at big rewards!
- **Sputnik**: Satellite fragments will crash-land across the map, guarded by helicopters, NPCs, and turrets. Players must use Space Cards to access high-value loot.
- **Dungeon Bases**: Dungeons are bases with puzzles, NPC defenders, turrets and more all one portal away.

### Mining and Rewards
- **Satoshi Reward Pool**: Players will compete for a total of 100,000 Satoshis in rewards, generously provided by Orangemart, our main sponsor for this wipe.
- **Scrap Mining**: Scrap can be generated via mining rigs or earned from various in-game events.
- **Bitcoin Rewards**: Earn Bitcoin by turning in Scrap at one of the Deposit Centers. The more scrap you submit, the greater your share of the prize pool.

### Wipe Schedule
- **Map Wipe**: The map will wipe on the first Thursday of every month, with the next wipe scheduled for Thursday, February 6th, 2025.
- **Blueprint Wipe**: Blueprints wipe alongside the map, the next blueprint wipe is also scheduled for Thursday, February 6th, 2025.

## Changelog for Block 4
- **01/02/2025**: Block 4 begins.
- **02/02/2025**: Block 4 Scrap Deposits Close
- **02/06/2025**: Block 4 ends.

## Logs and Additional Information
- [Scrap Deposit Logs](./depositboxlog.json)
- [Claim Rewards](./ClaimPlayerRewards.json)

## Plugins Used in Block 3
- **AdminPanel.cs**: Provides an in-game admin panel for managing the server.
- **AdminRadar.cs**: Tracks players and items for admin use.
- **AlphaLoot.cs**: Modifies loot tables and spawn rates.
- **Battlepass**: Creates a daily Battlepass for new rewards.
- **BetterChat.cs**: Manage chat groups, customize colors, and add titles.
- **BetterChatFilter.cs**: Chat filter based on keywords for Better Chat.
- **BetterChatMute.cs**: A simple chat mute system, for use with Better Chat or standalone.
- **BiPlane.cs**: Allows players to use simple in-game aircraft.
- **BuyableTugboats.cs**: This plugin adds an option to purchase Tugboats from Fishing Village.
- **ChaosExtensionDownloader.cs**: Manages Chaos extensions for the server.
- **ClaimPlayerRewards.cs**: Handles /claim command for claiming blood or rewards.
- **Convoy.cs**: Enables the Convoy event.
- **CopyPaste.cs**: Enables admins to copy and paste structures.
- **CupboardLimiters.cs**: Limits the number of TCs a player can place.
- **CustomVendingSetup.cs**: Customizes vending machines for in-game services.
- **DefaultRadioStation.cs**: Sets up default radio stations for players.
- **DepositBox.cs**: Manages scrap deposits for rewards.
- **DiscordAuth.cs**: Connects in-game profiles with Discord.
- **DiscordChat.cs**: Allows players to chat between discord and the game server.
- **DiscordCore.cs**: Creates a link between a player and a Discord server.
- **DiscordLogger.cs**: Logs events to Discord channels using webhooks.
- **DiscordMessages.cs**: Sends report and ban messages straight to Discord.
- **Discord Presendce**: Shows server status in Discord.
- **DynamicPVP.cs**: Handles our dynamicPVP zones at monuments.
- **GoodMorningBitcoin.cs**: Displays 'Now Playing' information for GoodMorningBitcoin.com.
- **ImageLibrary.cs**: Renders custom user interfaces for plugins.
- **InventoryViewer.cs**: Allows admins to manage player inventories.
- **MinerFarm.cs**: Adds a Bitcoin reward system for in-game activities.
- **MonumentAddons.cs**: Adds features to standard monuments.
- **MonumentFinder.cs**: Helps players locate monuments.
- **NoGiveNotices.cs**: Suppresses notifications when items are given.
- **NpcSpawn.cs**: Manages NPC spawns at monuments.
- **Orangemart.cs**: Handles Bitcoin payment integration
- **PermissionsManager.cs**: Allows easy management of player permissions.
- **PlaceholderAPI.cs**: Centralized location to query data from other plugins.
- **PlayerAdministration.cs**: Manages player accounts, bans, and tasks.
- **RadioStationManager.cs**: Manages in-game radio stations.
- **RaidableBases.cs**: Adds bases that can be raided.
- **RemoverTool.cs**: Allows players or admins to remove structures.
- **ServerInfo.cs**: Displays essential server information.
- **ServerPop.cs**: Tracks server population in real-time.
- **SignArtist.cs**: Lets players upload custom images to signs.
- **SkinBox.cs**: Provides access to item skins.
- **Sputnik.cs**: Enables the Sputnik event.
- **StackModifer.cs**: Enables editing of stack sizes.
- **TruePVE.cs**: Enables PvE environment on server.
- **UpdateChecker.cs**: Checks for plugin updates automatically.
- **Vanish.cs**: Allows admins to become invisible to players.
- **VendingMachineLogs.cs**: Logs vending machine transactions.
- **ZoneManager.cs**: Manages safe and PvP zones on the map.
- **Zone PVx Info**: Shows a HUD on PvE/PvP name defined zones
