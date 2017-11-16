# Test Case 

## Test Details

* Test Case ID:
  * TD8 Case P
* Test Case Name:
  * Player Mechanics
* Component: 
  * Mechanics the player character uses for stages in The Devil's Eight.
* Test Case Designer:
  * Aaron Island
* Creation Date:
  * November 16th, 2017
* Modified By:
  * Aaron Island
* Modified Date:
  * November 16th, 2017
* Requirements Covered:
  * Game Engine Requirement
  * Tutorial Requirement
  * Player Movement Requirement
* Test Description/Purpose:
  * Testing the functionality of the player's abilities and reactions to the stage and attacks.
* Pre-Test Conditions:
  * Game engine must be operational and started.
  * Tutorial must be completed to start/load a level.
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | If the player blocks an attack successfully, then their health will rise and the enemy will sustain damage. | Blocking an attack will reflect damage or said attack to the attacker and heal the player by a flat amount. | (√) |			
| 2 | If the player does not block an attack correctly, then they take damage and stagger (depends on strength of attack). | If the player is unable to block an attack and takes a blow from the enemy the player will stagger backwards, fall to the ground and lose a fraction of health. | (√) |			
| 3 | When the player's health reaches zero, the player dies and the game over screen comes up. | Whenever the player has no more health, the player dies and is prompted to either retry the boss or return to the main menu. | (√) |			
| 4 | When the player blocks, they lose an icon that represents # of blocks available. | Onscreen, the player will have a set amount of blocks shown as an icon above health. The player will use one every block, and will be unable to block attacks when there are no icons left. | (√) |			
| 5 | The player's blocks will passively regenerate every few seconds. | Approximately every 8 seconds, the player will recieve a new block so they may retaliate once more. The player cannot have more blocks than is currently allowed. | (√) |			
| 6 | The player can recover from a hit by pressing Jump. | When the player is downed, they will be prompted to hit the Jump action to recover. | (√) |			
| 7 | Player can fall off a platform by pressing Down controls. | The player will quickly drop to the floor when down is pressed if they reside on a platform. | (√) |

## Overall Test Status:



## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | November 16th | 12:15:04 PM | (√) |			
