# Check Ball Escaped Player 1 Slab

## Feature

checks if ball escaped player 1 slab

## Acceptance Criteria

### Scenario: Ball escaping player 1 slab

  Given the ball is moving
  and player 1 and player 2
  are active.

  When ball is escaping player 1 slab.

  Then update player 2 score module gets executed.

### Scenario: Ball hits player 1 slab

  Given the ball is moving
  and player 1 and player 2
  are active.

  When ball is hits player 1 slab.

  Then reflect the ball towards the player 2 slab
 
