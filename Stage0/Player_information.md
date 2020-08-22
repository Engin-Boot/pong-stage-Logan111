# player information

## Feature

Able to create, rename and statistics

### Scenario: how to create a new player

  Given the game is launched and player haven't registered yet

  When the player press "Create new player" option

  Then the player gets registered

### Scenario: how to rename a player

  Given the game is launched and player had already registered

  When the player press "Rename" option

  Then the palyer is able to rename
  
### Scenario: how to view player stats

  Given the game is aunched and player is interested to see his stats

  When the player press "View stats" ption

  Then the player is able to view his last 10 matches results
