# Test Case 

## Test Details

* Test Case ID:
  * 3
* Test Case Name:
  * Load Game
* Component: 
  * The operation of loading to resume the game from a saved point.
* Test Case Designer:
  * Aaron Island
* Creation Date:
  * October 17th, 2017
* Modified By:
  * Aaron Island
* Modified Date:
  * October 24th, 2017
* Requirements Covered:
  * Game Engine Requirement
  * New Game Requirement
  * Save Game Requirement
* Test Description/Purpose:
  * Allowing the player to load the game from the saved file to continue their progress.
* Pre-Test Conditions:
  * Need to make sure that the engine for the game is operating.
  * Need to have a game prepared and ready to play.
  * Game must have been saved at least once.
  
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Only works in story mode. | Game can be loaded up by player in single player mode. Game is loaded from a database on multiplayer mode. | (√) |			
| 2 | The file needs to exist. | If there is no file to load, the game cannot be continued since there is no game to begin. | (√) |			
| 3 | The save file must be able to be read by the load function. | If the save file is corrupted or uses wrong formatting it will not be permitted to load or it will crash, so the game must be able to be read correctly. | (√) |			
	

## Overall Test Status:



## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | October 24th, 2017 | 5:15:05 AM | (√) |					
