# Interaction Sequences

## Startup Sequence

Start_game-->Collision_Check-->Scoring-->Stop_game

## Movement Initiation

when the player starts the game, the start game modules finds the opponent for the player. When the opponent is found it calls move_ball module which starts moving the ball.
Move_paddle module is called When the game is started and when player tries to scroll the paddle is moved in the same direction.
Collision_Check checks for the collisions and if there is a collision between ball and paddle then it increases the scoring module is called to update the score of the player, and if there is a collision between ball and vertical wall which indicates that the ball is missed then the game is stopped and the scores of the two players is gathered and winner is declared.

## One score

When there is a collision between ball and the paddle Collision_check module interacts with the Scoring module and updates the score.
