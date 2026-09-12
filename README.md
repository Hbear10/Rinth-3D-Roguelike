# Rinth
Rinth is a 3D turn-based maze roguelike.

Graphically, it takes a lot of inspiration from the likes of Doom and Wolfenstein 3D. The player traverses 3 procedurally generated floors of increasingly stronger enemies on a quest to defeat the Robot King. At the end of each floor is a boss enemy to test the player's strength. To fight these enemies, there is a turn based combat system including: basic attacks, Energy moves (i.e. a sci-fi version of magic), items, elements and a dynamic turn based system. Replacing a standard levelling up system is a relic based system where at the end of each battle the player is given a choice of 3 random relics that upgrade one of the players stats which gives the player more control over their character build. If the player dies they will have to restart without any of their relics.

This game is fully built in Python using the libraries Pygame and PIL. I created the 3D renderer using the DDA algorithm. Sprites are rendered with a step-based ray casting algorithm. The mazes are generated with a backtracking maze generating algorithm. 

To play the game you will need to open it in an IDE and install the relevant libraries.
