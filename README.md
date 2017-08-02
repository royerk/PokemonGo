# PokemonGo

## Lazy Pidgey capturing policy for power leveling

As any trainer knows Pidgeys are the key to power leveling. They are everywhere and remain quite easy to capture even at level 20.

The downsize is, in my humble and lazy opinion, counting all those birds in your inventory to check if it is the right time to use a lucky-egg. Yes it takes only a minute to do it but this minute is much longer than a classic minute (obviously).

So I thought that some basic data science might help answer: **is there a way to restrict the Pidgeys counting and still use the lucky ASAP ?**

As a fellow trainer pointed out: "I only keep them when their cp is high (>260)". She came up with this idea empirically, keeping those Pidgeys ensure that her Pidgey count goes up one by one when Pidgey's candies goes up 3 times faster (*1 kept, 3 transfered = enough candies for 1 evolution*).

The jupyter-notebook explores Pidgey's CP distribution and evaluate the CP threshold that guaranties a proportionate growth between Pidgeys and Pidgeys' candies. Now when, if following the lazy policy, you hit 825 Pidgeys' candies you approximately have 75 Pidgeys ready to level up.

Improve CP calculation: **WIP**

Better article with cool graphs: **WIP**

Requirements:
- pandas
- seaborne (for prettiness)
- matplotlib
