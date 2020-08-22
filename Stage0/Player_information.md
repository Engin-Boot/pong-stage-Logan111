# player information

## Feature

Able to create, rename and statistics

## Acceptance Criteria

### Scenario: Create a new plyer

  Given the game is launched and player haven't registered yet

  When the player press "Create new player" 

  Then the player gets registered

### Scenario: Rename a  plyer

  Given the game is launched and the player had already registered 

  When the player press "Rename" 

  Then the player is able to rename
  
### Scenario: To view statistics

  Given the game is launched and player is interested to see his stats

  When the player press "View Stats" 

  Then the player is able to view his last 10 matches results
  
