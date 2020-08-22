# Update Player 1 Score

## Feature

updates the player 1 score.

## Acceptance Criteria

### Scenario: ball got escaped from player 2 slab
  Given the ball is moving and player 1
  and player 2 are active

  When ball gets escaped from player 2 slab.

  Then this module updates player 1 score by 1
  and calls check for win module
  and display score module.
