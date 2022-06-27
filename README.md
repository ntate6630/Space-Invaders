# Space-Invaders
## A Space Invaders game written in Z180 assembler

### Progress so far

#####  Codeing underway on the SC126 - A Z180 based computer.
##### Working Display driver using some Z180 specific instructions. 
##### Many routines like "copyGameRAMtoScreenRAM", "drawTurret", "drawHouses", "drawAliens", "clearScreen", "moveTurret", "fireShot", "moveShotUp", "moveAliens" are finished and working.
##### players turret movable left and right. 
##### Player can fire shots and hit aliens.
##### The aliens get deleted and the score is incremented.
##### The aliens get selected to shoot from a semi-random table of data which represents the position of each alien.
##### Added "moveAlienShotDown" routine.
##### Added collision detection routine for the alien shot when any of three conditions occur, being either a house is hit, the shot reaches the bottom of display or the ##### players turret is hit.


### ToDo

##### Add "moveAliensDown" a row after so many repetitions of the "mainLoop". (to be decided).
##### Add sounds, for player and alien fire and explosions for a hit using Arduino synth module coming soon. 
##### Add "displayScore", "displayLives" at the end of the game.
##### Add code tidyup and optimizations.

