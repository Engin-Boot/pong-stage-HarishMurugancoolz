# Update Player 2 Score

## Feature

updates the player 2 score.

## Acceptance Criteria

### Scenario: ball got escaped from player 1 slab

  Given the ball is moving and player 1
  and player 2 are active

  When ball gets escaped from player 1 slab.

  Then this module updates player 2 score by 2
  and calls check for win module
  and display score module.
