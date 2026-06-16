# Assignment 03 — Monty Hall Problem

## Problem
Simulate the Monty Hall problem: a car is hidden behind one of 3 doors.
The player picks a door, the host opens a losing door, 
and the player decides to stay or switch.

## Strategies
| Sheet          | Strategy                        | Win Probability |
|----------------|---------------------------------|-----------------|
| strategy_stay  | Player keeps original choice    | ~33%            |
| strategy_switch| Player switches to other door   | ~66%            |

## Key Insight
The host's action is not random — he always reveals a losing door.
This makes switching strictly better than staying.
