# Fireball Test Plan

# Summary
Testing of this game should ensure that inputs work correctly, the menus go to their designated areas, and the fireball does its primary applications such as:
* Being able to ignite and melt blocks, as well as making sure the "slam" function efficiently does its intended purpose (this requires a test on block types as well.).
* Assuring the fireball does not lag its inputs when pressed, and that the reset button complies.
* Testing that the endgoal (a torch) allows the player to end the stage.
* Making sure the Chain Size counter doesn't obscure the player.

# Environment/User Community
We will be testing on a PS2 in the test room near the classroom. This game will stick to the PS2 throughout its lifespan.

# Test Objectives
* Pressing X to jump without a delay.
* Pressing Square or Circle to slam onto the ground and explode.
* Pressing Triangle to allow top down view whilst jumping.
* Assuring that holding Select for 0.5 seconds to reset the level.
* Moving the player with the forward analog button.
* Pressing L1 to strafe left and L2 to turn left.
* Pressing R1 to strafe right and R2 to turn right.
* Igniting each block to make sure which burn and which melt properly.
* Getting to the torch and assuring that the player gains the "win" state.
* Playing a level with a giant chain possibility to check for certain Chain will not obscure the player's view.

# Acceptance Criteria
I expect about 2 defects will take place, but they will be minor and acceptable. 

# References
[Fireball Core Design Document (Do Not Click.)](https://alamo.instructure.com/courses/1057715/files/115295612/download?verifier=k6x3qpf3m6D0ryJBittsmYikCz4MRCTdXw7GMsSx&wrap=1)

# Test Description
For movement purposes, we need to be able to manuever around the level with the LR buttons, pressing forward to continue the correct path. For exploration and uses of the game's gimmick, the play buttons are needed to jump and handle the game's main mechanic, and resetting is necessary as there is no proper game over. As for the game itself, we need to make sure the player can play and win the game without any distractions whatsoever.

# Test Team
John Doe - Menu Tester
Joe Smith - Level Rundown, Button Tester
Aaron Island - Test Plan Scribe

# Milestones
All testing is to be done at least 4 hours a week, and we should be finished by next month.

# Budgets
The testing will be done as classwork without monetary gain.

# Testing

## Requirements
1 PS2, 1-2 Controllers, 1 Fireball (Hidama) game, paper or Github/Google Docs for note taking, tester willing to play through levels for data (Joe Smith) 

## Testing Materials/Test Tools
Only really need the Github/Google Doc for documentation.

## Test Training
Joe will be playtesting while he tests for the level's general concepts. No training

# Requiement Specifications

# Business Rules/Functions
* N/A

# Software/Game Functions
* Playstation 2 (Controller included)

# Test/Function Relationships
 | Test | Functions |
 | Game Controls | The Select button held for .5 seconds will reset the level. |
 | Game Controls | The L/R1 buttons strafe the player, while the L/R2 buttons move the character 90 degrees |
 | Game Controls | The Forward button on the analog buttons will propel the player forward. |
 | Game Controls | The X button will make the character jump, triangle button will make the character jump but will swap to top down. |
 | Game Controls | The Square and Circle button will allow the player to Slam and explode. |

# Test Progression
From one test to another, each button works together and not against each other, and flow well.
