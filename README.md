# Earthbound-1
My first full project: A minigame based on Onett, the first part of Earthbound

This is a fairly straightforward game, based on the RPG style of earthbound. Press Space Bar to attack enemies, eliminate those enemies to gain EXP, 
and gain a new player level whenever a target EXP quantity is reached. HP is displayed in the top right corner and is depleted when player is in range of an 
enemy or (moreso) when player collides with an enemy. When HP reaches 0, game is over. Some enemies drop hamburgers, which can increase hp by 5. 
New features are introduced at different player levels:

At level 3, a PSI "powerup" system is enabled. Butterflies appear, and when touched, butterflies give player one of two "PSI Moves". 
Player can only have one PSI Move at a time, and contact with a second butterfly will override a currently held PSI Move. Pressing V "uses" 
the PSI Move: "PSI Rockin'" tries to destroy each enemy on screen, with a 90% success rate, and garners the player 50% EXP from destroyed enemies 
(rounded up). "PSI Life Up" restores HP, adding between 10 and 14 HP per use (without exceeding Max HP).

At level 4, "Sharks," a stronger enemy type, are added to the enemy spawn pool (and frequency of weaker enemies is reduced slightly).

At level 5, a random EXP quantity is set, and once that EXP is reached, the boss battle is triggered. At this point the current enemies run from the boss,
Frank, and player fights Frank much like he did the other enemies.



It features a collage of free artwork I got from the Unity Asset Store and elsewhere on the web, so it's not exactly pretty. The code is limited,
as it only features what I've learned from the first five modules of the Junior Programmer tutorial track, and a few other things I was savvy enough to google
and really understand.
