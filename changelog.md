# Changelog
===============

All notable changes to this project will be documented in this file.


## [Unreleased] - TBD

### Added 

+ Official release file for Minecraft version 1.20.1 


## [0.2.0] - 2024-11-17 : Beta v2 Update!

### Added

+ Bingo 0.2.0 for Minecraft version 1.20.1
+ Bingo Game Screens
+ Bingo Loot datapack
+ Bingo Collectibles datapacks
+ Bingo language translations

#### Files

+ Bingo game file
+ Bingo card file
+ Bingo client/server save files
+ Bingo networking files
+ Bingo screen files
+ Bingo key binding file
+ Bingo commands file
+ Custom collectibles easy datapack
+ Custom collectibles medium datapack
+ Custom collectibles hard datapack
+ Loot table files:
	* data/bingo/loot_tables/square.json
	* data/bingo/loot_tables/winner.json
+ Bingo English version language file
+ Bingo French version language file

Download Language Specification: [en_us.json](https://github.com/J78FDK42/Bingo-1.18.2/blob/Version-0.2.0/en_us.json)

#### Minecraft GUI

+ Bingo Card screen
+ Bingo Winners screen
+ Bingo Start screen
 
#### Advancement Options Tab

+ Include/exclude recipe advancements in the game
+ Include/exclude vanilla advancements in the game
+ Include/exclude custom advancements in the game

#### Card Options Tab

* Personal - All players have individual randomized cards
* Team - All players on the same team have the same randomized card
* Global - All players have the same randomized card

#### Progress Options Tab

* Personal - Squares unlock for each individual player
* Team - Squares unlock for each player on the same team (except neutral)
* Global - Squares unlock for all players in the session
* Loot Generation - Loot is Generated for square and game completion using the bingo loot table

#### Teams Tab (optional)

+ Join Team Neutral (no team)
+ Join Team Red
+ Join Team Blue

#### Key Bindings
+ View Bingo card key `'o'`
+ View Start and Config key `'b'`

#### Minecraft item

`bingo:bingo_card`
+ right click / view card

#### Minecraft Commands

+ `bingo start` starts the game
+ `bingo stop` cancels any game in progress
+ `bingo reset` same as `bingo stop` to cancel a game in progress
+ `bingo start` starts the game for all active players
+ `bingo players` lists all active players in the session
+ `bingo add -player- red|blue` adds the player to the list of active team players
+ `bingo join red|blue` adds the player to the list of active team players
+ `bingo quit team` leaves the current team and joins the neutral team
+ `bingo toggle loot` toggles game loot generation on or off


[0.2.0]: https://github.com/J78FDK42/Bingo/raw/1.20.1-2.0b/bingo-0.2.0b-forge-1.20.1.jar
