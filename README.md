CS209: MINI PROJECT PHASE-2
THE MAZE RUNNER

SUBMITTED BY:
Pranjal Chamaria			   	                                       
2201CS55


Introduction

The maze game implemented on the DE1-SoC board with Nios II architecture offers an engaging gaming experience with three levels of increasing difficulty. This report details the design, implementation, and features of the game.

Game Overview

The game revolves around navigating a character through a maze to reach designated target coordinates. The character’s movement is controlled by user input(A, S, D, W), and the objective is to reach the target while avoiding collisions with walls.

Game Levels
The game consists of three levels of increasing difficulty. The maze of each level has been hardcoded by using the draw_level1, draw_level2 and draw_level3 functions.

Character Movement

The character’s movement is handled by updating its position based on user input. Collision detection ensures that the character cannot move through walls. If the character attempts to move into a wall, its position remains unchanged. This is facilitate by the logic that if the character touches a pixel that is green( i.e. the coulour of the wall), then the move is not permitted.
Upon reaching the target coordinates in a level, the user completes the current level and is moved to the home page allowing him to choose any other level and play the game. Meanwhile, a score variable is maintained which stores the current score of the user as follows:
+5 points for level 1
+10 points for level 2
+15 points for level 3.
	



Additional Features

To enhance the overall appearance and usability of the game, additional features have been added. These are as follows:
Homepage: Provides an overview of all available levels, allowing users to select their desired starting point.

Rule Book Page: Offers comprehensive instructions and rules for playing the game.

Conclusion

The maze game demonstrates effective use of the DE1-SoC board and Nios II architecture to create an interactive gaming experience. With its multiple levels, intuitive controls, and engaging gameplay mechanics, the game provides entertainment while showcasing the capabilities of embedded systems development.


