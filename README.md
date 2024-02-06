# increlement
incremental game inspired by neal.fun/infinite-craft/ and the many elemental combining games that have come before it

## plan

### elevator pitch

an incremental game where you combine things to create new things, combining gives you points you can use to automate the combining process. you win the game when you have created all things

### points gain

base gain is 10 points for a new thing, 1 point for an already discovered thing

### upgrades

- auto combiners - randomly combines found things
    - upgrading one upgrade increases the cost of all upgrades for that machine
    - can buy multiple combiners, each one more expensive
    - upgrades 
        - speed 
        - chance to try new combo
- efficient combinations - increases points earned from combining
    - additive
    - multiplicative
- cool down for time between creating things

### ui

```
===============  ============
| combining   |  | info   & |
| area        |  | discovery|
|             |  | history  |
===============  ============
=============================
|    upgrades               |
|                           |
=============================
```

info constantly shows a "% of things created" bar