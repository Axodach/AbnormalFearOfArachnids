This project is a simple platformer game developed using the Phaser framework. The game includes various assets such as images, audio files, and JSON data for levels. 
The main character, enemies, and other game elements are loaded and managed through the PlayState object.

Getting Started
Prerequisites
To run this game, you need a web browser that supports JavaScript.

Installation
Clone the repository or download the source code.
Open the index.html file in your web browser.
Game Structure
The game consists of the following main components:

Preload: Loads all the necessary assets for the game, including images, audio files, and level data.
Create: Initializes the game world, adds background images, loads the current level, and sets up sound effects.
Update: Handles game logic, including collisions and player input.

Code Overview
Preload Function: Loads all the assets required for the game.
Create Function: Sets up the game world, including background, level data, and sound effects.
_loadLevel Function: Loads the level data and spawns platforms, characters, coins, door, and key.
_spawnPlatform Function: Creates platforms and invisible walls to block enemies.
_spawnCharacters Function: Spawns the hero and enemy characters (spiders).
_spawnCoin Function: Spawns collectible coins.
_spawnEnemyWall Function: Creates invisible walls to block enemies.
_spawnDoor Function: Spawns the door at the end of the level.
_spawnKey Function: Spawns the key required to unlock the door.

Init Function: Initializes the game state, including keyboard input and level data.
Update Function: Updates the game state, handles collisions, and player input.
Assets

Images: Various images for the hero, ground, grass, coins, spiders, door, background, and key.

Audio: Sound effects for jumping, collecting coins, stomping enemies, collecting keys, opening doors, and background music.
JSON Data: Level data stored in JSON files.

Controls - How to play!
Left Arrow: Move left
Right Arrow: Move right
Up Arrow: Jump

License
This project is licensed under the MIT License - see the LICENSE file for details
