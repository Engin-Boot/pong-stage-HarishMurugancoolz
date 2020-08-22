# Check For Win

## Feature

Checking which player won the game

## Acceptance Criteria

### Scenario: when player 1 score is 50

  Given player 1 and player 2 are active
  and ball is moving

  When player 1 scored 50 points

  Then update the player 1
  and player 2 score is set
  to zero and declare the
  display message as player 1 won.

### Scenario: when player 2 score is 50

  Given player 1 and player 2 are active
  and ball is moving

  When player 2 scored 50 points

  Then update the player 1
  and player 2 score is set
  to zero and declare the
  display message as player 2 won.
