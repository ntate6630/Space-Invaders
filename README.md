# Space-Invaders
A Space Invaders game written in Z180 assembler

#### Progress so far

Codeing underway on the SC126 - A Z180 based computer.
Working Display driver using some Z180 specific instructions. 
Many routines like "copyGameRAMtoScreenRAM", "drawTurret", "drawHouses", "drawAliens", "clearScreen", "moveTurret", "fireShot", "moveShotUp", "moveAliens" are finished and working.
players turret movable left and right. 
Player can fire shots and hit aliens.
The aliens get deleted and the score is incremented.


ToDo

Add generator of random numbers 1 to 6 for randomly selecting one of the six aliens to fire back at the player.
Add "moveAlienShotDown" routine.
Add "moveAliensDown" a row after so many repetitions of the "mainLoop". (to be decided).
Add collision detection routine for the alien shot when any of three conditions occur.
Add sounds, for player and alien fire and explosions for a hit.
Add code tidyup and optimizations.

