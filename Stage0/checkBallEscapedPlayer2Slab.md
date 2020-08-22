# Check Ball Escaped Player 2 Slab

## Feature

checks if ball escaped player 2 slab

## Acceptance Criteria

### Scenario: Ball escaping player 2 slab

  Given the ball is moving
  and player 1 and player 2
  are active.

  When ball is escaping player 2 slab.

  Then update player 1 score module gets executed.
  
  ### Scenario: Ball hits player 2 slab

  Given the ball is moving
  and player 1 and player 2
  are active.

  When ball is hits player 2 slab.

  Then reflect the ball towards the player 1 slab.
  
