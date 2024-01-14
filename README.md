The zip file in this repository contains my CS 50 final project dating from December 2023.

My project consists of a 2D top-down single player game where players battle enemy planes and destroy gas stations in an effort to save the forest.
I developed the game using the Godot game engine, and the code is written in GDScript.

The game is not currently officially released, but it can be downloaded and run along with all the assets.
To play the game, you will have to download Godot (for free) and run the game from 
the editor. This way, you can see all the scenes and code used in my game.
Most of my work is contained in the World.tscn scene, but clicking
through other scenes will reveal more snippets of connect code.

When playing game, you will run around using w a s d, sprint using shift, 
attack using space, and interact with objects using e. The goal is to find and explode
all gas stations scattered across the map. Each gas station is locked behind a gate.
Two of the gates can be opened using keys hidden around the map. One gate opens when the
player wins a race with the character in the bottom left. The final gate opens by building
enough strength (through leveling up) to break down the gate. 

Along the way, enemy airplaness scattered in the forest shoot "green houses" at the player. 
Players can fight back by pressing the spacebar to punch. Defeating enemies will grant 
experience. Accumulating experience will cause the player to level up, dealing more
damage with each attack.

NOTE: The hitboxes for attacking are somewhat finicky. In order to damage the plane 
enemies or interact with entities, you have to press the attack or interact key
before moving into the enemy or entity. For that reason, it is easiest to attack 
enemies while running.

NOTE: Not all of the gates currently work. I may fix the gates in a future update.

Here is a YouTube video demonstrating the mechanics of the game: https://youtu.be/SHWMWGAJttY 

