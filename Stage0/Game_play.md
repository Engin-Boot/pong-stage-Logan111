# Game Play

## Acceptance Criteria

Player/players with a mobile/pc having the game can play

### Scenario: How long does the players have to wait before starting

  Given the playes launched the game and waiting for the game to start

  When the player press "PLAY" option on menu

  Then a timer of 5 seconds is shown before ball triggers from any paddle

### Scenario: From which end the ball needs to be triggered initially

  Given the player launched the game and play is about to start

  When the computation produces a random integer number

  Then if the number is even, even player starts and vice-versa
  
### Scenario: Continue ball task and slider task

  Given the game is launched and players are already In game

  When the players are able to hit the ball with their paddle

  Then keep continuing the ball task and slider task
  
### Scenario: how to choose a winner

  Given the players are already in game and having some scores

  When any player score becomes equal to 9 and game stops

  Then declare that player as winner
  
### Scenario: Did any player loose

  Given the player launched game and already In game

  When any of the player misses to hit the ball with his paddle

  Then the player missed to hit will loose a point to opponent
  
### Scenario: Displaying scores when any of the player looses

  Given the player launched game and already In game

  When one of the player had lost the chance to hit the ball

  Then the display function is triggered to show scores  
