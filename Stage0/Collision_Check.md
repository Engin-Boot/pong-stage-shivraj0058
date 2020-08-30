## Feature

Checks for the Collision of the Ball

### Scenario: Check for the Collision of the ball with wall or the paddle

  Given The game has started

  When Ball Collides with <Horizontal wall/Vertical Wall/paddle>

  Then go to the module <modulename>
  
  Examples:
    |Horizontal wall/Vertical Wall/paddle  |modulename     |
    |Paddle                                |Scorin         |
    |Vertical wall                         |Stop_game      |
