# Ball Movement

## Feature

Determines the motion of ball

## Acceptance Criteria

### Scenario: Ball moves towards player 1 slab

  Given the ball is moving
  and player 1
  and player 2 are active.

  When ball moves towards player 1 slab.

  Then check ball escaped player 1 slab module is triggered

### Scenario: Ball moves towards player 2 slab

  Given the ball is moving
  and player 1
  and player 2 are active.

  When ball moves towards player 2 slab.

  Then check ball escaped player 2 slab module is triggered
  
### Scenario: Ball moving towards the wall

  Given the ball is moving
  and player 1
  and player 2 are active
  and ball got reflected from
  either of the slabs.

  When ball is moving towards wall

  Then check for wall collision module gets executed.
