# Command Line Monsties
### An exercise in lean gameplay design

A simple game based on the basic battle mechanics of Monster Hunter Stories

## Iteration One: Type-determined Win/Loss

In Monster Hunter, there are three types of attacks: Power, Speed, Technical.

Power beats Technical, Technical beats Speed, and Speed beats Power. Don't ask me why.

Given a face-off between two monsters, the monster who chooses the stronger in the match-up wins; otherwise there is a draw.

## Iteration Two: Multiple turns, fixed Health Points, damage pegged to typed win/loss

In a real Monster Hunter battle, there will be several rounds of combat.

In a simple model of this, every monster should begin with 10 HP. In a draw, both monsters lose 1 HP. If a monster loses a match-up, it loses 2 HP.

The first monster to 0 HP loses the battle.
